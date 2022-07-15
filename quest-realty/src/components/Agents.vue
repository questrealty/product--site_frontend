<template>
  <div class="container">
    <h3>Agents and Partners</h3>
    <div class="width-regulator">
      <div class="image__container">
        <div class="image one">
          <img src="../assets/Frame-299-1.png" alt="" />
        </div>
        <div class="image two">
          <img src="../assets/Frame-301-1.png" alt="" />
        </div>
        <div class="image three">
          <img src="../assets/Frame-302.png" alt="" />
        </div>
        <div class="image five">
          <img src="../assets/Frame-300-1.png" alt="" />
        </div>
      </div>
    </div>

    <div class="btn-container">
      <button class="more-contacts">View more contacts</button>
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

.width-regulator {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0 20px;
}

.image__container {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  justify-content: space-between;
}
.image {
  flex: 1 1 50%;
  text-align: center;
}

.btn-container {
  display: flex;
  justify-content: center;
  width: 100%;
  margin-top: 60px;
}

.more-contacts {
  background-color: #6d553e;
  color: white;
  padding: 16px 32px;
  border-radius: 5px;
  font-weight: 700;
  font-size: 16px;
  outline: none;
  border: none;
  cursor: pointer;
}

.more-contacts:hover {
  box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
}

@media (min-width: 1024px) {
  .container {
    padding: 74px 40px;
  }

  .width-regulator {
    padding: 0;
  }

  .image {
    flex: 1 1 25%;
  }
}
</style>
