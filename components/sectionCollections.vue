<template>
  <section class="container py-5">
    <div class="collections-info">
      <h1 class="heading-md">Collections</h1>
      <p class="lead">
        Explore curated lists of top restaurants, cafes, pubs, and bars in
        Ahmedabad, based on trends
      </p>
    </div>
    <div class="collections-cards">
      <div class="row">
        <div v-for="i in 4" :key="i" class="col-lg-3">
          <div class="collection-card border rounded-3">
            <img
              class="collection-card-img img-fluid"
              src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Zm9vZHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60"
              alt=""
            />
            <div class="collection-card-content w-100 p-3 h-100 d-flex">
              <div class="info mt-auto">
                <h6 class="fw-light m-0">Newly Opened</h6>
                <div class="places d-flex align-items-center">
                  <p class="fw-light m-0">8 Places</p>
                  <img
                    class="icon ms-2"
                    src="~/static/icons/caret-icon-right.svg"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.heading-md {
  font-weight: 400;
}

.collection-card {
  height: 320px;
  position: relative;
  overflow: hidden;
  cursor: pointer;

  .icon {
    filter: invert(100%);
  }

  &-img {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 1;
  }

  &-content {
    color: #fff;
    position: absolute;
    bottom: 0px;
    left: 0px;
    z-index: 100;
    background: #232526;
    background: linear-gradient(
      0deg,
      rgba(0, 0, 0, 0.678) 5%,
      rgba(255, 255, 255, 0) 95%
    );
  }
}
</style>
