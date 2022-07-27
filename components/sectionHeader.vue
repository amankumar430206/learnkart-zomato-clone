<template>
  <div>
    <Header class="header">
      <AppNavbar />
      <div class="header-content text-center">
        <img
          class="img-fluid brand-logo"
          src="https://b.zmtcdn.com/web_assets/8313a97515fcb0447d2d77c276532a511583262271.png"
          alt=""
        />
        <h1 class="text-center text-white fw-light mt-4">
          Discover the best food & drinks in
          <span class="heading-md">Ahmedabad</span>
        </h1>
        <div class="explore d-flex justify-content-center mt-5">
          <div class="input-group input-group-lg mb-3">
            <span class="input-group-text bg-white border p-0">
              <img class="icon ms-2" src="~/static/icons/icon-location.svg" />
            </span>
            <input
              type="text"
              class="form-control input-location border-0 border-end"
              placeholder="Location"
            />
            <span class="input-group-text bg-white border p-0">
              <img class="icon ms-2" src="~/static/icons/icon-search.svg" />
            </span>
            <input
              type="text"
              class="form-control input-search border-0"
              placeholder="Search for restaurant, cuisine or a dish"
            />
          </div>
        </div>
      </div>
    </Header>
  </div>
</template>

<script>
import AppNavbar from './appNavbar.vue'
export default {
  components: { AppNavbar },
}
</script>

<style lang="scss" scoped>
.icon {
  width: 20px;
  height: auto;
}

.brand-logo {
  width: 280px;
  height: auto;
}

.header {
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-image: linear-gradient(
      to top,
      rgba(0, 0, 0, 0.13) 10%,
      rgba(0, 0, 0, 0.144) 45%,
      rgba(0, 0, 0, 0.164) 100%
    ),
    url('https://b.zmtcdn.com/web_assets/81f3ff974d82520780078ba1cfbd453a1583259680.png');
}

.form-control {
  border: 0;
  outline: none;
  box-shadow: none;
  font-size: 16px;

  &::placeholder {
    font-size: 14px;
  }
}

.input {
  &-location {
    max-width: 200px;
  }
}

.header-content {
  padding: 6rem 0 8rem 0;
}

.input-group {
  max-width: 820px;
  height: 50px;
}
</style>
