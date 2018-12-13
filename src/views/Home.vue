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
        >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repellendus accusantium sapiente possimus blanditiis, nisi quis iste laborum amet fugiat adipisci doloribus cupiditate eos facilis dolorem impedit, asperiores doloremque libero sunt labore animi debitis nemo? Numquam aliquid dolor ut dolore magnam reprehenderit repellendus voluptatem et incidunt temporibus eaque excepturi, esse commodi harum aperiam at nihil labore, unde deleniti nam rem laudantium fuga! Enim, quidem quisquam vero veniam harum porro expedita ipsum.</h5>
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
          <i class="fas fa-angle-double-right"></i>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Harum reiciendis similique porro rem? Vel veritatis labore quia optio laborum assumenda harum, quas illum pariatur nisi vero corrupti ipsam autem totam!
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

    <div class="row s-4">
      <div class="col-10 offset-1 projects">
        <h1 class="txt-3">
          <i class="fas fa-angle-double-down"></i>Projects
        </h1>
      </div>
      <div class="col-8 offset-2 bki-l">
        <img :src="bki" class="proj-img">
        <p
          class="txt-7"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus dignissimos, incidunt veritatis error sint est!</p>
      </div>
      <div class="col-8 offset-2 bki-r">
        <p
          class="txt-7"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus dignissimos, incidunt veritatis error sint est!</p>
        <img :src="pol" class="proj-img">
      </div>
      <div class="col-8 offset-2 bki-l">
        <img :src="castleLogo" class="proj-img">
        <p
          class="txt-7"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus dignissimos, incidunt veritatis error sint est!</p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import profilePic from "@/assets/images/compressed-version.jpg";
import bki from "@/assets/images/bki-logo.jpg";
import poLogo from "@/assets/images/po-logo.jpg";
import castleLogo from "@/components/castle-logo.jpg";
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
  border-bottom: solid white;
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
  align-items: flex-start;
  padding-top: 8vh;
  background-color: rgb(160, 160, 160, 0.4);
  border-bottom: solid white;
}
.skills {
  height: 15vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.skills-2 {
  height: 15vh;
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
  width: 25rem;
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
  letter-spacing: 2px;
  font-size: 1.2rem;
  /* margin-top: 4rem; */
}
.txt-7 {
  font-family: "Roboto", sans-serif;
  color: white;
  text-shadow: 0 0 1px rgb(0, 0, 0, 0.5);
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 2px;
  font-size: 15px;
  text-align: center;
}
</style>
