<template>
  <v-app>
    <!-- Navigation Drawer (Hidden on Mobile) -->
    <v-navigation-drawer
      v-show="!isMobile"
      v-model="drawer"
      app
      color="#3A404D"
      :disable-overlay="true"
    >
      <v-list>
        <v-list-item>
          <v-img
            :src="require('@/assets/logo_mj_portfolio.png')"
            alt="Logo"
            max-width="150"
          ></v-img>
        </v-list-item>
        <div class="menu-list-padding">
          <v-list-item
            v-for="(item, i) in items"
            :key="i"
            :to="item.to"
            router
            exact
          >
            <v-list-item-content>
              <v-list-item-title class="drawer-text">
                {{ item.title }}
              </v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </div>
        <v-list-item class="custom-padding-pattern">
          <v-img
            :src="require('@/assets/pattern_portfolio.png')"
            alt="Logo"
            max-width="500"
          ></v-img>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>

    <!-- App Bar (With Menu for Mobile) -->
    <v-app-bar
      app
      color="#3A404D"
      dark
      v-show="isMobile"
      density="prominent"
      class="custom-app-bar"
    >
      <v-img
        :src="require('@/assets/logo_mj_portfolio.png')"
        alt="Logo"
        max-width="120"
      ></v-img>
      <v-spacer></v-spacer>

      <!-- Menu in App Bar -->
      <v-menu
        v-model="menuVisible"
        offset-y
        :close-on-content-click="true"
        class="d-flex justify-end"
      >
        <template #activator="{ on, attrs }">
          <v-btn icon v-bind="attrs" v-on="on">
            <v-icon>mdi-menu</v-icon>
          </v-btn>
        </template>
        <v-list>
          <v-list-item
            v-for="item in items"
            :key="item.title"
            :to="item.to"
            router
            exact
            @click="menuVisible = false"
          >
            <v-list-item-title>{{ item.title }}</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>

    <!-- Main Content -->
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data() {
    return {
      drawer: true, // Drawer state for larger screens
      menuVisible: false, // Tracks menu visibility on mobile
      items: [
        { title: 'Home', to: '/' },
        { title: 'Work', to: '/work' },
        { title: 'Experience', to: '/experience' },
        { title: 'About', to: '/' },
      ],
    }
  },
  computed: {
    isMobile() {
      return this.$vuetify.breakpoint.smAndDown // True for small screens
    },
  },
  methods: {
    toggleMenu() {
      console.log('App bar button clicked!')
      // Define any mobile menu actions here
    },
  },
}
</script>

<style scoped>
.drawer-title {
  color: white; /* Change title font color */
  font-weight: bold;
}

.drawer-text {
  color: #a0c3c1; /* Change drawer item font color */
}

.v-list-item:hover .drawer-text {
  color: white; /* Change color on hover */
}

.custom-padding-pattern {
  padding-left: 0 !important;
  padding-right: 0 !important;
  padding-top: 100px !important;
}

.menu-list-padding {
  padding-top: 150px;
}

.custom-app-bar {
  min-height: 120px !important; /* Increase the height */
  padding-top: 20px !important; /* Optional: Adjust top padding */
  padding-bottom: 20px !important; /* Optional: Adjust bottom padding */
  display: flex; /* Ensure the content is aligned correctly */
  align-items: center; /* Center the content vertically */
}
</style>
