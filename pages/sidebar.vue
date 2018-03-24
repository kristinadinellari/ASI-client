<template>
  <div>
    <div class="sidenav">
      <i class="fa fa-bars" aria-hidden="true"></i>
      <h1>Menu</h1>
      <nuxt-link to="/sidebar/yourprojects">Your project</nuxt-link>
      <nuxt-link to="/sidebar/tasks">Your Tasks</nuxt-link>
      <a>Create Project</a>
    </div>
    <nuxt-child/>
  </div>
</template>
