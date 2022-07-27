<template>
  <section class="py-5">
    <div class="container">
      <h1 class="section-header-localities fw-light">
        Popular localities in and around <span class="">Ahmedabad</span>
      </h1>
      <div class="row mt-5">
        <div
          v-for="(local, index) in locals"
          :key="index"
          class="col-lg-4 mb-3 locality-card-wrapper"
        >
          <div
            class="locality-card border p-3 rounded-2 d-flex align-items-center"
          >
            <div class="locality">
              <h5 class="fw-light">{{ local.name }}</h5>
              <p class="m-0 p-0">{{ local.count }} Places</p>
            </div>
            <div class="right-arrow ms-auto">
              <img class="icon" src="~/static/icons/icon-right.svg" alt="" />
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div
            class="locality-card border p-3 rounded-2 d-flex align-items-center"
          >
            <h6 class="m-0 fw-light ms-auto me-auto">
              See More
              <img
                class="icon ms-2"
                src="~/static/icons/icon-down.svg"
                alt=""
              />
            </h6>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      locals: [
        {
          name: 'Bodakdev',
          count: 450,
        },
        {
          name: 'Navrangpura ',
          count: 385,
        },
        {
          name: 'Prahlad Nagar',
          count: 310,
        },
        {
          name: 'Satellite',
          count: 410,
        },
        {
          name: 'Bodakdev',
          count: 312,
        },
        {
          name: 'Bodakdev',
          count: 450,
        },
        {
          name: 'Bodakdev',
          count: 450,
        },
        {
          name: 'Bodakdev',
          count: 450,
        },
      ],
    }
  },
}
</script>

<style lang="scss" scoped>
.icon {
  width: 16px;
  height: auto;
}

.section-header-localities {
  span {
    font-weight: 400;
  }
}

.locality-card {
  height: 90px;

  &:hover {
    cursor: pointer;
    box-shadow: 0px 5px 10px rgba(228, 228, 228, 0.667);
  }
}
</style>
