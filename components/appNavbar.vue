<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-transparent py-3">
      <div class="container">
        <a class="nav-link text-white" href="#">
          <img
            class="icon get-app-icon"
            src="~/static/icons/cell-phone.png"
            alt=""
          />
          <small>Get the App</small></a
        >
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
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item ms-3">
              <a class="nav-link fw-light" aria-current="page" href="#"
                >Investor Relations</a
              >
            </li>
            <li class="nav-item ms-3">
              <a class="nav-link fw-light" href="#">Add Restaturant</a>
            </li>
            <li class="nav-item ms-3">
              <a class="nav-link fw-light" href="#">Login</a>
            </li>
            <li class="nav-item ms-3">
              <a class="nav-link fw-light" href="#">Sign Up</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
.nav-link {
  color: #fff;
  font-size: 18px;
}

.get-app-icon {
  filter: invert(100%);
}
</style>
