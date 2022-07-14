<template>
  <div class="container">
    <div class="inner-container">
      <div class="text">
        <div class="inner-text-container">
          <h1>Why People Choose Quest Realty</h1>
          <h3>Finding Your Dream Home</h3>
          <p>
            There is no better feeling than walking through the door to your new
            house and knowing you are fully home. At Quest realty we make this
            dream a happy reality.
          </p>

          <h3>Best Home Guarantee</h3>
          <p>
            Coming home is one of the most beautiful things only the best houses
            with fully working amenities are listed on our platform.
          </p>
        </div>
      </div>
      <div class="image">
        <img src="../../assets/Frame-290.png" alt="perfect-house" />
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  background-color: var(--barley-120);
  width: 100%;
  padding: 84px 0;
  margin: 80px 0 120px;
}

h1 {
  color: var(--barley-40);
  margin-bottom: 4px;
}
h3 {
  margin: 24px 0 16px;
  color: #a37f5d;
}

.text {
  display: flex;
  justify-content: center;
}

.inner-text-container {
  width: 80%;
}

.image {
  padding-top: 60px;
}

img {
  max-width: 100%;
}

@media (min-width: 700px) {
  .container {
    padding: 84px 32px;
  }
  .inner-container {
    display: flex;
    flex-direction: row-reverse;
  }

  .image,
  .text {
    width: 50%;
    padding-top: 0;
  }
}
</style>
