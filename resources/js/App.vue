<template>
  <div>
    <!--    Main Content-->
    <main class="main" id="top">
      <nav class="navbar navbar-vertical navbar-expand-lg">
        <div class="collapse navbar-collapse" id="navbarVerticalCollapse">
          <!-- scrollbar removed-->
          <div class="navbar-vertical-content">
            <ul class="navbar-nav flex-column" id="navbarVerticalNav">
              <!-- parent pages-->
              <div class="nav-item-wrapper">
                <router-link
                  class="nav-link label-1"
                  to="/"
                  role="button"
                  data-bs-toggle=""
                  aria-expanded="false"
                >
                  <div class="d-flex align-items-center">
                    <span class="nav-link-icon"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16px"
                        height="16px"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="feather feather-message-square"
                      >
                        <path
                          d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"
                        ></path>
                      </svg> </span
                    ><span class="nav-link-text-wrapper"
                      ><span class="nav-link-text"> ສະຕັອກ​ສິນ​ຄ້າ</span></span
                    >
                  </div>
                </router-link>
              </div>

              <div class="nav-item-wrapper">
                <router-link
                  class="nav-link label-1"
                  to="pos"
                  role="button"
                  data-bs-toggle=""
                  aria-expanded="false"
                >
                  <div class="d-flex align-items-center">
                    <span class="nav-link-icon"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16px"
                        height="16px"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="feather feather-calendar"
                      >
                        <rect
                          x="3"
                          y="4"
                          width="18"
                          height="18"
                          rx="2"
                          ry="2"
                        ></rect>
                        <line x1="16" y1="2" x2="16" y2="6"></line>
                        <line x1="8" y1="2" x2="8" y2="6"></line>
                        <line x1="3" y1="10" x2="21" y2="10"></line>
                      </svg> </span
                    ><span class="nav-link-text-wrapper"
                      ><span class="nav-link-text"> ຂາຍ​ສິນ​ຄ້າ</span></span
                    >
                  </div>
                </router-link>
              </div>

              <div class="nav-item-wrapper">
                <router-link
                  class="nav-link label-1"
                  to="transection"
                  role="button"
                  data-bs-toggle=""
                  aria-expanded="false"
                >
                  <div class="d-flex align-items-center">
                    <span class="nav-link-icon"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16px"
                        height="16px"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="feather feather-calendar"
                      >
                        <rect
                          x="3"
                          y="4"
                          width="18"
                          height="18"
                          rx="2"
                          ry="2"
                        ></rect>
                        <line x1="16" y1="2" x2="16" y2="6"></line>
                        <line x1="8" y1="2" x2="8" y2="6"></line>
                        <line x1="3" y1="10" x2="21" y2="10"></line>
                      </svg> </span
                    ><span class="nav-link-text-wrapper"
                      ><span class="nav-link-text"> ການ​ເຄື່ອນ​ໄຫວ</span></span
                    >
                  </div>
                </router-link>
              </div>

              <div class="nav-item-wrapper">
                <router-link
                  class="nav-link label-1"
                  to="report"
                  role="button"
                  data-bs-toggle=""
                  aria-expanded="false"
                >
                  <div class="d-flex align-items-center">
                    <span class="nav-link-icon"
                      ><svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16px"
                        height="16px"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="feather feather-calendar"
                      >
                        <rect
                          x="3"
                          y="4"
                          width="18"
                          height="18"
                          rx="2"
                          ry="2"
                        ></rect>
                        <line x1="16" y1="2" x2="16" y2="6"></line>
                        <line x1="8" y1="2" x2="8" y2="6"></line>
                        <line x1="3" y1="10" x2="21" y2="10"></line>
                      </svg> </span
                    ><span class="nav-link-text-wrapper"
                      ><span class="nav-link-text"> ລາຍ​ງານ</span></span
                    >
                  </div>
                </router-link>
              </div>
            </ul>
          </div>
        </div>
        <div class="navbar-vertical-footer">
          <button
            class="btn navbar-vertical-toggle border-0 fw-semi-bold w-100 white-space-nowrap d-flex align-items-center"
          >
            <span class="uil uil-left-arrow-to-left fs-0"></span
            ><span class="uil uil-arrow-from-right fs-0"></span
            ><span class="navbar-vertical-footer-text ms-2"> ຫຍໍ້​ລົງ</span>
          </button>
        </div>
      </nav>

      <!-- LOGO AND HEAD -->
      <nav
        class="navbar navbar-top fixed-top navbar-expand-lg"
        id="navbarCombo"
        data-navbar-top="combo"
        data-move-target="#navbarVerticalNav"
      >
        <div class="navbar-logo">
          <button
            class="btn navbar-toggler navbar-toggler-humburger-icon hover-bg-transparent"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarVerticalCollapse"
            aria-controls="navbarVerticalCollapse"
            aria-expanded="false"
            aria-label="Toggle Navigation"
          >
            <span class="navbar-toggle-icon"
              ><span class="toggle-line"></span
            ></span>
          </button>
          <a class="navbar-brand me-1 me-sm-3" href="assets/index.html">
            <div class="d-flex align-items-center">
              <div class="d-flex align-items-center">
                <img src="assets/img/icons/logo.png" alt="phoenix" width="27" />
                <p class="logo-text ms-2 d-none d-sm-block">MiniStore</p>
              </div>
            </div>
          </a>
        </div>
        <div
          class="collapse navbar-collapse navbar-top-collapse order-1 order-lg-0 justify-content-center"
          id="navbarTopCollapse"
        ></div>

        <!-- ແຈ້ງ​ເຕືອນ -->
        <ul class="navbar-nav navbar-nav-icons flex-row">
          <li class="nav-item">
            <div class="theme-control-toggle fa-icon-wait px-2">
              <input
                class="form-check-input ms-0 theme-control-toggle-input"
                type="checkbox"
                data-theme-control="phoenixTheme"
                value="dark"
                id="themeControlToggle"
              /><label
                class="mb-0 theme-control-toggle-label theme-control-toggle-light"
                for="themeControlToggle"
                data-bs-toggle="tooltip"
                data-bs-placement="left"
                aria-label="Switch theme"
                data-bs-original-title="Switch theme"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16px"
                  height="16px"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="feather feather-moon icon"
                >
                  <path
                    d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"
                  ></path></svg></label
              ><label
                class="mb-0 theme-control-toggle-label theme-control-toggle-dark"
                for="themeControlToggle"
                data-bs-toggle="tooltip"
                data-bs-placement="left"
                aria-label="Switch theme"
                data-bs-original-title="Switch theme"
                ><svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16px"
                  height="16px"
                  viewBox="0 0 24 24"
                  fill="none"
                  stroke="currentColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="feather feather-sun icon"
                >
                  <circle cx="12" cy="12" r="5"></circle>
                  <line x1="12" y1="1" x2="12" y2="3"></line>
                  <line x1="12" y1="21" x2="12" y2="23"></line>
                  <line x1="4.22" y1="4.22" x2="5.64" y2="5.64"></line>
                  <line x1="18.36" y1="18.36" x2="19.78" y2="19.78"></line>
                  <line x1="1" y1="12" x2="3" y2="12"></line>
                  <line x1="21" y1="12" x2="23" y2="12"></line>
                  <line x1="4.22" y1="19.78" x2="5.64" y2="18.36"></line>
                  <line x1="18.36" y1="5.64" x2="19.78" y2="4.22"></line></svg
              ></label>
            </div>
          </li>
          <li class="nav-item">
            <a
              class="nav-link"
              href="#"
              data-bs-toggle="modal"
              data-bs-target="#searchBoxModal"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                width="16px"
                height="16px"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-search"
                style="height: 19px; width: 19px; margin-bottom: 2px"
              >
                <circle cx="11" cy="11" r="8"></circle>
                <line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg
            ></a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link"
              href="#"
              style="min-width: 2.5rem"
              role="button"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
              data-bs-auto-close="outside"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                width="16px"
                height="16px"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
                class="feather feather-bell"
                style="height: 20px; width: 20px"
              >
                <path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"></path>
                <path d="M13.73 21a2 2 0 0 1-3.46 0"></path></svg
            ></a>
            <div
              class="dropdown-menu dropdown-menu-end notification-dropdown-menu py-0 shadow border border-300 navbar-dropdown-caret"
              id="navbarDropdownNotfication"
              aria-labelledby="navbarDropdownNotfication"
            >
              <div class="card position-relative border-0">
                <div class="card-header p-2">
                  <div class="d-flex justify-content-between">
                    <h5 class="text-black mb-0">Notificatons</h5>
                    <button
                      class="btn btn-link p-0 fs--1 fw-normal"
                      type="button"
                    >
                      Mark all as read
                    </button>
                  </div>
                </div>
                <div class="card-body p-0">
                  <div
                    class="scrollbar-overlay"
                    style="height: 27rem"
                    data-simplebar="init"
                  >
                    <div class="simplebar-wrapper" style="margin: 0px">
                      <div class="simplebar-height-auto-observer-wrapper">
                        <div class="simplebar-height-auto-observer"></div>
                      </div>
                      <div class="simplebar-mask">
                        <div
                          class="simplebar-offset"
                          style="right: 0px; bottom: 0px"
                        >
                          <div
                            class="simplebar-content-wrapper"
                            tabindex="0"
                            role="region"
                            aria-label="scrollable content"
                            style="height: auto; overflow: hidden"
                          >
                            <div class="simplebar-content" style="padding: 0px">
                              <div class="border-300">
                                <div
                                  class="px-2 px-sm-3 py-3 border-300 notification-card position-relative read border-bottom"
                                >
                                  <div
                                    class="d-flex align-items-center justify-content-between position-relative"
                                  >
                                    <div class="d-flex">
                                      <div
                                        class="avatar avatar-m status-online me-3"
                                      >
                                        <img
                                          class="rounded-circle"
                                          src="assets/img/team/40x40/30.webp"
                                          alt=""
                                        />
                                      </div>
                                      <div class="flex-1 me-sm-3">
                                        <h4 class="fs--1 text-black">
                                          Jessie Samson
                                        </h4>
                                        <p
                                          class="fs--1 text-1000 mb-2 mb-sm-3 fw-normal"
                                        >
                                          <span class="me-1 fs--2">💬</span
                                          >Mentioned you in a comment.<span
                                            class="ms-2 text-400 fw-bold fs--2"
                                            >10m</span
                                          >
                                        </p>
                                        <p class="text-800 fs--1 mb-0">
                                          <svg
                                            class="svg-inline--fa fa-clock me-1"
                                            aria-hidden="true"
                                            focusable="false"
                                            data-prefix="fas"
                                            data-icon="clock"
                                            role="img"
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 512 512"
                                            data-fa-i2svg=""
                                          >
                                            <path
                                              fill="currentColor"
                                              d="M256 512C114.6 512 0 397.4 0 256C0 114.6 114.6 0 256 0C397.4 0 512 114.6 512 256C512 397.4 397.4 512 256 512zM232 256C232 264 236 271.5 242.7 275.1L338.7 339.1C349.7 347.3 364.6 344.3 371.1 333.3C379.3 322.3 376.3 307.4 365.3 300L280 243.2V120C280 106.7 269.3 96 255.1 96C242.7 96 231.1 106.7 231.1 120L232 256z"
                                            ></path></svg
                                          ><!-- <span class="me-1 fas fa-clock"></span> Font Awesome fontawesome.com --><span
                                            class="fw-bold"
                                            >10:41 AM </span
                                          >August 7,2021
                                        </p>
                                      </div>
                                    </div>
                                    <div
                                      class="font-sans-serif d-none d-sm-block"
                                    >
                                      <button
                                        class="btn fs--2 btn-sm dropdown-toggle dropdown-caret-none transition-none notification-dropdown-toggle"
                                        type="button"
                                        data-bs-toggle="dropdown"
                                        data-boundary="window"
                                        aria-haspopup="true"
                                        aria-expanded="false"
                                        data-bs-reference="parent"
                                      >
                                        <svg
                                          class="svg-inline--fa fa-ellipsis fs--2 text-900"
                                          aria-hidden="true"
                                          focusable="false"
                                          data-prefix="fas"
                                          data-icon="ellipsis"
                                          role="img"
                                          xmlns="http://www.w3.org/2000/svg"
                                          viewBox="0 0 448 512"
                                          data-fa-i2svg=""
                                        >
                                          <path
                                            fill="currentColor"
                                            d="M120 256C120 286.9 94.93 312 64 312C33.07 312 8 286.9 8 256C8 225.1 33.07 200 64 200C94.93 200 120 225.1 120 256zM280 256C280 286.9 254.9 312 224 312C193.1 312 168 286.9 168 256C168 225.1 193.1 200 224 200C254.9 200 280 225.1 280 256zM328 256C328 225.1 353.1 200 384 200C414.9 200 440 225.1 440 256C440 286.9 414.9 312 384 312C353.1 312 328 286.9 328 256z"
                                          ></path></svg
                                        ><!-- <span class="fas fa-ellipsis-h fs--2 text-900"></span> Font Awesome fontawesome.com -->
                                      </button>
                                      <div
                                        class="dropdown-menu dropdown-menu-end py-2"
                                      >
                                        <a class="dropdown-item" href="#!"
                                          >Mark as unread</a
                                        >
                                      </div>
                                    </div>
                                  </div>
                                </div>
                                <div
                                  class="px-2 px-sm-3 py-3 border-300 notification-card position-relative unread border-bottom"
                                >
                                  <div
                                    class="d-flex align-items-center justify-content-between position-relative"
                                  >
                                    <div class="d-flex">
                                      <div
                                        class="avatar avatar-m status-online me-3"
                                      >
                                        <div class="avatar-name rounded-circle">
                                          <span>J</span>
                                        </div>
                                      </div>
                                      <div class="flex-1 me-sm-3">
                                        <h4 class="fs--1 text-black">
                                          Jane Foster
                                        </h4>
                                        <p
                                          class="fs--1 text-1000 mb-2 mb-sm-3 fw-normal"
                                        >
                                          <span class="me-1 fs--2">📅</span
                                          >Created an event.<span
                                            class="ms-2 text-400 fw-bold fs--2"
                                            >20m</span
                                          >
                                        </p>
                                        <p class="text-800 fs--1 mb-0">
                                          <svg
                                            class="svg-inline--fa fa-clock me-1"
                                            aria-hidden="true"
                                            focusable="false"
                                            data-prefix="fas"
                                            data-icon="clock"
                                            role="img"
                                            xmlns="http://www.w3.org/2000/svg"
                                            viewBox="0 0 512 512"
                                            data-fa-i2svg=""
                                          >
                                            <path
                                              fill="currentColor"
                                              d="M256 512C114.6 512 0 397.4 0 256C0 114.6 114.6 0 256 0C397.4 0 512 114.6 512 256C512 397.4 397.4 512 256 512zM232 256C232 264 236 271.5 242.7 275.1L338.7 339.1C349.7 347.3 364.6 344.3 371.1 333.3C379.3 322.3 376.3 307.4 365.3 300L280 243.2V120C280 106.7 269.3 96 255.1 96C242.7 96 231.1 106.7 231.1 120L232 256z"
                                            ></path></svg
                                          ><!-- <span class="me-1 fas fa-clock"></span> Font Awesome fontawesome.com --><span
                                            class="fw-bold"
                                            >10:20 AM </span
                                          >August 7,2021
                                        </p>
                                      </div>
                                    </div>
                                    <div
                                      class="font-sans-serif d-none d-sm-block"
                                    >
                                      <button
                                        class="btn fs--2 btn-sm dropdown-toggle dropdown-caret-none transition-none notification-dropdown-toggle"
                                        type="button"
                                        data-bs-toggle="dropdown"
                                        data-boundary="window"
                                        aria-haspopup="true"
                                        aria-expanded="false"
                                        data-bs-reference="parent"
                                      >
                                        <svg
                                          class="svg-inline--fa fa-ellipsis fs--2 text-900"
                                          aria-hidden="true"
                                          focusable="false"
                                          data-prefix="fas"
                                          data-icon="ellipsis"
                                          role="img"
                                          xmlns="http://www.w3.org/2000/svg"
                                          viewBox="0 0 448 512"
                                          data-fa-i2svg=""
                                        >
                                          <path
                                            fill="currentColor"
                                            d="M120 256C120 286.9 94.93 312 64 312C33.07 312 8 286.9 8 256C8 225.1 33.07 200 64 200C94.93 200 120 225.1 120 256zM280 256C280 286.9 254.9 312 224 312C193.1 312 168 286.9 168 256C168 225.1 193.1 200 224 200C254.9 200 280 225.1 280 256zM328 256C328 225.1 353.1 200 384 200C414.9 200 440 225.1 440 256C440 286.9 414.9 312 384 312C353.1 312 328 286.9 328 256z"
                                          ></path></svg
                                        ><!-- <span class="fas fa-ellipsis-h fs--2 text-900"></span> Font Awesome fontawesome.com -->
                                      </button>
                                      <div
                                        class="dropdown-menu dropdown-menu-end py-2"
                                      >
                                        <a class="dropdown-item" href="#!"
                                          >Mark as unread</a
                                        >
                                      </div>
                                    </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div
                        class="simplebar-placeholder"
                        style="width: 0px; height: 0px"
                      ></div>
                    </div>
                    <div
                      class="simplebar-track simplebar-horizontal"
                      style="visibility: hidden"
                    >
                      <div
                        class="simplebar-scrollbar"
                        style="width: 0px; display: none"
                      ></div>
                    </div>
                    <div
                      class="simplebar-track simplebar-vertical"
                      style="visibility: hidden"
                    >
                      <div
                        class="simplebar-scrollbar"
                        style="height: 0px; display: none"
                      ></div>
                    </div>
                  </div>
                </div>
                <div class="card-footer p-0 border-top border-0">
                  <div class="my-2 text-center fw-bold fs--2 text-600">
                    <a class="fw-bolder" href="assets/pages/notifications.html"
                      >Notification history</a
                    >
                  </div>
                </div>
              </div>
            </div>
          </li>

          <!-- Profile -->
          <li class="nav-item dropdown">
            <a
              class="nav-link lh-1 pe-0"
              id="navbarDropdownUser"
              href="#!"
              role="button"
              data-bs-toggle="dropdown"
              data-bs-auto-close="outside"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <div class="avatar avatar-l">
                <img class="rounded-circle" src="assets/img/bg/me.jpg" alt="" />
              </div>
            </a>
            <div
              class="dropdown-menu dropdown-menu-end navbar-dropdown-caret py-0 dropdown-profile shadow border border-300"
              aria-labelledby="navbarDropdownUser"
            >
              <div class="card position-relative border-0">
                <div class="card-body p-0">
                  <div class="text-center pt-4 pb-3">
                    <div class="avatar avatar-xl">
                      <img
                        class="rounded-circle"
                        src="assets/img/mine-rem.png"
                        alt=""
                      />
                    </div>
                    <h6 class="mt-2 text-black">zomma Phiwthammavong</h6>
                  </div>
                  <div class="mb-3 mx-3">
                    <input
                      class="form-control form-control-sm"
                      id="statusUpdateInput"
                      type="text"
                      placeholder="Update your status"
                    />
                  </div>
                </div>
                <div class="overflow-auto scrollbar" style="height: 10rem">
                  <ul class="nav d-flex flex-column mb-2 pb-1">
                    <li class="nav-item">
                      <a class="nav-link px-3" href="#!">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16px"
                          height="16px"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          class="feather feather-user me-2 text-900"
                        >
                          <path
                            d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"
                          ></path>
                          <circle cx="12" cy="7" r="4"></circle></svg
                        ><span> ໂປ​ຣ​ຟາຍ​ລ໌</span></a
                      >
                    </li>
                    <li class="nav-item">
                      <a class="nav-link px-3" href="#!"
                        ><svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16px"
                          height="16px"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          class="feather feather-pie-chart me-2 text-900"
                        >
                          <path d="M21.21 15.89A10 10 0 1 1 8 2.83"></path>
                          <path d="M22 12A10 10 0 0 0 12 2v10z"></path></svg
                        >Dashboard</a
                      >
                    </li>
                    <li class="nav-item">
                      <a class="nav-link px-3" href="#!">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16px"
                          height="16px"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          class="feather feather-lock me-2 text-900"
                        >
                          <rect
                            x="3"
                            y="11"
                            width="18"
                            height="11"
                            rx="2"
                            ry="2"
                          ></rect>
                          <path d="M7 11V7a5 5 0 0 1 10 0v4"></path></svg
                        >Posts &amp; Activity</a
                      >
                    </li>
                    <li class="nav-item">
                      <a class="nav-link px-3" href="#!">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16px"
                          height="16px"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          class="feather feather-settings me-2 text-900"
                        >
                          <circle cx="12" cy="12" r="3"></circle>
                          <path
                            d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1 0 2.83 2 2 0 0 1-2.83 0l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-2 2 2 2 0 0 1-2-2v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83 0 2 2 0 0 1 0-2.83l.06-.06a1.65 1.65 0 0 0 .33-1.82 1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1-2-2 2 2 0 0 1 2-2h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 0-2.83 2 2 0 0 1 2.83 0l.06.06a1.65 1.65 0 0 0 1.82.33H9a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 0 2 2 0 0 1 0 2.83l-.06.06a1.65 1.65 0 0 0-.33 1.82V9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 2 2 2 2 0 0 1-2 2h-.09a1.65 1.65 0 0 0-1.51 1z"
                          ></path></svg
                        >Settings &amp; Privacy
                      </a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link px-3" href="#!">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16px"
                          height="16px"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          class="feather feather-help-circle me-2 text-900"
                        >
                          <circle cx="12" cy="12" r="10"></circle>
                          <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                          <line x1="12" y1="17" x2="12.01" y2="17"></line></svg
                        >Help Center</a
                      >
                    </li>
                    <li class="nav-item">
                      <a class="nav-link px-3" href="#!">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16px"
                          height="16px"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          class="feather feather-globe me-2 text-900"
                        >
                          <circle cx="12" cy="12" r="10"></circle>
                          <line x1="2" y1="12" x2="22" y2="12"></line>
                          <path
                            d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"
                          ></path></svg
                        >Language</a
                      >
                    </li>
                  </ul>
                </div>
                <div class="card-footer p-0 border-top">
                  <ul class="nav d-flex flex-column my-3">
                    <li class="nav-item">
                      <a class="nav-link px-3" href="#!">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16px"
                          height="16px"
                          viewBox="0 0 24 24"
                          fill="none"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          class="feather feather-user-plus me-2 text-900"
                        >
                          <path
                            d="M16 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"
                          ></path>
                          <circle cx="8.5" cy="7" r="4"></circle>
                          <line x1="20" y1="8" x2="20" y2="14"></line>
                          <line x1="23" y1="11" x2="17" y2="11"></line></svg
                        >Add another account</a
                      >
                    </li>
                  </ul>
                  <hr />
                  <div class="px-3">
                    <a
                      class="btn btn-phoenix-secondary d-flex flex-center w-100"
                      href="#!"
                    >
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16px"
                        height="16px"
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="2"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        class="feather feather-log-out me-2"
                      >
                        <path
                          d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"
                        ></path>
                        <polyline points="16 17 21 12 16 7"></polyline>
                        <line x1="21" y1="12" x2="9" y2="12"></line></svg
                      >Sign out</a
                    >
                  </div>
                  <div class="my-2 text-center fw-bold fs--2 text-600">
                    <a class="text-600 me-1" href="#!">Privacy policy</a>•<a
                      class="text-600 mx-1"
                      href="#!"
                      >Terms</a
                    >•<a class="text-600 ms-1" href="#!">Cookies</a>
                  </div>
                </div>
              </div>
            </div>
          </li>
        </ul>
      </nav>

      <!-- Search  -->
      <div
        class="modal fade"
        id="searchBoxModal"
        tabindex="-1"
        aria-hidden="true"
        data-bs-backdrop="true"
        data-phoenix-modal="data-phoenix-modal"
        style="--phoenix-backdrop-opacity: 1"
      >
        <div class="modal-dialog">
          <div class="modal-content mt-15 rounded-pill">
            <div class="modal-body p-0">
              <div
                class="search-box navbar-top-search-box"
                data-list='{"valueNames":["title"]}'
                style="width: auto"
              >
                <form
                  class="position-relative"
                  data-bs-toggle="search"
                  data-bs-display="static"
                  aria-expanded="false"
                >
                  <input
                    class="form-control search-input fuzzy-search rounded-pill form-control-lg"
                    type="search"
                    placeholder="Search..."
                    aria-label="Search"
                  />
                  <svg
                    class="svg-inline--fa fa-magnifying-glass search-box-icon"
                    aria-hidden="true"
                    focusable="false"
                    data-prefix="fas"
                    data-icon="magnifying-glass"
                    role="img"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 512 512"
                    data-fa-i2svg=""
                  >
                    <path
                      fill="currentColor"
                      d="M500.3 443.7l-119.7-119.7c27.22-40.41 40.65-90.9 33.46-144.7C401.8 87.79 326.8 13.32 235.2 1.723C99.01-15.51-15.51 99.01 1.724 235.2c11.6 91.64 86.08 166.7 177.6 178.9c53.8 7.189 104.3-6.236 144.7-33.46l119.7 119.7c15.62 15.62 40.95 15.62 56.57 0C515.9 484.7 515.9 459.3 500.3 443.7zM79.1 208c0-70.58 57.42-128 128-128s128 57.42 128 128c0 70.58-57.42 128-128 128S79.1 278.6 79.1 208z"
                    ></path></svg
                  ><!-- <span class="fas fa-search search-box-icon"></span> Font Awesome fontawesome.com -->
                </form>
                <div
                  class="btn-close position-absolute end-0 top-50 translate-middle cursor-pointer shadow-none"
                  data-bs-dismiss="search"
                >
                  <button
                    class="btn btn-link btn-close-falcon p-0"
                    aria-label="Close"
                  ></button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- content -->
      <div class="content">
        <router-view></router-view>
      </div>
    </main>
    <!-- ===============================================-->
    <!--    End of Main Content-->
    <!-- ===============================================-->

    <div
      class="offcanvas offcanvas-end settings-panel border-0"
      id="settings-offcanvas"
      tabindex="-1"
      aria-labelledby="settings-offcanvas"
    >
      <div class="offcanvas-header align-items-start border-bottom flex-column">
        <div
          class="pt-1 w-100 mb-6 d-flex justify-content-between align-items-start"
        >
          <div>
            <h5 class="mb-2 me-2 lh-sm">
              <svg
                class="svg-inline--fa fa-palette me-2 fs-0"
                aria-hidden="true"
                focusable="false"
                data-prefix="fas"
                data-icon="palette"
                role="img"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 512 512"
                data-fa-i2svg=""
              >
                <path
                  fill="currentColor"
                  d="M512 255.1C512 256.9 511.1 257.8 511.1 258.7C511.6 295.2 478.4 319.1 441.9 319.1H344C317.5 319.1 296 341.5 296 368C296 371.4 296.4 374.7 297 377.9C299.2 388.1 303.5 397.1 307.9 407.8C313.9 421.6 320 435.3 320 449.8C320 481.7 298.4 510.5 266.6 511.8C263.1 511.9 259.5 512 256 512C114.6 512 0 397.4 0 256C0 114.6 114.6 0 256 0C397.4 0 512 114.6 512 256V255.1zM96 255.1C78.33 255.1 64 270.3 64 287.1C64 305.7 78.33 319.1 96 319.1C113.7 319.1 128 305.7 128 287.1C128 270.3 113.7 255.1 96 255.1zM128 191.1C145.7 191.1 160 177.7 160 159.1C160 142.3 145.7 127.1 128 127.1C110.3 127.1 96 142.3 96 159.1C96 177.7 110.3 191.1 128 191.1zM256 63.1C238.3 63.1 224 78.33 224 95.1C224 113.7 238.3 127.1 256 127.1C273.7 127.1 288 113.7 288 95.1C288 78.33 273.7 63.1 256 63.1zM384 191.1C401.7 191.1 416 177.7 416 159.1C416 142.3 401.7 127.1 384 127.1C366.3 127.1 352 142.3 352 159.1C352 177.7 366.3 191.1 384 191.1z"
                ></path></svg
              ><!-- <span class="fas fa-palette me-2 fs-0"></span> Font Awesome fontawesome.com -->Theme
              Customizer
            </h5>
            <p class="mb-0 fs--1">
              Explore different styles according to your preferences
            </p>
          </div>
          <button
            class="btn p-1 fw-bolder"
            type="button"
            data-bs-dismiss="offcanvas"
            aria-label="Close"
          >
            <svg
              class="svg-inline--fa fa-xmark fs-0"
              aria-hidden="true"
              focusable="false"
              data-prefix="fas"
              data-icon="xmark"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 320 512"
              data-fa-i2svg=""
            >
              <path
                fill="currentColor"
                d="M310.6 361.4c12.5 12.5 12.5 32.75 0 45.25C304.4 412.9 296.2 416 288 416s-16.38-3.125-22.62-9.375L160 301.3L54.63 406.6C48.38 412.9 40.19 416 32 416S15.63 412.9 9.375 406.6c-12.5-12.5-12.5-32.75 0-45.25l105.4-105.4L9.375 150.6c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0L160 210.8l105.4-105.4c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25l-105.4 105.4L310.6 361.4z"
              ></path></svg
            ><!-- <span class="fas fa-times fs-0"> </span> Font Awesome fontawesome.com -->
          </button>
        </div>
        <button
          class="btn btn-phoenix-secondary w-100"
          data-theme-control="reset"
        >
          <svg
            class="svg-inline--fa fa-arrows-rotate me-2 fs--2"
            aria-hidden="true"
            focusable="false"
            data-prefix="fas"
            data-icon="arrows-rotate"
            role="img"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 512 512"
            data-fa-i2svg=""
          >
            <path
              fill="currentColor"
              d="M464 16c-17.67 0-32 14.31-32 32v74.09C392.1 66.52 327.4 32 256 32C161.5 32 78.59 92.34 49.58 182.2c-5.438 16.81 3.797 34.88 20.61 40.28c16.89 5.5 34.88-3.812 40.3-20.59C130.9 138.5 189.4 96 256 96c50.5 0 96.26 24.55 124.4 64H336c-17.67 0-32 14.31-32 32s14.33 32 32 32h128c17.67 0 32-14.31 32-32V48C496 30.31 481.7 16 464 16zM441.8 289.6c-16.92-5.438-34.88 3.812-40.3 20.59C381.1 373.5 322.6 416 256 416c-50.5 0-96.25-24.55-124.4-64H176c17.67 0 32-14.31 32-32s-14.33-32-32-32h-128c-17.67 0-32 14.31-32 32v144c0 17.69 14.33 32 32 32s32-14.31 32-32v-74.09C119.9 445.5 184.6 480 255.1 480c94.45 0 177.4-60.34 206.4-150.2C467.9 313 458.6 294.1 441.8 289.6z"
            ></path></svg
          ><!-- <span class="fas fa-arrows-rotate me-2 fs--2"></span> Font Awesome fontawesome.com -->Reset
          to default
        </button>
      </div>
      <div class="offcanvas-body scrollbar px-card" id="themeController">
        <div class="setting-panel-item mt-0">
          <h5 class="setting-panel-item-title">Color Scheme</h5>
          <div class="row gx-2">
            <div class="col-6">
              <input
                class="btn-check"
                id="themeSwitcherLight"
                name="theme-color"
                type="radio"
                value="light"
                data-theme-control="phoenixTheme"
                checked="true"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="themeSwitcherLight"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype mb-0"
                    src="assets/assets/img/generic/default-light.png"
                    alt="" /></span
                ><span class="label-text">Light</span></label
              >
            </div>
            <div class="col-6">
              <input
                class="btn-check"
                id="themeSwitcherDark"
                name="theme-color"
                type="radio"
                value="dark"
                data-theme-control="phoenixTheme"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="themeSwitcherDark"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype mb-0"
                    src="assets/assets/img/generic/default-dark.png"
                    alt="" /></span
                ><span class="label-text"> Dark</span></label
              >
            </div>
          </div>
        </div>
        <div class="border rounded-3 p-4 setting-panel-item bg-white">
          <div class="d-flex justify-content-between align-items-center">
            <h5 class="setting-panel-item-title mb-1">RTL</h5>
            <div class="form-check form-switch mb-0">
              <input
                class="form-check-input ms-auto"
                type="checkbox"
                data-theme-control="phoenixIsRTL"
              />
            </div>
          </div>
          <p class="mb-0 text-700">Change text direction</p>
        </div>
        <div class="border rounded-3 p-4 setting-panel-item bg-white">
          <div class="d-flex justify-content-between align-items-center">
            <h5 class="setting-panel-item-title mb-1">Support Chat</h5>
            <div class="form-check form-switch mb-0">
              <input
                class="form-check-input ms-auto"
                type="checkbox"
                data-theme-control="phoenixSupportChat"
                checked="true"
              />
            </div>
          </div>
          <p class="mb-0 text-700">Toggle support chat</p>
        </div>
        <div class="setting-panel-item">
          <h5 class="setting-panel-item-title">Navigation Type</h5>
          <div class="row gx-2">
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarPositionVertical"
                name="navigation-type"
                type="radio"
                value="vertical"
                data-theme-control="phoenixNavbarPosition"
                disabled="disabled"
                checked="true"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarPositionVertical"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none"
                    src="assets/assets/img/generic/default-light.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none"
                    src="assets/assets/img/generic/default-dark.png"
                    alt="" /></span
                ><span class="label-text">Vertical</span></label
              >
            </div>
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarPositionHorizontal"
                name="navigation-type"
                type="radio"
                value="horizontal"
                data-theme-control="phoenixNavbarPosition"
                disabled="disabled"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarPositionHorizontal"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none"
                    src="assets/assets/img/generic/top-default.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none"
                    src="assets/assets/img/generic/top-default-dark.png"
                    alt="" /></span
                ><span class="label-text"> Horizontal</span></label
              >
            </div>
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarPositionCombo"
                name="navigation-type"
                type="radio"
                value="combo"
                data-theme-control="phoenixNavbarPosition"
                disabled="disabled"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarPositionCombo"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none"
                    src="assets/assets/img/generic/nav-combo-light.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none"
                    src="assets/assets/img/generic/nav-combo-dark.png"
                    alt="" /></span
                ><span class="label-text"> Combo</span></label
              >
            </div>
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarPositionTopDouble"
                name="navigation-type"
                type="radio"
                value="dual-nav"
                data-theme-control="phoenixNavbarPosition"
                disabled="disabled"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarPositionTopDouble"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none"
                    src="assets/assets/img/generic/dual-light.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none"
                    src="assets/assets/img/generic/dual-dark.png"
                    alt="" /></span
                ><span class="label-text"> Dual nav</span></label
              >
            </div>
          </div>
          <p class="text-warning-500 font-medium">
            <svg
              class="svg-inline--fa fa-triangle-exclamation me-2 text-warning"
              aria-hidden="true"
              focusable="false"
              data-prefix="fas"
              data-icon="triangle-exclamation"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
              data-fa-i2svg=""
            >
              <path
                fill="currentColor"
                d="M506.3 417l-213.3-364c-16.33-28-57.54-28-73.98 0l-213.2 364C-10.59 444.9 9.849 480 42.74 480h426.6C502.1 480 522.6 445 506.3 417zM232 168c0-13.25 10.75-24 24-24S280 154.8 280 168v128c0 13.25-10.75 24-23.1 24S232 309.3 232 296V168zM256 416c-17.36 0-31.44-14.08-31.44-31.44c0-17.36 14.07-31.44 31.44-31.44s31.44 14.08 31.44 31.44C287.4 401.9 273.4 416 256 416z"
              ></path></svg
            ><!-- <span class="fa-solid fa-triangle-exclamation me-2 text-warning"></span> Font Awesome fontawesome.com -->You
            can't update navigation type in this page
          </p>
        </div>
        <div class="setting-panel-item">
          <h5 class="setting-panel-item-title">Vertical Navbar Appearance</h5>
          <div class="row gx-2">
            <div class="col-6">
              <input
                class="btn-check"
                id="navbar-style-default"
                type="radio"
                name="config.name"
                value="default"
                data-theme-control="phoenixNavbarVerticalStyle"
                checked="true"
              /><label
                class="btn d-block w-100 btn-navbar-style fs--1"
                for="navbar-style-default"
              >
                <img
                  class="img-fluid img-prototype d-dark-none"
                  src="assets/assets/img/generic/default-light.png"
                  alt=""
                /><img
                  class="img-fluid img-prototype d-light-none"
                  src="assets/assets/img/generic/default-dark.png"
                  alt=""
                /><span class="label-text d-dark-none"> Default</span
                ><span class="label-text d-light-none">Default</span></label
              >
            </div>
            <div class="col-6">
              <input
                class="btn-check"
                id="navbar-style-dark"
                type="radio"
                name="config.name"
                value="darker"
                data-theme-control="phoenixNavbarVerticalStyle"
              /><label
                class="btn d-block w-100 btn-navbar-style fs--1"
                for="navbar-style-dark"
              >
                <img
                  class="img-fluid img-prototype d-dark-none"
                  src="assets/assets/img/generic/vertical-darker.png"
                  alt=""
                /><img
                  class="img-fluid img-prototype d-light-none"
                  src="assets/assets/img/generic/vertical-lighter.png"
                  alt=""
                /><span class="label-text d-dark-none"> Darker</span
                ><span class="label-text d-light-none">Lighter</span></label
              >
            </div>
          </div>
        </div>
        <div class="setting-panel-item">
          <h5 class="setting-panel-item-title">Horizontal Navbar Shape</h5>
          <div class="row gx-2">
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarShapeDefault"
                name="navbar-shape"
                type="radio"
                value="default"
                data-theme-control="phoenixNavbarTopShape"
                disabled="disabled"
                checked="true"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarShapeDefault"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none mb-0"
                    src="assets/assets/img/generic/top-default.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none mb-0"
                    src="assets/assets/img/generic/top-default-dark.png"
                    alt="" /></span
                ><span class="label-text">Default</span></label
              >
            </div>
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarShapeSlim"
                name="navbar-shape"
                type="radio"
                value="slim"
                data-theme-control="phoenixNavbarTopShape"
                disabled="disabled"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarShapeSlim"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none mb-0"
                    src="assets/assets/img/generic/top-slim.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none mb-0"
                    src="assets/assets/img/generic/top-slim-dark.png"
                    alt="" /></span
                ><span class="label-text"> Slim</span></label
              >
            </div>
          </div>
          <p class="text-warning-500 font-medium">
            <svg
              class="svg-inline--fa fa-triangle-exclamation me-2 text-warning"
              aria-hidden="true"
              focusable="false"
              data-prefix="fas"
              data-icon="triangle-exclamation"
              role="img"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
              data-fa-i2svg=""
            >
              <path
                fill="currentColor"
                d="M506.3 417l-213.3-364c-16.33-28-57.54-28-73.98 0l-213.2 364C-10.59 444.9 9.849 480 42.74 480h426.6C502.1 480 522.6 445 506.3 417zM232 168c0-13.25 10.75-24 24-24S280 154.8 280 168v128c0 13.25-10.75 24-23.1 24S232 309.3 232 296V168zM256 416c-17.36 0-31.44-14.08-31.44-31.44c0-17.36 14.07-31.44 31.44-31.44s31.44 14.08 31.44 31.44C287.4 401.9 273.4 416 256 416z"
              ></path></svg
            ><!-- <span class="fa-solid fa-triangle-exclamation me-2 text-warning"></span> Font Awesome fontawesome.com -->You
            can't update vertical navbar appearance type in this page
          </p>
        </div>
        <div class="setting-panel-item">
          <h5 class="setting-panel-item-title">Horizontal Navbar Appearance</h5>
          <div class="row gx-2">
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarTopDefault"
                name="navbar-top-style"
                type="radio"
                value="default"
                data-theme-control="phoenixNavbarTopStyle"
                checked="true"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarTopDefault"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none mb-0"
                    src="assets/assets/img/generic/top-default.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none mb-0"
                    src="assets/assets/img/generic/top-style-darker.png"
                    alt="" /></span
                ><span class="label-text">Default</span></label
              >
            </div>
            <div class="col-6">
              <input
                class="btn-check"
                id="navbarTopDarker"
                name="navbar-top-style"
                type="radio"
                value="darker"
                data-theme-control="phoenixNavbarTopStyle"
              /><label
                class="btn d-inline-block btn-navbar-style fs--1"
                for="navbarTopDarker"
              >
                <span class="mb-2 rounded d-block"
                  ><img
                    class="img-fluid img-prototype d-dark-none mb-0"
                    src="assets/assets/img/generic/navbar-top-style-light.png"
                    alt="" /><img
                    class="img-fluid img-prototype d-light-none mb-0"
                    src="assets/assets/img/generic/top-style-lighter.png"
                    alt="" /></span
                ><span class="label-text d-dark-none">Darker</span
                ><span class="label-text d-light-none">Lighter</span></label
              >
            </div>
          </div>
        </div>
        <a
          class="bun btn-primary d-grid mb-3 text-white dark__text-100 mt-5 btn btn-primary"
          href="https://themes.getbootstrap.com/product/phoenix-admin-dashboard-webapp-template/"
          target="_blank"
          >Purchase template</a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MiniStoreApp",

  data() {
    return {};
  },

  mounted() {},

  methods: {},

  computed() {},

  whatch: {},
};
</script>

<style lang="scss" scoped>
</style>