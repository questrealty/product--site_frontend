<template>
  <div>
    <div class="container">
      <div class="inner-container">
        <div class="image">
          <img src="../../assets/Frame 290.png" alt="perfect-house" />
        </div>
        <div class="text">
          <div class="inner-text-container">
            <h1>Find Your Next Perfect Place To Live</h1>
            <p>
              There is no better feeling than walking through the door to your
              new house and knowing you are fully home. At Quest Realty we make
              this dream a happy reality.
            </p>
            <button class="btn">Learn More</button>
          </div>
        </div>
      </div>
    </div>

    <div class="banner-container">
      <div class="banner">
        <div class="banner-item location">
          <div class="title">
            <img src="../../assets/location.png" alt="Location icon" />
            <h3>Location</h3>
          </div>
          <div class="details">
            <p>Choose State</p>
            <img
              src="../../assets/down-arrow.png"
              alt="Down Arrow"
              width="14"
            />
          </div>
        </div>
        <div class="banner-item property-type">
          <div class="title">
            <img src="../../assets/property.png" alt="Location icon" />
            <h3>Property type</h3>
          </div>
          <div class="details">
            <p>Choose Type</p>
            <img
              src="../../assets/down-arrow.png"
              alt="Down Arrow"
              width="14"
            />
          </div>
        </div>
        <div class="banner-item price-range">
          <div class="title">
            <img src="../../assets/moneys.png" alt="Location icon" />
            <h3>Price range</h3>
          </div>
          <div class="details">
            <p>Choose price</p>
            <img
              src="../../assets/down-arrow.png"
              alt="Down Arrow"
              width="14"
            />
          </div>
        </div>
        <div class="banner-item search">
          <button type="search">Search</button>
        </div>
      </div>
    </div>
    <!-- <div v-for="(_, index) in 40" :key="index">Helo</div> -->
  </div>
</template>

<script setup></script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  width: 100%;
  margin-bottom: 60px;
}

img {
  max-width: 100%;
}
.text {
  /* padding: 0px 32px; */

  display: flex;
  justify-content: center;
}
.inner-text-container {
  width: 80%;
}

h1 {
  margin-bottom: 24px;
}

button {
  padding: 10px 20px;
  color: white;
  background-color: var(--barley-40);
  border-radius: 4px;
  outline: none;
  border: none;
  margin-top: 20px;
}

.banner-container {
  display: flex;
  justify-content: center;
}

.banner {
  width: 80%;
  background: #fff;
  box-shadow: 1px 4px 8px rgba(0, 0, 0, 0.582);
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  padding: 4px 12px;
  margin-bottom: 120px;
}

.banner-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 4px 12px;
  margin: 4px 4px 28px;
  flex: 1 1 100%;
}
h3 {
  margin-left: 2px;
}

.details > img {
  height: 10px;
  margin-left: 2px;
}
.title,
.details {
  display: flex;
  align-items: center;
}

@media (min-width: 520px) {
  .banner-item {
    flex: 1 1 33%;
  }
}
@media (min-width: 700px) {
  .container {
    padding: 40px 32px;
  }
  .inner-container {
    display: flex;
    flex-direction: row-reverse;
  }

  .image,
  .text {
    width: 50%;
  }

  img {
    height: 100%;
  }
}
@media (min-width: 1024px) {
  .banner-item {
    flex: 1 1 20%;
  }
}
</style>
