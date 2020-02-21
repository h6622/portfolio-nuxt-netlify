<template>
  <div class="navBar container">
    <div>title</div>
    <div>
      <ul v-for="item in menuItems" :key="item" class="menuItems">
        <li class="menuItem" @click="onClickButton(item)">{{ item }}</li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      menuItems: ['Home', 'About', 'Skill', 'Project', 'Contact']
    }
  },
  methods: {
    onClickButton(item) {
      if (item === 'Home') {
        window.scrollTo({
          top: 0,
          behavior: 'smooth'
        })
      } else if (item === 'About') {
        window.scrollTo({
          top: 600,
          behavior: 'smooth'
        })
      } else if (item === 'Skill') {
        window.scrollTo({
          top: 1300,
          behavior: 'smooth'
        })
      } else if (item === 'Project') {
        window.scrollTo({
          top: 1717,
          behavior: 'smooth'
        })
      } else {
        window.scrollTo({
          top: 1717,
          behavior: 'smooth'
        })
      }
    }
  }
}
</script>
<style scoped>
.navBar {
  position: fixed;
  display: flex;
  justify-content: space-between;
  padding-top: 30px;
}

.menuItem {
  list-style-type: none;
  margin: 10px;
}

.menuItems {
  float: left;
}

.thisScroll {
  scroll-behavior: smooth;
}
</style>
