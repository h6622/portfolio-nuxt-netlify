<template>
  <div class="bg">
    <div class="container">
      <h1 class="aboutTitle">About Me</h1>
      <div class="aboutContent">
        <img src="http://placehold.it/250x250" />
        <div>
          <div>content1</div>
          <div class="marginTop">content2</div>
        </div>
      </div>
      <div class="viewMore">
        <nuxt-link to="about" class="viewMoreBtn">View More</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.bg {
  height: 600px;
  background-color: #6cd6e3;
}

.aboutTitle {
  padding: 70px 0;
  text-align: center;
}

.aboutContent {
  display: flex;
  justify-content: space-around;
}

.marginTop {
  margin-top: 100px;
}

.viewMore {
  display: flex;
  justify-content: center;
  margin-top: 70px;
}

.viewMoreBtn {
  font-size: 20px;
  background-color: #424954;
  color: #6cd6e3;
  padding: 10px 20px;
  border-radius: 5px;
}

a {
  text-decoration: none;
}
</style>
