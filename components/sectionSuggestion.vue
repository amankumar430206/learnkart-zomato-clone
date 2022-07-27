<template>
  <section class="container py-5">
    <div class="row">
      <div class="col">
        <div class="card rounded-4">
          <img
            class="card-img-top rounded-top"
            src="https://b.zmtcdn.com/webFrontend/e5b8785c257af2a7f354f1addaf37e4e1647364814.jpeg?output-format=webp&fit=around|402:360&crop=402:360;*,*"
          />
          <div class="card-body">
            <h5 class="card-title">Order Online</h5>
            <p class="card-text fw-light">
              Stay home and order to your doorstep
            </p>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card rounded-4">
          <img
            class="card-img-top rounded-top"
            src="https://b.zmtcdn.com/webFrontend/d026b357feb0d63c997549f6398da8cc1647364915.jpeg?output-format=webp&fit=around|402:360&crop=402:360;*,*"
          />
          <div class="card-body">
            <h5 class="card-title">Dining</h5>
            <p class="card-text fw-light">
              View the city's favourite dining venues
            </p>
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

.card {
  transition: ease-in-out 0.2s;
  overflow: hidden;

  img {
    max-height: 200px;
    object-fit: cover;
  }

  &:hover {
    cursor: pointer;
    transform: scale(1.05);
  }
}
</style>
