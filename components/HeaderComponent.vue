<template>
  <div class="navBar container">
    <div>title</div>
    <div>
      <ul v-for="item in menuItems" :key="item" class="menuItems">
        <li class="menuItem" @click="onClick(item)">{{ item }}</li>
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
    onClick(item) {
      if (item === 'Home') {
        window.scrollTo({
          top: 0,
          behavior: 'smooth'
        })
      } else if (item === 'About') {
        window.scrollTo({
          top: 1080,
          behavior: 'smooth'
        })
      } else if (item === 'Skill') {
        window.scrollTo({
          top: 2160,
          behavior: 'smooth'
        })
      } else if (item === 'Project') {
        window.scrollTo({
          top: 3240,
          behavior: 'smooth'
        })
      } else if (item === 'Contact') {
        window.scrollTo({
          top: 4320,
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

.menuItems {
  float: left;
}

.menuItem {
  list-style-type: none;
  margin-left: 10px;
}
</style>
