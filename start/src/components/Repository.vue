<template>
  <div class="mb-6">
    <section class="hero is-medium is-primary is-bold mb-6">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">Get GitHub Repositories</h1>
          <h2 class="subtitle">using Vue JS, REST API &amp; Bulma</h2>
        </div>
      </div>
    </section>
    <div class="container">
      <div class="table-container">
        <table class="table is-bordered is-striped is-hoverable is-fullwidth">
          <thead>
            <tr>
              <th>ID</th>
              <th>Name</th>
              <th>URL</th>
              <th>Language</th>
              <th>Login</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>245888387</td>
              <td>Bootstrap4-Project-Corporate</td>
              <td>https://github.com/bibeva/Bootstrap4-Project-Corporate</td>
              <td>HTML</td>
              <td>bibeva</td>
            </tr>
            <tr>
              <td>314196361</td>
              <td>Vue-Project-VueBasics</td>
              <td>https://github.com/bibeva/Vue-Project-VueBasics</td>
              <td>Vue</td>
              <td>bibeva</td>
            </tr>
            <tr>
              <td>276947153</td>
              <td>React-AntDesign-Project-Tech</td>
              <td>https://github.com/bibeva/React-AntDesign-Project-Tech</td>
              <td>JavaScript</td>
              <td>bibeva</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Repository",
};
</script>

<style>
body {
  font: 15px/1.8 "Poppins", sans-serif !important;
}

.table td,
.table th {
  padding: 20px !important;
}
</style>