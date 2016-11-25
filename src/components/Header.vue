<template lang="html">
  <section class="hero is-brown">
    <div class="columns">
      <div class="column is-one-quarter">
        <div class="notification is-brown photo">
          <a href="https://www.facebook.com/paiizz.mpk.1">
            <img src="dist/images/profile.png">
          </a>
        </div>
      </div>
      <div class="column">
        <div class="notification is-brown">
          <div class="hero-head">
            <div class="title-1 my-title text-white">
              Wanchanapon Thanwaranurak
            </div>
            <div class="title-2 my-title text-white sub-head">
              Software Engineer
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data () {
    return {}
  },
  computed: {},
  mounted () {},
  methods: {},
  components: {
  }
}
</script>

<style scoped>
  .my-title {
    text-align: center;
  }
  
  .title-1 {
    font-size: 44px;
  }
  
  .title-2 {
    font-size: 32px;
  }
  
  .head {
    padding-top: 3%;
    padding-bottom: 1%;
  }
  
  .sub-head {
    padding-top: 1%;
  }
  
  .is-brown {
    background-color: #302723;
  }
  
  .text-white {
    color: white;
  }
  
  .photo {
    margin-left: 15%;
    width: 250px;
  }
</style>