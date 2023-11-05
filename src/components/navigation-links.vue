<template>
  <nav class="navigation-links-nav" v-bind:class="rootClassName">
    <span class="navigation-links-text Navigation-Link">{{ link1 }}</span>
    <span class="navigation-links-text1 Navigation-Link">{{ link2 }}</span>
    <span class="navigation-links-text2 Navigation-Link">{{ link3 }}</span>
    <span class="navigation-links-text3 Navigation-Link">{{ link4 }}</span>
    <span class="navigation-links-text4 Navigation-Link">{{ link5 }}</span>
  </nav>
</template>

<script>
export default {
  name: 'NavigationLinks',
  props: {
    rootClassName: String,
    link2: {
      type: String,
      default: 'Services',
    },
    link3: {
      type: String,
      default: 'Resources',
    },
    link1: {
      type: String,
      default: 'Home',
    },
    link4: {
      type: String,
      default: 'Contact',
    },
    link5: {
      type: String,
      default: 'Client Login',
    },
  },
}
</script>

<style scoped>
.navigation-links-nav {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navigation-links-text {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
}
.navigation-links-text:hover {
  color: var(--dl-color-scheme-pink);
}
.navigation-links-text1 {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
  margin-left: var(--dl-space-space-threeunits);
}
.navigation-links-text1:hover {
  color: var(--dl-color-scheme-pink);
}
.navigation-links-text2 {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
  margin-left: var(--dl-space-space-threeunits);
}
.navigation-links-text2:hover {
  color: var(--dl-color-scheme-pink);
}
.navigation-links-text3 {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
  margin-left: var(--dl-space-space-threeunits);
}
.navigation-links-text3:hover {
  color: var(--dl-color-scheme-pink);
}
.navigation-links-text4 {
  color: var(--dl-color-scheme-white);
  cursor: pointer;
  transition: 0.3s;
  margin-left: var(--dl-space-space-threeunits);
  padding-top: var(--dl-space-space-halfunit);
  border-color: var(--dl-color-scheme-pink);
  border-width: 5px;
  padding-left: 4px;
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: 4px;
  padding-bottom: var(--dl-space-space-halfunit);
}
.navigation-links-text4:hover {
  color: var(--dl-color-scheme-pink);
}








@media(max-width: 767px) {
  .navigation-links-nav {
    align-items: flex-start;
    flex-direction: column;
  }
  .navigation-links-text {
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text1 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text2 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text3 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
  .navigation-links-text4 {
    margin-left: 0;
    margin-bottom: var(--dl-space-space-unit);
  }
}
</style>
