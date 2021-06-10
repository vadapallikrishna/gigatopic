<template>
  <div id="app">
    <div id="nav">
      <b-navbar>
        <template #brand>
           <b-navbar-item tag="router-link" :to="{ path: '/' }">
              GigaTopic
           </b-navbar-item>
        </template>
        <template #start>
          <b-navbar-item href="/">
                Home
          </b-navbar-item>
          <b-navbar-item href="/new">
                NewPost
          </b-navbar-item>
          <b-navbar-item href="/about">
                About
          </b-navbar-item>
        </template>
      </b-navbar>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
