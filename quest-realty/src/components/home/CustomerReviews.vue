<template>
  <div class="main-container flex">
    <div class="dots">
      <img src="../../assets/group-71.png" alt="dots" />
    </div>
    <div>
      <h1>Customer Reviews</h1>
      <div class="reviews flex">
        <div class="review">
          <div class="one">
            <div class="float-left">
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Orci
                erat vestibulum ac non. Lorem ipsum dolor sit amet, consectetur
                adipiscing elit. Orci erat vestibulum ac non. Lorem ipsum dolor
                sit amet, consectetur adipiscing elit. Orci erat vestibulum ac
                non.
              </p>
              <div class="flex customer-info">
                <img src="../../assets/image-1.png" alt="customer 1" />
                <div>
                  <h3>Hope Franklin</h3>
                  <p>Customer</p>
                </div>
              </div>
            </div>
          </div>
          <div class="two">
            <div class="float-right">
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Orci
                erat vestibulum ac non. Lorem ipsum dolor sit amet, consectetur
                adipiscing elit. Orci erat vestibulum ac non. Lorem ipsum dolor
                sit amet, consectetur adipiscing elit. Orci erat vestibulum ac
                non.
              </p>
              <div class="flex customer-info">
                <img src="../../assets/image-2.png" alt="customer 2" />
                <div>
                  <h3>Hope Franklin</h3>
                  <p>Customer</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex">
        <button class="btn">See More Reviews</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.main-container {
  padding: 120px 0;
  flex-direction: column;
  height: fit-content;
}

.dots {
  display: flex;
  justify-content: flex-end;
  padding: 0 36px;
  width: 100%;
  height: fit-content;
}

.dots > img {
  width: 60px;
  height: 80px;
  margin-bottom: 24px;
}

h1 {
  text-align: center;
  color: var(--barley-40);
  margin-bottom: 80px;
}

.review {
  width: 90%;
}

.float-left,
.float-right {
  border-radius: 8px 56px;
  background-color: var(--barley-120);
  padding: 12px 24px;
  margin-bottom: 40px;
}

.one {
  display: flex;
  justify-content: flex-start;
}

.two {
  display: flex;
  justify-content: flex-end;
}

.float-left > p,
.float-right > p {
  font-size: 14px;
}

.customer-info {
  justify-content: flex-start;
}

button {
  background-color: #6d553e;
  color: white;
  padding: 16px 32px;
  border-radius: 5px;
  font-weight: 700;
  font-size: 16px;
  outline: none;
  border: none;
  cursor: pointer;
  margin-top: 24px;
}

button:hover {
  box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
}

@media (min-width: 786px) {
  .dots > img {
    width: 91px;
    height: 136px;
    margin-bottom: 0;
  }
  .float-left,
  .float-right {
    width: 60%;
  }
}

@media (min-width: 1200px) {
  .float-left,
  .float-right {
    width: 40%;
  }
}
</style>
