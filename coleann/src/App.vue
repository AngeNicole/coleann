  <template>
  <div id="app">
    <div class="center example-nav">
      <input class="input-color" v-model="colorx" type="color" name="" id="">
      
      <vs-navbar not-line center-collapsed v-model="active" class="navbar"  :color="colorx"
      text-color="rgba(255,255,255,.6)"
      active-text-color="rgba(255,255,255,1)">
        <div slot="title">
          <vs-navbar-title>
            Navbar Color
          </vs-navbar-title>
        </div>
        <template #left>
          <img src="assets/c4.jpg" alt="">
        </template>
        <vs-navbar-item :active="active == 'guide'" id="guide">
          Shop
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'docs'" id="docs">
          About
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'components'" id="components">
          Blogs
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'license'" id="license">
          FAQs
        </vs-navbar-item>
        <template #right>
          <vs-button flat >Register</vs-button>
          <vs-button>Login</vs-button>
        </template>
      </vs-navbar>
      
    </div>
    </div>
  </template>

 <script>
  export default {
    data:() => ({
      active: 0,

      colorx:'#BFCBE3'
    })
  }
  </script>
<style lang="stylus">
 .input-color
  position relative
  display inline-block
 .navbar
  height 50px
  font 20px
  
</style>