  <template>
  <div id="app">
    <div class="center example-nav">
      <vs-navbar not-line center-collapsed v-model="active" color="blue">
        <template #left>
          <img src="assets/c4.jpg" alt="">
        </template>
        <vs-navbar-item :active="active == 'guide'" id="guide">
          Guide
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'docs'" id="docs">
          Documents
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'components'" id="components">
          Components
        </vs-navbar-item>
        <vs-navbar-item :active="active == 'license'" id="license">
          license
        </vs-navbar-item>
        <template #right>
          <vs-button flat >Login</vs-button>
          <vs-button>Get Started</vs-button>
        </template>
      </vs-navbar>
      
    </div>
    </div>
  </template>

 <script>
  export default {
    data:() => ({
      active: 'guide'
    })
  }
  </script>
<style>
 #guide{
   color: red;
 }
</style>