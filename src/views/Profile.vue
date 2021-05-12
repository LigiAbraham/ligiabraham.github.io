<template>
  <div class="wrapper">
    <parallax
      class="section page-header header-filter"
      :style="headerStyle"
    ></parallax>
    <div class="main main-raised">
      <div class="section profile-content">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-50 mx-auto">
              <div class="profile">
                <div class="avatar">
                  <img
                    :src="img"
                    alt="Circle Image"
                    class="img-raised rounded-circle img-fluid"
                  />
                </div>
                <div class="name">
                  <h3 class="title">Ligi Abraham</h3>
                  <h6>Full Stack Developer</h6>
                  <md-button
                    href="https://www.linkedin.com/in/ligi-abraham-560a2b133/"
                    class="md-just-icon md-simple md-linkedin"
                    target="_blank"
                    ><i class="fab fa-linkedin"></i
                  ></md-button>
                  <md-button
                    href="https://github.com/LigiAbraham"
                    class="md-just-icon md-simple md-github"
                    target="_blank"
                    ><i class="fab fa-github"></i
                  ></md-button>
                  <md-button
                    href="https://www.instagram.com/ligi_abraham/"
                    class="md-just-icon md-simple md-instagram"
                    target="_blank"
                    ><i class="fab fa-instagram"></i
                  ></md-button>
                </div>
              </div>
            </div>
          </div>
          <div class="description text-center">
            <p>
              Experienced Full Stack Developer with a demonstrated history of working in the 
              information technology and services industry. Skilled in SQL, PHP, Laravel framework,
               Wordpress, Angular, Ionic 4 framework. Strong engineering professional with a Bachelor of 
               Engineering - BE focused in Electronics and Communications.
            </p>
          </div>
          <div class="profile-tabs">
            <tabs
              :tab-name="['Skills', 'Experience', 'Education']"
              plain
              color-button="primary"
            >
              <!-- here you can add your content for tab-content -->
              <template slot="tab-pane-1">
                <div class="md-layout">
                  <div class="md-layout-item md-size-70 mx-auto md-xsmall-size-100">
                    <div class="vertical-center">
                      <md-button class="md-primary md-sm">PHP</md-button>
                      <md-button class="md-info md-sm">Laravel</md-button>
                      <md-button class="md-success md-sm">SQL</md-button>
                      <md-button class="md-primary md-sm">Wordpress</md-button>
                      <md-button class="md-info md-sm">Ionic 4</md-button>
                      <md-button class="md-success md-sm">Angular</md-button>
                      <md-button class="md-warning md-sm">HTML</md-button>
                      <md-button class="md-danger md-sm">CSS</md-button>
                      <md-button class="md-rose md-sm">BOOTSTRAP</md-button>
                      <md-button class="md-sm">Javascript</md-button>
                      <md-button class="md-warning md-sm">NodeJs</md-button>
                      <md-button class="md-danger md-sm">Typescript</md-button>
                      <md-button class="md-rose md-sm">MySQL</md-button>
                      <md-button class="md-danger md-sm">NoSQL</md-button>
                      <md-button class="md-rose md-sm">Firebase</md-button>
                      <md-button class="md-sm">Rest API</md-button>
                      <md-button class="md-primary md-sm">Google API</md-button>
                      <md-button class="md-info md-sm">Git</md-button>
                      <md-button class="md-sm">RedBean</md-button>
                      <md-button class="md-primary md-sm">Razorpay</md-button>
                      <md-button class="md-info md-sm">Stripe</md-button>
                      <md-button class="md-success md-sm">Jquery</md-button>
                      <md-button class="md-warning md-sm">Linux</md-button>
                      <md-button class="md-success md-sm">Windows</md-button>
                      <md-button class="md-warning md-sm">Envoyer</md-button>
                      <md-button class="md-danger md-sm">Postman</md-button>
                      <md-button class="md-rose md-sm">Horizon</md-button>
                      <md-button class="md-sm">Socialite</md-button>
                      <md-button class="md-primary md-sm">Gitlab</md-button>
                      <md-button class="md-info md-sm">Bagisto</md-button>
                      <md-button class="md-success md-sm">Akeneo</md-button>
                      <md-button class="md-warning md-sm">Tailwind CSS</md-button>
                    </div>
                  </div>
                </div>
              </template>
              <template slot="tab-pane-2">
                <div class="md-layout">
                  <div class="md-layout-item md-size-70 mx-auto md-xsmall-size-100">
                    <div id="notifications">

                      <div class="alert">
                        <div class="container">
                          <b>Toolyt</b>, Kannur, Kerala, India<br>
                          <span>Full Stack Developer</span>
                          <p>March 2021 - Present</p>
                        </div>
                      </div>

                      <div class="alert alert-primary">
                        <div class="container">
                          <b>Palmate solutions Pvt Ltd</b>, Bangalore, Karnataka, India<br>
                          <span>Full Stack Developer</span>
                          <p>Jan 2019 - March 2021</p>
                        </div>
                      </div>

                      <div class="alert alert-danger">
                        <div class="container">
                          <b>Preatech Technologies Pvt Ltd</b>, Cochin, Kerala, India<br>
                          <span>Web Developer</span>
                          <p>July 2017 - Dec 2018</p>
                        </div>
                      </div>

                    </div>
                  </div>
                </div>
              </template>
              <template slot="tab-pane-3">
                <div class="md-layout">
                  <div class="md-layout-item md-size-70 mx-auto md-xsmall-size-100">
                    <div id="notifications">

                      <div class="alert">
                        <div class="container">
                          <b>Bachelor of Engineering in Electronics and Communication</b><br>
                          <b>Srinivas Institute of Technology</b>, Mangalore, Karnataka, India<br>
                          <span>VTU Board</span>
                          <p>Graduated - 2017 with 64%</p>
                        </div>
                      </div>

                      <div class="alert alert-primary">
                        <div class="container">
                          <b>PUC</b><br>
                          <b>St. Philomena College</b>, Puttur, Karnataka, India<br>
                          <span>State Board</span>
                          <p>Graduated - 2013 with 63%</p>
                        </div>
                      </div>

                      <div class="alert alert-danger">
                        <div class="container">
                          <b>SSLC</b><br>
                          <b>Knanaya Jyothi English Medium School</b>, Kadaba, Karnataka, India<br>
                          <span>State Board</span>
                          <p>Graduated - 2011 with 82%</p>
                        </div>
                      </div>

                    </div>
                  </div>
                </div>
              </template>
            </tabs>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { Tabs } from "@/components";
export default {
  components: {
    Tabs
  },
  bodyClass: "profile-page",
  props: {
    header: {
      type: String,
      default: require("@/assets/img/vue-mk-header.jpg")
    },
    img: {
      type: String,
      default: require("@/assets/img/ligi.jpg")
    }
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`
      };
    }
  }
};
</script>

<style lang="scss" scoped>
.section {
  padding: 0;
}

.profile-tabs::v-deep {
  .md-card-tabs .md-list {
    justify-content: center;
  }

  [class*="tab-pane-"] {
    margin-top: 3.213rem;
    padding-bottom: 50px;

    img {
      margin-bottom: 2.142rem;
    }
  }
}
</style>
