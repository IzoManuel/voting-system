<template>
  <div id="wrapper">
    <!-- Navigation -->
    <nav
      class="navbar navbar-default navbar-static-top"
      role="navigation"
      style="margin-bottom: 0"
    >
      <div class="navbar-header">
        <button
          type="button"
          class="navbar-toggle"
          data-toggle="collapse"
          data-target=".navbar-collapse"
        >
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="index.html">SB Admin v2.0</a>
      </div>
      <!-- /.navbar-header -->

      <ul class="nav navbar-top-links navbar-right">
        <li class="dropdown">
          <a class="dropdown-toggle" data-toggle="dropdown" href="#">
            <i class="fa fa-envelope fa-fw"></i>
            <i class="fa fa-caret-down"></i>
          </a>
          <ul class="dropdown-menu dropdown-messages">
            <li>
              <a href="#">
                <div>
                  <strong>John Smith</strong>
                  <span class="pull-right text-muted">
                    <em>Yesterday</em>
                  </span>
                </div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Pellentesque eleifend...
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a href="#">
                <div>
                  <strong>John Smith</strong>
                  <span class="pull-right text-muted">
                    <em>Yesterday</em>
                  </span>
                </div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Pellentesque eleifend...
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a href="#">
                <div>
                  <strong>John Smith</strong>
                  <span class="pull-right text-muted">
                    <em>Yesterday</em>
                  </span>
                </div>
                <div>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Pellentesque eleifend...
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a class="text-center" href="#">
                <strong>Read All Messages</strong>
                <i class="fa fa-angle-right"></i>
              </a>
            </li>
          </ul>
          <!-- /.dropdown-messages -->
        </li>
        <!-- /.dropdown -->
        <!-- /.dropdown -->
        <li class="dropdown">
          <a class="dropdown-toggle" data-toggle="dropdown" href="#">
            <i class="fa fa-bell fa-fw"></i> <i class="fa fa-caret-down"></i>
          </a>
          <ul class="dropdown-menu dropdown-alerts">
            <li>
              <a href="#">
                <div>
                  <i class="fa fa-comment fa-fw"></i> New Comment
                  <span class="pull-right text-muted small">4 minutes ago</span>
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a href="#">
                <div>
                  <i class="fa fa-twitter fa-fw"></i> 3 New Followers
                  <span class="pull-right text-muted small"
                    >12 minutes ago</span
                  >
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a href="#">
                <div>
                  <i class="fa fa-envelope fa-fw"></i> Message Sent
                  <span class="pull-right text-muted small">4 minutes ago</span>
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a href="#">
                <div>
                  <i class="fa fa-tasks fa-fw"></i> New Task
                  <span class="pull-right text-muted small">4 minutes ago</span>
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a href="#">
                <div>
                  <i class="fa fa-upload fa-fw"></i> Server Rebooted
                  <span class="pull-right text-muted small">4 minutes ago</span>
                </div>
              </a>
            </li>
            <li class="divider"></li>
            <li>
              <a class="text-center" href="#">
                <strong>See All Alerts</strong>
                <i class="fa fa-angle-right"></i>
              </a>
            </li>
          </ul>
          <!-- /.dropdown-alerts -->
        </li>
        <!-- /.dropdown -->
        <li class="dropdown">
          <a class="dropdown-toggle" data-toggle="dropdown" href="#">
            <i class="fa fa-user fa-fw"></i> <i class="fa fa-caret-down"></i>
          </a>
          <ul class="dropdown-menu dropdown-user">
            <li>
              <a href="#"><i class="fa fa-user fa-fw"></i> User Profile</a>
            </li>
            <li>
              <a href="#"><i class="fa fa-gear fa-fw"></i> Settings</a>
            </li>
            <li class="divider"></li>
            <li>
              <a href="login.html"
                ><i class="fa fa-sign-out fa-fw"></i> Logout</a
              >
            </li>
          </ul>
          <!-- /.dropdown-user -->
        </li>
        <!-- /.dropdown -->
      </ul>
      <!-- /.navbar-top-links -->

      <div class="navbar-default sidebar" role="navigation">
        <div class="sidebar-nav navbar-collapse">
          <ul class="nav" id="side-menu">
            <li class="sidebar-search">
              <div class="input-group custom-search-form">
                <input
                  type="text"
                  class="form-control"
                  placeholder="Search..."
                />
                <span class="input-group-btn">
                  <button class="btn btn-default" type="button">
                    <i class="fa fa-search"></i>
                  </button>
                </span>
              </div>
              <!-- /input-group -->
            </li>
            <li>
              <router-link to="/dashborad">
                <i class="fa fa-dashboard fa-fw"></i> Dashboard
              </router-link>
            </li>
            <li>
              <router-link to="/createElection">
                <i class="fa fa-plus"></i> Create Election
              </router-link>
            </li>
            <li>
              <router-link to="/preActiveElections">
                <i class="fa fa-hourglass-start"></i> PreActive Elections
              </router-link>
            </li>
            <li>
              <router-link to="/activeElections">
                <i class="fa fa-hourglass-half"></i> Active Elections
              </router-link>
            </li>
            <li>
              <router-link to="/postActiveElections">
                <i class="fa fa-hourglass-end"></i> PostActive Elections
              </router-link>
            </li>
            <li>
              <router-link to="/participationRequests">
                <i class="fa fa-envelope"></i> Participation Requests
                <span
                  class="badge badge-primary vb"
                  style="background-color: blue"
                  >23</span
                >
              </router-link>
            </li>
            <li>
              <a href="#"
                ><i class="fa fa-bar-chart-o fa-fw"></i> Charts<span
                  class="fa arrow"
                ></span
              ></a>
              <ul class="nav nav-second-level">
                <li>
                  <router-link to="/float"> Flot Charts </router-link>
                </li>
                <li>
                  <router-link to="/morris"> Morris.js Charts </router-link>
                </li>
              </ul>
              <!-- /.nav-second-level -->
            </li>
            <li>
              <router-link to="/tables">
                <i class="fa fa-table fa-fw"></i> Tables
              </router-link>
            </li>
            <li>
              <router-link to="/forms">
                <i class="fa fa-table fa-fw"></i> Forms
              </router-link>
            </li>
            <li>
              <a href="#"
                ><i class="fa fa-wrench fa-fw"></i> UI Elements<span
                  class="fa arrow"
                ></span
              ></a>
              <ul class="nav nav-second-level">
                <li>
                  <router-link to="/panels"> Panels and Wells </router-link>
                </li>
                <li>
                  <router-link to="/buttons"> Buttons </router-link>
                </li>
                <li>
                  <router-link to="/notifications"> Notifications </router-link>
                </li>
                <li>
                  <router-link to="/typography"> Typography </router-link>
                </li>
                <li>
                  <router-link to="/icons"> Icons </router-link>
                </li>
                <li>
                  <router-link to="/grid"> Grid </router-link>
                </li>
              </ul>
              <!-- /.nav-second-level -->
            </li>
            <li>
              <a href="#"
                ><i class="fa fa-sitemap fa-fw"></i> Multi-Level Dropdown<span
                  class="fa arrow"
                ></span
              ></a>
              <ul class="nav nav-second-level">
                <li>
                  <a href="#">Second Level Item</a>
                </li>
                <li>
                  <a href="#">Second Level Item</a>
                </li>
                <li>
                  <a href="#">Third Level <span class="fa arrow"></span></a>
                  <ul class="nav nav-third-level">
                    <li>
                      <a href="#">Third Level Item</a>
                    </li>
                    <li>
                      <a href="#">Third Level Item</a>
                    </li>
                    <li>
                      <a href="#">Third Level Item</a>
                    </li>
                    <li>
                      <a href="#">Third Level Item</a>
                    </li>
                  </ul>
                  <!-- /.nav-third-level -->
                </li>
              </ul>
              <!-- /.nav-second-level -->
            </li>
            <li>
              <a href="#"
                ><i class="fa fa-files-o fa-fw"></i> Sample Pages<span
                  class="fa arrow"
                ></span
              ></a>
              <ul class="nav nav-second-level">
                <li>
                  <router-link to="/blank"> Blank Page </router-link>
                </li>
                <li>
                  <router-link to="/public/login"> Login Page </router-link>
                </li>
              </ul>
              <!-- /.nav-second-level -->
            </li>
          </ul>
        </div>
        <!-- /.sidebar-collapse -->
      </div>
      <!-- /.navbar-static-side -->
    </nav>

    <router-view />
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
