<template>
  <div class="navBar container">
    <div>title</div>
    <div>
      <ul v-for="item in menuItems" :key="item" class="menuItems">
        <li class="menuItem">{{ item }}</li>
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
