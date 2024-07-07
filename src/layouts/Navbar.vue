<template>
  <nav class="navbar navbar-expand-md navbar-light bg-white shadow-sm px-md-0 px-sm-2 py-md-2 py-sm-2">
    <div class="container-fluid md:row d-md-flex justify-content-between px-md-5">
      <div class="d-flex justify-content-start align-items-center gap-2">
        <g-image
          alt="multividas, multividas api documentation, multividas threads, multividas status, multividas help center, multividas developer, multividas about us, multividas ads, multividas engineering blog, multividas developers documentation, multividas embed threadsmultividas, multividas api documentation, multividas threads, multividas status, multividas help center, multividas developer, multividas about us, multividas ads, multividas engineering blog, multividas developers documentation, multividas embed threadsmultividas, multividas api documentation, multividas threads, multividas status, multividas help center, multividas developer, multividas about us, multividas ads, multividas engineering blog, multividas developers documentation, multividas embed threadsmultividas, multividas api documentation, multividas threads, multividas status, multividas help center, multividas developer, multividas about us, multividas ads, multividas engineering blog, multividas developers documentation, multividas"
          src="~/assets/png/nav-multividas-blogging-platform-multividas-social-media-blog-multividas-posts-threads-multividas-comments-discussions-multividas-short-texts-multividas-social-blogging.svg"
          width="32"
        />
        <strong>
          <g-link to="/" class="navbar-brand text-primary fw-bold fs-4">Help Center</g-link>
        </strong>
      </div>

      <div class="navbar-block show-on-medium">
        <ul
          class="navbar-nav d-flex justify-container-end align-items-center gap-4"
        >
          <li class="nav-item">
            <g-link class="nav-link" to="/web">Web</g-link>
          </li>
          <li class="nav-item">
            <g-link class="nav-link" to="/moderation">Moderation</g-link>
          </li>
          <li class="nav-item">
            <g-link class="nav-link" to="/terminology">Terminology</g-link>
          </li>
          <li class="nav-item">
            <g-link class="nav-link" to="/community">Community</g-link>
          </li>
          <li class="nav-item">
            <g-link class="nav-link" to="/legal">Legal</g-link>
          </li>
          <li class="nav-item">
            <g-link class="nav-link" to="/contact">Contact</g-link>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link text-xxs dropdown-toggle"
              href="javascript:void(0)"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Multividas Settings
            </a>
            <ul class="dropdown-menu">
              <li class="drodpwn-menu-item">
                <g-link class="dropdown-item my-2" to="/settings" exact>Settings</g-link>
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link text-xxs dropdown-toggle"
              href="javascript:void(0)"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Multividas Premium
            </a>
            <ul class="dropdown-menu">
              <li class="drodpwn-menu-item">
                <g-link class="dropdown-item my-2" to="/premium" exact>Premium</g-link>
              </li>
              <li class="drodpwn-menu-item">
                <g-link
                  class="dropdown-item mb-2"
                  to="/premium/verified-organizations"
                  exact
                >
                  Verified Organizations
                </g-link>
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link text-xxs dropdown-toggle"
              href="javascript:void(0)"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              MultiChat
            </a>
            <ul class="dropdown-menu">
              <li class="drodpwn-menu-item">
                <g-link class="dropdown-item my-2" to="/multichat/security" exact>MultiChat Security</g-link>
              </li>
            </ul>
          </li>
          <li class="nav-item">
            <a
              class="btn btn-sm btn-light border text-xxs fw-medium px-3 py-2 rounded-4"
              href="https://multividas.com/"
              target="_blank"
            >
              Go to Multividas.com
            </a>
          </li>
        </ul>
      </div>

      <div class="navbar-block show-on-small">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="offcanvas"
          data-bs-target="#offcanvasMultividasNavbar"
          aria-controls="offcanvasMultividasNavbar"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div
          class="offcanvas offcanvas-start"
          tabindex="-1"
          id="offcanvasMultividasNavbar"
          aria-labelledby="offcanvasMultividasNavbarLabel"
        >
          <div class="offcanvas-header">
            <h5
              @click="redirectRoute('/')"
              role="button"
              class="offcanvas-title text-primary fw-bold"
              id="offcanvasMultividasNavbarLabel"
            >
              Multividas
            </h5>
            <button
              type="button"
              class="btn-close"
              data-bs-dismiss="offcanvas"
              aria-label="Close"
            ></button>
          </div>
          <div class="offcanvas-body p-0">
            <ul
              class="navbar-nav d-flex justify-container-end align-items-center gap-md-4"
            >
              <li
                class="nav-item border-top border-bottom w-100 w-full text-center"
              >
                <span
                  class="nav-link"
                  @click="redirectRoute('/web')"
                  :class="{ 'active--exact active': $route.path === '/web' }"
                  role="button"
                >
                  Web
                </span>
              </li>
              <li class="nav-item border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/moderation')"
                  :class="{
                    'active--exact active': $route.path === '/moderation',
                  }"
                  role="button"
                >
                  Moderation
                </span>
              </li>
              <li class="nav-item border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/terminology')"
                  :class="{
                    'active--exact active': $route.path === '/terminology',
                  }"
                  role="button"
                >
                  Terminology
                </span>
              </li>
              <li class="nav-item border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/community')"
                  :class="{
                    'active--exact active': $route.path === '/community',
                  }"
                  role="button"
                >
                  Community
                </span>
              </li>
              <li class="nav-item border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/legal')"
                  :class="{ 'active--exact active': $route.path === '/legal' }"
                  role="button"
                >
                  Legal
                </span>
              </li>
              <li class="nav-item border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/contact')"
                  :class="{
                    'active--exact active': $route.path === '/contact',
                  }"
                  role="button"
                >
                  Contact
                </span>
              </li>
              <li class="nav-item border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/settings')"
                  :class="{
                    'active--exact active': $route.path === '/settings',
                  }"
                  role="button"
                >
                  Settings
                </span>
              </li>
              <li class="nav-item dropdown border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/premium')"
                  :class="{
                    'active--exact active': $route.path === '/premium',
                  }"
                  role="button"
                  exact
                >
                  Premium
                </span>
              </li>
              <li class="nav-item dropdown border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/premium/verified-organizations')"
                  :class="{
                    active: $route.path === '/premium/verified-organizations',
                  }"
                  role="button"
                  exact
                >
                  Verified Organizations
                </span>
              </li>
              <li class="nav-item dropdown border-bottom w-100 w-full text-center">
                <span
                  class="nav-link"
                  @click="redirectRoute('/multichat/security')"
                  :class="{
                    active: $route.path === '/multichat/security',
                  }"
                  role="button"
                  exact
                >
                  MultiChat Security
                </span>
              </li>
              <li class="nav-item w-100 w-full text-center my-3">
                <a
                  class="btn btn-sm btn-light border text-xxs fw-medium px-3 py-2 rounded-4"
                  href="https://multividas.com/"
                  target="_blank"
                >
                  Go to Multividas.com
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  methods: {
    redirectRoute(name) {
      return (window.location.href = name);
    },
  },
};
</script>

<style scoped>
/* Default styles for all screen sizes */
.navbar-block {
  display: none;
}

/* Display elements on small screens */
@media (max-width: 767px) {
  .show-on-small {
    display: block;
  }
}

/* Display elements on medium and larger screens */
@media (min-width: 768px) {
  .show-on-medium {
    display: block;
  }
}
</style>
