  <template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Dropdown
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>
            <li class="nav-item">
              <a
                class="nav-link disabled"
                href="#"
                tabindex="-1"
                aria-disabled="true"
                >Disabled</a
              >
            </li>
          </ul>
          <form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search"
              aria-label="Search"
            />
            <button class="btn btn-outline-success" type="submit">
              Search
            </button>
          </form>
        </div>
      </div>
    </nav>
  </div>
  <!-- <div id="app">
    <div class="navbar">
      <a href="#">Home</a>
      <a href="#">Story</a>
      <a href="#">Blog</a>
      <a href="#">FAQs</a>
    </div> -->

  <!-- <div class="center example-nav">
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
      
    </div> -->
</template>

 <script>

export default {
  data: () => ({
    active: 0,

    colorx: "#BFCBE3",
  }),
};
</script>
<style>
.navbar {
  background-color: black;
  height: 80px;
  font-family: "TW cent MT";
}
</style>

