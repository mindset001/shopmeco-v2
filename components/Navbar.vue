<template>
  <v-card
    class="mx-auto overflow-hidden"
    height="50"
    flat
  >
    <v-app-bar
      color="#7029FF"
      dark
    >
      <v-app-bar-nav-icon @click="drawer = true"></v-app-bar-nav-icon>

       <div class="logo">
        <a href="/"><img src="../assets/images/Mask group.png" alt=""></a>
      </div>
    </v-app-bar>

    <v-navigation-drawer
      v-model="drawer"
      absolute
      temporary
    >
      <v-list
        nav
        dense
      >
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-home</v-icon>
            </v-list-item-icon>
            <li style="color: #FFB74C;"><a href="/">Home</a></li>
          </v-list-item>

            <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-account</v-icon>
            </v-list-item-icon>
            <li><a href="about">About</a></li>
          </v-list-item>

          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-account</v-icon>
            </v-list-item-icon>
            <li><a href="contact">Contact</a></li>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
  </v-card>
</template>

<script>
  export default {
    data: () => ({
      drawer: false,
      group: null,
    }),
  }
</script>