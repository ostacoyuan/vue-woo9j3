<template>
  <div id="prof-com">
    <div id="todo-card">
      <div class="container">
        <div class="alert alert-primary" role="alert">
          <h1>{{ msg3 }}</h1>
        </div>
        <h2><strong>Applicant Name:</strong></h2>
        <h3>Ostaco River Yuan M.</h3>
        <h2><strong>Age</strong></h2>
        <h3>20 Years of Age</h3>
        <h2><strong>Course</strong></h2>
        <h3>BSIT Major in Web Development</h3>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'prof-com',
  data() {
    return {
      msg3: 'This is the Profile Component',
    };
  },
};
</script>
