<template>
  <div>
    <div class="img-cover">
      <div class="navbar">
        <div class="logo">
          <img src="../../../assets/logo-ftc.png" alt="" />
        </div>
        <v-spacer />
        <div class="options">
          <v-row>
            <v-col>
              <span class="about"> SOBRE </span>
            </v-col>
            <v-col>
              <span class="courses"> CURSOS </span>
            </v-col>
            <v-col>
              <span class="support"> SUPORTE </span>
            </v-col>
          </v-row>
        </div>
      </div>
      <div class="content">
        <div class="title">Amplie sua área de conheimento!</div>
        <div class="text">
          Somos uma das maiores instituições de ensino do país, juntamente com
          nossos alunos montamos uma plataforma de cursos de capacitação em
          diiversas área de conhecimento da tecnologia. <br />
          Vem com a gente!

          <div class="img">
            <img
              align="right"
              style="width: 600px; border-radius: 10%"
              src="../../../assets/about.jpeg"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
    <div class="team">
      <p>Nossos colaboradores</p>
      <section class="cards">
      </section>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.img {
  padding-left: 20px;
  border-radius: 50%;
}
.name img {
  border-radius: 50%;
  display: flex;
  margin: 15px;
}

.cards{
  align-items: center;
}
.img-cover {
  padding-top: 18px;
  height: 90vh;
  background-color: #fff8f8;
  padding: 0px 130px 0px 150px;
}
.title {
  font-size: 2.5rem;
  width: 100%;
  margin-left: 220px;
  font-weight: bolder;
}
.text {
  display: flex;
  margin-top: 40px;
  margin-left: 220px;
  width: 65%;
  font-size: 1.8rem;
  font-weight: bold;
}
.team p {
  position: absolute;
  text-align: center;
  top: 94%;
  font-weight: bold;
  font-size: 1.5rem;
}
.team {
  background-color: black;
  height: 110vh;
  width: 100%;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
}

.content {
  padding-top: 160px;
  height: 50%;
}
.navbar {
  width: 100%;
  height: 10%;
  display: flex;
  padding-left: 65px;
  padding-right: 200px;
}
.logo {
  display: flex;
}
.options {
  display: flex;
  align-items: center;
  color: black;
  font-weight: bolder;
  font-size: 1.1rem;
  width: 25%;
}
.about,
.support,
.courses {
  cursor: pointer;
}
.about:hover,
.support:hover,
.courses:hover {
  color: #008cf2;
}
</style>
