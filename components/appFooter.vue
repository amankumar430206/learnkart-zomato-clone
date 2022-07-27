<template>
  <footer class="py-4">
    <div class="app-footer container">
      <div class="footer-header d-flex">
        <div class="brand-logo my-5">
          <img
            src="https://b.zmtcdn.com/web_assets/b40b97e677bc7b2ca77c58c61db266fe1603954218.png?fit=around|198:42&crop=198:42;*,*"
          />
        </div>
      </div>
      <div class="row mb-5">
        <div class="col">
          <h6 class="footer-section text-uppercase">about zomato</h6>
          <ul class="footer-section-list text-secondary m-0 p-0">
            <li class="text-capitalize fw-light">Who we are</li>
            <li class="text-capitalize fw-light">Blog</li>
            <li class="text-capitalize fw-light">Work With Us</li>
            <li class="text-capitalize fw-light">Investor Relations</li>
            <li class="text-capitalize fw-light">Report Fraud</li>
          </ul>
        </div>
        <div class="col">
          <h6 class="footer-section text-uppercase">about zomato</h6>
          <ul class="footer-section-list text-secondary m-0 p-0">
            <li class="text-capitalize fw-light">Who we are</li>
            <li class="text-capitalize fw-light">Blog</li>
            <li class="text-capitalize fw-light">Work With Us</li>
            <li class="text-capitalize fw-light">Investor Relations</li>
          </ul>
        </div>
        <div class="col">
          <h6 class="footer-section text-uppercase">about zomato</h6>
          <ul class="footer-section-list text-secondary m-0 p-0">
            <li class="text-capitalize fw-light">Who we are</li>
            <li class="text-capitalize fw-light">Blog</li>
          </ul>
          <h6 class="footer-section text-uppercase mt-3">FOR ENTERPRISES</h6>
          <ul class="footer-section-list text-secondary m-0 p-0">
            <li class="text-capitalize fw-light">Zomato For Work</li>
          </ul>
        </div>

        <div class="col">
          <h6 class="footer-section text-uppercase">LEARN MORE</h6>
          <ul class="footer-section-list text-secondary m-0 p-0">
            <li class="text-capitalize fw-light">privacy</li>
            <li class="text-capitalize fw-light">security</li>
            <li class="text-capitalize fw-light">terms</li>
            <li class="text-capitalize fw-light">sitemap</li>
          </ul>
        </div>

        <div class="col">
          <h6 class="footer-section text-uppercase">social links</h6>
          <div class="social-links my-3">
            <a href="#" class="social-link me-2">
              <img src="~/static/icons/logo-linkedin.svg" alt="" />
            </a>
            <a href="#" class="social-link me-2">
              <img src="~/static/icons/logo-youtube.svg" alt="" />
            </a>
            <a href="#" class="social-link me-2">
              <img src="~/static/icons/logo-instagram.svg" alt="" />
            </a>
            <a href="#" class="social-link me-2">
              <img src="~/static/icons/logo-facebook.svg" alt="" />
            </a>
            <a href="#" class="social-link me-2">
              <img src="~/static/icons/logo-twitter.svg" alt="" />
            </a>
          </div>
          <a href="#" class="d-block share-icon mb-3">
            <img
              src="https://b.zmtcdn.com/data/webuikit/9f0c85a5e33adb783fa0aef667075f9e1556003622.png"
              alt=""
            />
          </a>
          <a href="#" class="d-block share-icon">
            <img
              src="https://b.zmtcdn.com/data/webuikit/23e930757c3df49840c482a8638bf5c31556001144.png"
              alt=""
            />
          </a>
        </div>
      </div>
      <hr />
      <p class="text-muted">
        <small
          >By continuing past this page, you agree to our Terms of Service,
          Cookie Policy, Privacy Policy and Content Policies. All trademarks are
          properties of their respective owners. 2008-2022 © Zomato™ Ltd. All
          rights reserved.</small
        >
      </p>
    </div>
  </footer>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
* {
  font-size: 0.9rem;
}
footer {
  background: rgba(240, 240, 240, 0.664);
}
.brand-logo {
  img {
    height: 28px;
  }
}
ul {
  li {
    list-style: none;
    margin-bottom: 0.25rem;
  }
}

.social-link {
  img {
    height: 20px;
    width: auto;
  }
}

.share-icon {
  img {
    height: 40px;
  }
}
</style>
