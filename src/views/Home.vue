<template>
  <div class="container-fluid hero-img">
    <!-- TOP ROW W TITLE & HERO IMG -->
    <div class="row top">
      <div class="col-12 title">
        <img class="prof-pic" :src="profPic">
        <div class="title-2">
          <h1 class="txt-1">Madison Abegglen</h1>
          <h5 class="txt-2">Full Stack Software Developer</h5>
        </div>
      </div>
    </div>

    <!-- ABOUT ROW CONTAINING ABOUT SECTION -->
    <div class="row s-2">
      <div class="col-10 offset-1 about">
        <h1 class="txt-3">
          <i class="fas fa-angle-double-down"></i>About
        </h1>
      </div>
      <div class="col-2 offset-2 img-col">
        <img
          class="comp-img"
          src="https://cdn0.iconfinder.com/data/icons/web-seo-development-vol-1-3/48/19_pencil_ruler_laptop_device_drawing_design-512.png"
          alt
        >
      </div>
      <div class="col-6 about-2">
        <h5
          class="txt-4"
        >As a self starter, I am comfortable leading conversation and assisting in driving decisions & designs in team environments, engaging with peers at a leadership capacity. I have experience with modern web frameworks and tools, working with relational database technologies, building with RESTful web services via JSON, as well as a strong customer focus and entrepreneurial mindset. With the enthusiasm and ability to work in a fast paced, rapidly changing environment with a positive attitude and professionalism, I would describe myself as a valuable asset to the IT workforce.</h5>
      </div>
    </div>

    <!-- SKILLS ROW, DISPLAYS SOFTWARE SKILLS -->
    <div class="row s-3">
      <div class="col-10 offset-1 skills">
        <h1 class="txt-5">
          <i class="fas fa-angle-double-down"></i>Skills
        </h1>
      </div>
      <div class="col-10 offset-1 skills-2">
        <h1 class="txt-6">
          <i class="fas fa-angle-double-right"></i> Alongside a strong enthusiasm for building and working with languages of many types, there are several skills that accompany my full-stack software development certification. Here are a few to list:
          <br>Javascript, HTML5, CSS, C#, Vue.js, jQuery, Bootstrap, Node.js, MongoDB, .NET, Visual Studio Code, SQL
        </h1>
      </div>
      <div class="col-10 offset-1 icon-p">
        <img
          class="icon-c"
          src="https://png.pngtree.com/svg/20170719/javascript_633988.png"
          style="height: 110px; background-color: white;"
        >
        <img
          class="icon-c"
          src="https://www.w3.org/html/logo/downloads/HTML5_Badge_512.png"
          style="height: 110px"
        >
        <img
          class="icon-c"
          src="https://raw.githubusercontent.com/github/explore/6c6508f34230f0ac0d49e847a326429eefbfc030/topics/css/css.png"
          style="height: 120px;"
        >
        <img
          class="icon-c"
          src="http://dynagendynamics.com/wp-content/uploads/2018/09/c.png"
          style="height: 140px;"
        >
        <img
          class="icon-c"
          src="http://www.stickpng.com/assets/images/58482acecef1014c0b5e4a1e.png"
          style="height: 100px;"
        >
        <img
          class="icon-c"
          src="https://cdn2.iconfinder.com/data/icons/designer-skills/128/code-programming-javascript-jquery-develop-framework-language-512.png"
          style="height: 115px;"
        >
        <img
          class="icon-c"
          src="https://img.icons8.com/color/1600/bootstrap.png"
          style="height: 125px"
        >
        <img
          class="icon-c"
          src="https://img.icons8.com/color/1600/nodejs.png"
          style="height: 120px;"
        >
        <img
          class="icon-c"
          src="https://png.pngtree.com/svg/20170216/mongodb_1014590.png"
          style="height: 120px;"
        >
        <img
          class="icon-c"
          src="https://www.vividsites.com/mm/images/careers-dotnet-icon.png"
          style="height: 110px;"
        >
        <img
          class="icon-c"
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Visual_Studio_Code_1.18_icon.svg/1000px-Visual_Studio_Code_1.18_icon.svg.png"
          style="height: 110px;"
        >
        <img class="icon-c" src="https://img.icons8.com/metro/1600/sql.png" style="height: 110px;">
      </div>
    </div>

    <!-- PROJECTS SECTION - DISPLAYS RECENT PROJECTS -->
    <div class="row s-4">
      <div class="col-10 offset-1 projects">
        <h1 class="txt-3">
          <i class="fas fa-angle-double-down"></i>Projects
        </h1>
      </div>
      <div class="col-8 offset-2 bki-l">
        <img :src="bki" class="proj-img">
        <p class="txt-7">
          BUMBLE Kanban is a collaborative project, that takes on the form of a nontrivial Vue.js front-end and Node.js back-end, resembling the widely-used and versatile Kanban board concept.
          <a
            class="castle-link"
            href="https://bumble-kanban.herokuapp.com/"
          >Click</a> here to view the deployed application.
        </p>
      </div>
      <div class="col-8 offset-2 bki-r">
        <p class="txt-7">
          PartyOx, a collaborative project & PWA built to aid DJ's and social event hosts to manage song requests, utilizes Vue.js & Node.js allowing a host to create parties where others join & suggest songs.
          <a
            class="castle-link"
            href="https://partyox.herokuapp.com/"
          >Click</a> here to view the deployed application.
        </p>
        <img :src="pol" class="proj-img">
      </div>
      <div class="col-8 offset-2 bki-l">
        <img :src="castleLogo" class="proj-img">
        <p class="txt-7">
          Castle Grimtol is a console game application made using C#, that allows users to move about a set of rooms & achieve objectives.
          <a
            class="castle-link"
            href="https://github.com/Madison-Abegglen/castle-grimtol"
          >Click</a> here to view the repository.
        </p>
      </div>
    </div>

    <!-- CONTACT INFO / SOCIAL MEDIA PRESENCES -->
    <div class="row s-5">
      <div class="col-10 offset-1 contact">
        <h1 class="txt-5">
          <i class="fas fa-angle-double-left"></i>Contact Me!
          <i class="fas fa-angle-double-right"></i>
        </h1>
      </div>
      <div class="col-4 offset-4 c-info">
        <p class="txt-8">email | madison.abegglen@gmail.com</p>
        <p class="txt-8"># | 208-573-7663</p>
      </div>
      <div class="col-4 offset-4">
        <div class="row iconz">
          <a class="col-2 c-icon-fb" href="https://www.facebook.com/marilacy">
            <i class="fab fa-facebook fa-4x"></i>
          </a>
          <a href="https://www.linkedin.com/in/madison-abegglen-708338121/" class="col-2 c-icon-li">
            <i class="fab fa-linkedin fa-4x"></i>
          </a>
          <a href="https://github.com/Madison-Abegglen" class="col-2 c-icon-gi">
            <i class="fab fa-github-square fa-4x"></i>
          </a>
        </div>
      </div>
    </div>

    <!-- QUOTE ROW -->
    <div class="row s-6">
      <div class="col-8 offset-2 quote">
        <h5
          class="txt-9"
        >“Nothing is particularly hard if you divide it into small jobs.” | Henry Ford</h5>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import profilePic from "@/assets/images/compressed-version.jpg";
import bki from "@/assets/images/bki-logo.jpg";
import poLogo from "@/assets/images/po-logo.jpg";
import castleLogo from "@/assets/images/new-castle-logo.jpg";
import navbar from "@/components/navbar.vue";

export default {
  name: "home",
  data() {
    return {
      profPic: profilePic,
      bki: bki,
      pol: poLogo,
      castleLogo: castleLogo
    };
  },
  components: {
    navbar
  }
};
</script>

<style scoped>
.castle-link {
  color: rgb(106, 220, 255);
}
.top {
  height: 80vh;
}
.s-2 {
  height: 80vh;
  background-color: rgb(66, 66, 66);
}
.s-3 {
  height: 90vh;
  background-color: rgb(196, 196, 196);
}
.s-4 {
  height: 90vh;
  background-color: rgb(66, 66, 66);
  /* display: flex; */
  /* align-items: flex-start; */
}
.s-5 {
  height: 40vh;
  background-color: rgb(196, 196, 196);
}
.s-6 {
  height: 15vh;
  background-color: rgb(66, 66, 66);
}
.hero-img {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url("https://images.pexels.com/photos/15382/pexels-photo.jpg?auto=compress&cs=tinysrgb&h=750&w=1260");
  height: 80vh;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
.prof-pic {
  height: 8rem;
  border-radius: 100%;
}
.title {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 80vh;
  flex-direction: row;
}
.title-2 {
  display: flex;
  flex-direction: column;
  margin-left: 1rem;
  padding-left: 1.2rem;
  border-left: solid white;
}
.comp-img {
  height: 10rem;
  color: white;
  margin-bottom: 4rem;
}
.fa-angle-double-down {
  margin-right: 1rem;
}
.img-col {
  height: 40vh;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 8vh;
  background-color: rgb(160, 160, 160, 0.4);
  border-left: solid white;
  border-top: solid white;
}
.about {
  height: 15vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.about-2 {
  height: 40vh;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
  padding-top: 2rem;
  padding-right: 3rem;
  background-color: rgb(160, 160, 160, 0.4);
  border-bottom: solid white;
  border-right: solid white;
}
.skills {
  height: 15vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.skills-2 {
  height: 20vh;
  display: flex;
  align-items: flex-end;
}
.icon-p {
  height: 50vh;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  flex-wrap: wrap;
}
.icon-c {
  margin-left: 0.5rem;
  margin-right: 0.5rem;
  padding: 0.5rem;
}
.fa-angle-double-right {
  margin-right: 0.5rem;
}
.proj-img {
  height: 8rem;
  width: 24rem;
  border-radius: 2.5px;
  margin: 0.5rem;
}
.bki-l {
  height: 20vh;
  background-color: rgb(160, 160, 160, 0.4);
  display: flex;
  justify-content: flex-start;
  align-items: center;
  padding-right: 1rem;
  border-left: solid white;
}
.bki-r {
  height: 20vh;
  background-color: rgb(160, 160, 160, 0.4);
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding-left: 1rem;
  border-right: solid white;
}
.projects {
  height: 15vh;
  display: flex;
  justify-content: center;
  align-items: center;
  /* margin: 0; */
}
.contact {
  height: 15vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.c-info {
  height: 5vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.c-icon-fb {
  margin: 1rem;
  color: rgb(31, 54, 187);
}
.c-icon-li {
  margin: 1rem;
  color: rgb(31, 151, 187);
}
.c-icon-gi {
  margin: 1rem;
  color: rgb(66, 68, 80);
}
.iconz {
  display: flex;
  justify-content: center;
}
.fa-angle-double-left {
  margin-right: 1rem;
}
.txt-1 {
  font-family: "Roboto", sans-serif;
  color: white;
  text-shadow: 0 0 1px rgb(0, 0, 0, 0.5);
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 4rem;
}
.txt-2 {
  font-family: "Roboto", sans-serif;
  color: white;
  text-shadow: 0 0 1px rgb(0, 0, 0, 0.5);
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 2rem;
}
.txt-3 {
  font-family: "Roboto", sans-serif;
  color: white;
  text-shadow: 0 0 1px rgb(0, 0, 0, 0.5);
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 2.8rem;
  margin-top: 4rem;
}
.txt-4 {
  font-family: "Roboto", sans-serif;
  color: white;
  text-shadow: 0 0 1px rgb(0, 0, 0, 0.5);
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 15px;
}
.txt-5 {
  font-family: "Roboto", sans-serif;
  color: rgb(34, 34, 34);
  /* text-shadow: 0 0 1px rgb(0, 0, 0, 0.5); */
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 2.8rem;
  margin-top: 4rem;
}
.txt-6 {
  font-family: "Roboto", sans-serif;
  color: rgb(34, 34, 34);
  /* text-shadow: 0 0 1px rgb(0, 0, 0, 0.5); */
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 1px;
  font-size: 1.5rem;
  /* margin-top: 4rem; */
}
.txt-7 {
  font-family: "Roboto", sans-serif;
  color: white;
  text-shadow: 0 0 1px rgb(0, 0, 0, 0.5);
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 11px;
  text-align: start;
  margin-left: 1rem;
}
.txt-8 {
  font-family: "Roboto", sans-serif;
  color: rgb(34, 34, 34);
  /* text-shadow: 0 0 1px rgb(0, 0, 0, 0.5); */
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 10px;
  margin: 0;
}
.txt-9 {
  font-family: "Roboto", sans-serif;
  color: rgb(245, 245, 245);
  /* text-shadow: 0 0 1px rgb(0, 0, 0, 0.5); */
  text-transform: uppercase;
  /* font-weight: bold; */
  letter-spacing: 2px;
  font-size: 10px;
}
.quote {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
