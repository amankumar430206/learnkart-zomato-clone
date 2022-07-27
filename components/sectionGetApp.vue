<template>
  <section class="get-app-section py-3">
    <div class="get-app-wrapper container">
      <div class="row">
        <div class="col-8 offset-2">
          <div class="row p-0 m-0">
            <div class="col-3 d-flex me-5">
              <img
                class="get-app-img my-auto"
                src="https://b.zmtcdn.com/data/o2_assets/a500ffc2ab483bc6a550aa635f4e55531648107832.png"
                alt="get app image"
              />
            </div>
            <div class="col ms-4 ps-5">
              <h1 class="mb-4 heading-md">Get the Zomato app</h1>
              <p class="lead get-app-desc">
                <small
                  >We will send you a link, open it on your phone to download
                  the app</small
                >
              </p>

              <div class="share-app-link my-4">
                <div class="share-type-select d-flex">
                  <div class="form-check me-5">
                    <input
                      class="form-check-input"
                      type="radio"
                      value="email"
                      v-model="linkType"
                      id="email"
                    />
                    <label class="form-check-label fw-light" for="email">
                      Email
                    </label>
                  </div>
                  <div class="form-check">
                    <input
                      class="form-check-input"
                      type="radio"
                      value="phone"
                      v-model="linkType"
                      id="phone"
                    />
                    <label class="form-check-label fw-light" for="phone">
                      Phone
                    </label>
                  </div>
                </div>
                <div class="share-link-input d-flex mb-4 mt-3">
                  <input
                    v-show="linkType == 'email' || linkType == null"
                    type="email"
                    class="form-control"
                    placeholder="Email"
                  />
                  <input
                    v-show="linkType == 'phone'"
                    type="text"
                    class="form-control"
                    placeholder="+91 XXXXXXXXXX"
                  />
                  <button class="btn share-btn btn-danger ms-3 fw-light">
                    Share App Link
                  </button>
                </div>
              </div>
              <p class="text-muted">Download app from</p>
              <div class="download-buttons d-flex">
                <a href="#" class="me-3">
                  <img
                    class="download-btn"
                    src="https://b.zmtcdn.com/data/webuikit/23e930757c3df49840c482a8638bf5c31556001144.png"
                    alt="download from google play store"
                  />
                </a>
                <a href="#" class="">
                  <img
                    class="download-btn"
                    src="https://b.zmtcdn.com/data/webuikit/9f0c85a5e33adb783fa0aef667075f9e1556003622.png"
                    alt="download from app store"
                  />
                </a>
              </div>
            </div>
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
      linkType: null,
    }
  },
}
</script>

<style lang="scss" scoped>
.get-app-section {
  background: rgba(255, 247, 247, 0.712);
}

.get-app-img {
  height: 300px;
  width: auto;
}

.share-btn {
  width: 250px;
}

.download-btn {
  height: 40px;
}

.form-control {
  max-width: 300px;
  height: 45px;
  outline: none;
  box-shadow: none;
}
.form-check-label:hover {
  cursor: pointer;
}
.form-check-input {
  &:hover {
    cursor: pointer;
    border: 1px solid rgb(255, 58, 58);
  }

  &:checked {
    background-color: rgb(255, 58, 58);
    outline: none;
    border: 1px solid rgb(255, 58, 58);
    box-shadow: none;
  }
}

.get-app-wrapper {
  padding: 5rem 0;
}
</style>
