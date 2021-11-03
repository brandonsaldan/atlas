<template>
    <div class="">
        <a href="https://www.last.fm/user/shibbbe">
        <div class="rounded-lg p-2 listeninggreen items-center text-white leading-none lg:rounded-full flex lg:inline-flex">
            <i class="fab fa-spotify"></i>
            <div class="NowPlayingText">
                <span class="font-medium text-center flex-auto">Listening to 
                <span class="font-bold text-center flex-auto">{{ title }}</span>
                <span class="font-regular text-center flex-auto"> by </span>
                <span class="font-bold text-center flex-auto">{{ artist }}</span></span>
            </div>
        </div>
        </a>
    </div>
</template>

<script>
  export default {
    components: {
    },
    data() {
      return {
        title: "",
        artist: "",
      };
    },
    beforeMount() {
      window.location.search
      this.getParams()
      this.startPolling()
    },
    methods: {
      getParams() {
        this.username = "shibbbe"
      },
      startPolling() {
        this.fetch();
        window.setTimeout(() => {
          window.requestAnimationFrame(() => {
              this.startPolling();
          });
        }, 2500);
      },
      async fetch() {
        if(!this.username) {
          return
        }
        let apiKey = "0492a49dc25d76cc16ee280fc626e3e3";
        let res = await fetch(
          `//ws.audioscrobbler.com/2.0/?method=user.getrecenttracks&user=${this.username}&api_key=${apiKey}&format=json`
        );
        let data = await res.json();
        if (data.error) {
          this.isActive = false;
        } else {
          this.isActive = true;
          let track = data.recenttracks.track[0];
          this.artist = track.artist["#text"];
          this.title = track.name;
        }
      }
    }
  };
</script>