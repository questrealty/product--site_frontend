<template>
  <div class="container">
    <h3>Agents and Partners</h3>
    <div class="image__container">
      <div class="agents-1">
        <img src="../assets/Frame-299-1.png" alt="" class="image1" />
        <img src="../assets/Frame-300-1.png" alt="" class="image2" />
      </div>

      <div class="agents-2">
        <img src="../assets/Frame-302.png" alt="" class="image3" />
        <img src="../assets/Frame-301-1.png" alt="" class="image4" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  setup() {},
};
</script>

<style scoped>
@import url(https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;800;900&display=swap);

.container {
  width: 100%;
  font-family: "Poppins", sans-serif;
  background-color: #ede5df;
  padding: 16px 20px;
}

h3 {
  font-size: 40px;
  font-weight: 700;
  color: #6d553e;
  text-align: center;
  margin-bottom: 64px;
}

.image__container {
  display: flex;
  flex-direction: column;
  /* justify-content: space-between; */
}
.agents-1,
.agents-2 {
  width: 100%;
  display: flex;
  justify-content: space-between;
  margin-bottom: 24px;
}

img {
  max-width: 150px;
}

@media (min-width: 460px) {
  img {
    max-width: 250px;
  }
}

@media (min-width: 640px) {
}

@media (min-width: 786px) {
  .container {
    padding: 74px 80px;
  }
  img {
    max-width: 200px;
  }
  .image__container {
    flex-direction: row;
  }
}
</style>
