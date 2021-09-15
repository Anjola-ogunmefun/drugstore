<template>
  <main>
    <div id="wrapper">
      <!-- Sidebar -->
      <div id="sidebar-wrapper">
        <ul class="sidebar-nav">
          <li class="sidebar-brand">
            <a href="#">
              Drugstore.ng
            </a>
          </li>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Sales</a>
          </li>
          <li>
            <a href="#">Orders</a>
          </li>
          <li>
            <a href="#">Stocks</a>
          </li>
          <li>
            <a href="#" class="active">Patients</a>
          </li>
          <li>
            <a href="#">Coupon</a>
          </li>
          <li>
            <a href="#">Pharmacy Request</a>
          </li>
          <li>
            <a href="#">Logistics</a>
          </li>

          <li class="top">
            SETTINGS
          </li>
          <li class="bottom">
            <a href="#">Manage Admin</a>
          </li>
        </ul>

        <ul class="sidebar-nav bottom"></ul>
      </div>
      <!-- /#sidebar-wrapper -->

      <!-- Page Content -->
      <div id="page-content-wrapper">
        <div class="container-fluid">
          <div class="row">
                <div id="menu-toggle">
                <nav class="navbar navbar-expand-sm navbar-light f-r">
                  <div class="container-fluid">
                    <button
                      class="navbar-toggler"
                      type="button"
                      data-bs-toggle="collapse"
                      data-bs-target="#navbarSupportedContent"
                      aria-controls="navbarSupportedContent"
                      aria-expanded="false"
                      aria-label="Toggle navigation"
                      @click="showMenu"
                    >
                      <span class="navbar-toggler-icon"></span>
                    </button>
                  </div>
                </nav>
              </div>
            <div class="col-lg-12">

              <!-- Top row -->
              <div class="row">
                <h2 class="txt-color py-2 mt-5 ml">Patients</h2>
                <div class="float">
                  <span class="badge rounded-pill bg-c note"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      width="16"
                      height="16"
                      fill="currentColor"
                      class="bi bi-bell mx-1 my-2 txt-color"
                      viewBox="0 0 16 16"
                    >
                      <path
                        d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zM8 1.918l-.797.161A4.002 4.002 0 0 0 4 6c0 .628-.134 2.197-.459 3.742-.16.767-.376 1.566-.663 2.258h10.244c-.287-.692-.502-1.49-.663-2.258C12.134 8.197 12 6.628 12 6a4.002 4.002 0 0 0-3.203-3.92L8 1.917zM14.22 12c.223.447.481.801.78 1H1c.299-.199.557-.553.78-1C2.68 10.2 3 6.88 3 6c0-2.42 1.72-4.44 4.005-4.901a1 1 0 1 1 1.99 0A5.002 5.002 0 0 1 13 6c0 .88.32 4.2 1.22 6z"
                      />
                    </svg>
                    <p class="inline notice txt-color mx-3">
                      No unread message
                    </p>
                  </span>

                  <img src="../assets/avatar.jpeg" alt="avatar" />

                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    fill="currentColor"
                    class="bi bi-chevron-down mt-3"
                    viewBox="0 0 16 16"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z"
                    />
                  </svg>
                </div>
              </div>
            </div>
            <!-- end Top row -->

            <!-- outline button -->
            <div class="row">
              <div class="col-4">
                <div class="btn-group">
                  <button
                    class="btn outline dropdown-toggle py-1 px-3 mt-5 ml"
                    type="button"
                    data-bs-toggle="dropdown"
                    aria-expanded="false"
                  >
                    All Time
                  </button>
                  <ul class="dropdown-menu">
                    ...
                  </ul>
                </div>
              </div>
            </div>
            <!-- end outline button -->

            <!-- Patient count -->
            <div class="row">
              <div class="col-5 d-block align-items-center">
                <div class="box txt-color ml">
                  <strong><p class="py-3 mt-4 central num">2348</p></strong>
                  <h6 class="central neg-m total">
                    Total no
                    <br />
                    Of Patients
                  </h6>
                </div>
              </div>
            </div>
            <!-- end patient count -->

            <!-- Patients table -->
            <div class="row">
              <div class="table-responsive-sm mt-5 mb-5 px-3 tb-bg ml rounded">
                <table class="table mb-5">
                    <h4 class="px-3 py-4 txt-color">All Patients/Users</h4>
                  <tbody>
                    <tr class="bg-t neg-p">
                      <th scope="col" class="pad-5">User Name</th>
                      <th scope="col">Email Address</th>
                      <th scope="col">Phone Number</th>
                      <th scope="col">Address</th>
                    </tr>
                    <tr>
                      <td scope="row" class="pad-5">Oluwaseun Anjorin</td>
                      <td>hello@drugstore.ng</td>
                      <td>090574839293</td>
                      <td>Ikorodu, Lagos</td>
                    </tr>
                    <tr>
                      <td scope="row" class="pad-5">Oluwaseun Anjorin</td>
                      <td>hello@drugstore.ng</td>
                      <td>090574839293</td>
                      <td>Ikorodu, Lagos</td>
                    </tr>
                    <tr>
                      <td scope="row" class="pad-5">Oluwaseun Anjorin</td>
                      <td>hello@drugstore.ng</td>
                      <td>090574839293</td>
                      <td>Ikorodu, Lagos</td>
                    </tr>
                    <tr>
                      <td scope="row" class="pad-5">Oluwaseun Anjorin</td>
                      <td>hello@drugstore.ng</td>
                      <td>090574839293</td>
                      <td>Ikorodu, Lagos</td>
                    </tr>
                    <tr>
                      <td scope="row" class="pad-5">Oluwaseun Anjorin</td>
                      <td>hello@drugstore.ng</td>
                      <td>090574839293</td>
                      <td>Ikorodu, Lagos</td>
                    </tr>
                    <tr>
                      <td scope="row" class="pad-5">Oluwaseun Anjorin</td>
                      <td>hello@drugstore.ng</td>
                      <td>090574839293</td>
                      <td>Ikorodu, Lagos</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
            <!-- end patient table -->
          </div>
        </div>
      </div>
      <!-- /#page-content-wrapper -->
    </div>
    <!-- /#wrapper -->
  </main>
</template>

<script>
import $ from "jquery";

export default {
  dtat() {
    return {
      show: false,
    };
  },
  methods: {
    showMenu() {
      this.show = !this.show;
      $("#menu-toggle").click(function(e) {
        e.preventDefault();
        $("#wrapper").toggleClass("toggled");
      });
    }
  },
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lexend+Deca:wght@300&display=swap');

main {
  margin: 0;
  padding: 0;
  /* background: #edf4fd; */
  overflow-x: hidden;
font-family: 'Lexend Deca', sans-serif;}

.active {
  margin-left: 1px;
  border-left: 5px solid #023e8a;
  font-weight: bolder;
}

img {
  height: 3rem;
  border-radius: 50%;
  margin-right: 10px;
}

.f-r{
    float: right;
}

.txt-color {
  color: #023e8a;
}
.total{
  font-weight: bold;
}
.bg-c {
  background: #d2dae9;
}
.bg-t {
  background: #fafbfd;
  border-radius: 30% !important;
  overflow: hidden;
}

.ml {
  margin-left: 10px;
}
tr {
  line-height: 2.5rem;
}

.inline {
  display: inline;
}

.float {
  display: flex;
  justify-content: right;
  margin-top: -50px;
}
.notice {
  margin-right: 10px;
  font-weight: lighter;
}

main {
  overflow-x: hidden;
}

.top {
  margin-top: 22rem;
  color: #999999;
}
.bottom {
  margin-bottom: 7rem;
}

.num {
  font-size: 22px;
}

.neg-m {
  margin-top: -20px;
}

.rounded {
  border-radius: 17px !important;
}
.central {
  display: flex;
  margin-left: 15px;
}

.navbar-toggler:focus,
.navbar-toggler:active,
.navbar-toggler-icon:focus {
    border-color: #023e8a;
    outline-offset: 5px;
    box-shadow: none;
}

.navbar-toggler{
    margin-bottom: -35px;
  }

/* outline button */
.outline {
  position: relative;
  z-index: 3;
  background: transparent;
  color: #023e8a;
  border-color: #023e8a;
  border-style: solid;
  border-width: 2px;
  border-radius: 8%;
  padding: 10px 10px;
  transition: all 0.2s linear;
}
.outline:hover {
  color: white;
  background: #023e8a;
  border-color: white;
  transition: all 0.2s linear;
}
.outline:active {
  border-radius: 22px;
}
.box {
  width: 9rem;
  height: 7rem;
  background: #d2dae9 !important;
  border-radius: 10%;
  justify-content: center;
}

.tb-bg {
  background: #fff;
}

/* Toggle Styles */

#wrapper {
  padding-left: 0;
  -webkit-transition: all 0.5s ease;
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  transition: all 0.5s ease;
}

#sidebar-wrapper {
  z-index: 1000;
  position: fixed;
  left: 250px;
  width: 0;
  height: 100%;
  margin-left: -250px;
  overflow-y: auto;
  background: white;
  box-shadow: 2px 0 20px 0 #c7d9f3;
  -webkit-transition: all 0.5s ease;
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  transition: all 0.5s ease;
}

#wrapper.toggled #sidebar-wrapper {
  width: 220px;
  overflow-x: hidden;
}

#page-content-wrapper {
  width: 100%;
  height: 100;
  position: absolute;
  padding: 15px;
  background: #f6f8fb;
}

#wrapper.toggled #page-content-wrapper {
  position: absolute;
}

/* Sidebar Styles */

.sidebar-nav {
  position: absolute;
  top: 0;
  width: 250px;
  margin: 0;
  padding: 0;
  list-style: none;
}

.sidebar-nav li {
  text-indent: 30px;
  line-height: 50px;
  font-size: 16px;
}

.sidebar-nav li a {
  display: block;
  text-decoration: none;
  color: #023e8a;
}

.sidebar-nav li a:hover {
  text-decoration: none;
  color: #023e8a;
  background: #d9e7fa;
}

.sidebar-nav li a:active,
.sidebar-nav li a:focus {
  text-decoration: none;
}

.sidebar-nav > .sidebar-brand {
  margin-top: 65px;
  height: 90px;
  font-size: 25px;
  line-height: 50px;
}

.sidebar-nav > .sidebar-brand a {
  color: #023e8a;
}

.sidebar-nav > .sidebar-brand a:hover {
  color: #023e8a;
  background: none;
}

/* Media Queries */

@media (max-width: 600px) {
  .note {
    display: none !important;
  }
  img {
    height: 2.5rem;
    margin-left: 20px !important;
  }

  .bi-bell {
    padding: -50px 0 !important;
  }
  .top {
    margin-top: 5rem;
  }
  .bottom {
    margin-bottom: 2rem;
  }
}

@media (min-width: 768px) {
  .notice {
    font-size: 18px;
    margin-left: 10px;
  }
  .bi-bell {
    height: 30px;
    width: 30px;
  }

  img {
    margin-left: 20px;
  }

  .sidebar-nav li {
    text-indent: 30px;
    line-height: 60px;
    font-size: 20px;
  }

  .sidebar-nav > .sidebar-brand {
    font-size: 30px;
    line-height: 60px;
  }
  .outline {
    padding: 17px 35px !important;
    font-size: 22px;
  }

  .box {
    width: 14rem;
    height: 10rem;
    margin-top: 50px;
    background: #c8ddf9;
    border-radius: 10%;
    justify-content: center;
  }

  .num {
    font-size: 36px;
  }

  .total {
    font-size: 24px;
  }

  .ml{
    margin-left: 100px;
  }
  .neg-m {
    margin-top: -20px;
  }

  .pad-5 {
    padding: 0 30px;
  }

  tr {
    line-height: 5rem;
  }

  td,
  th {
    font-size: 20px;
  }

  .tb-bg{
    width: 90%;
  }
  h4{
    font-size: 26px;
  }
  .central {
    margin-left: 30px;
  }

  #wrapper {
    padding-left: 250px;
  }

  #wrapper.toggled {
    padding-left: 0;
  }

  #sidebar-wrapper {
    width: 300px;
  }

  #wrapper.toggled #sidebar-wrapper {
    width: 0;
  }

  #page-content-wrapper {
    padding: 20px;
    position: relative;
  }

  #wrapper.toggled #page-content-wrapper {
    position: relative;
    margin-right: 0;
  }

  #menu-toggle {
    display: none;
  }
}
</style>
