<template>
  <div>
    <b-container>
      <b-row>
        <b-col md="4" offset-md="8">
          <h4>Welcome To Trinity Lutheran</h4>
          <p>Trinity Lutheran Church, School, and Early Learning Center offers a wide variety of services to help you on your faith journey.  Join us for worship and fellowship.</p>
          <b-link to="/church"><b-button>Church</b-button></b-link>
          <b-link to="/school"><b-button>School</b-button></b-link>
          <b-link to="/earlylearningcenter"><b-button>Early Learning Center</b-button></b-link>
          <b-link to="/vist"><b-button>Vist Us</b-button></b-link>
        </b-col>
      </b-row>
      <b-row>
        <b-col>
          <h4>Worship With Us</h4>
        </b-col>
        <b-col>
          <h4>Contact Us</h4>
        </b-col>
        <b-col>
          <h4>Bible Studies</h4>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<style scoped>
button {
  width: 100%;
  display: block;
  margin: 4px 0 4px 0;
}
</style>
