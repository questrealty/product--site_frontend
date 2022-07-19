<template>
  <div class="container flex">
    <div class="inner-container">
      <h1 class="topic">Our Featured Properties</h1>
      <p class="sub-topic">
        This shows the list of our featured properties, they inlclude houses for
        sale and apartments for rent.
      </p>
      <div class="properties-container">
        <div
          class="properties flex"
          v-for="(property, index) in featuredProperties"
          :key="index"
        >
          <img :src="`../../assets/${property.image}.png`" alt="" />
          <div class="property-info flex">
            <div class="details">
              <h4>{{ property.propertyType }}</h4>
              <p>{{ property.location }}</p>
            </div>
            <div class="pricing flex">
              <h3>{{ property.price }}</h3>
              <p>{{ property.rooms }}</p>
              <p>{{ property.toilets }}</p>
              <p>{{ property.size }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      featuredProperties: [
        {
          image: "Frame-291",
          propertyType: "5 Bedroom Bungalow",
          location: "104, Banana Island Road, Ikoyi,Lagos.",
          price: "N5,300,000",
          rooms: "5 Bedrooms",
          toilets: "6 Toilets",
          size: "981 Sq.feet",
        },
        {
          image: "Frame-291-1",
          propertyType: "4 Bedroom Bungalow",
          location: "501 Close, Off 3rd Avenue, Banana Island, Lagos.",
          price: "N4,000,000",
          rooms: "4 Bedrooms",
          toilets: "4 Toilets",
          size: "781 Sq.feet",
        },
        {
          image: "Frame-291-5",
          propertyType: "3 Bedroom Duplex",
          location: "3 &4, Water Corperation Road, Victoria Island, Lagos.",
          price: "N12,300,000",
          rooms: "3 Bedrooms",
          toilets: "5 Toilets",
          size: "988 Sq.feet",
        },
        {
          image: "Frame-291-2",
          propertyType: "5 Bedroom Bungalow",
          location: "501 Close, Off 3rd Avenue,Banana Island, Lagos. ",
          price: "N5,300,000",
          rooms: "5 Bedrooms",
          toilets: "6 Toilets",
          size: "1081 Sq.feet",
        },
        {
          image: "Frame-291-3",
          propertyType: "5 Bedroom Duplex",
          location: "3 &4, Water Corperation Road,Victoria Island, Lagos.",
          price: "N22,000,000",
          rooms: "5 Bedrooms",
          toilets: "6 Toilets",
          size: "1081 Sq.feet",
        },
        {
          image: "Frame-291-4",
          propertyType: "4 Bedroom Bungalow",
          location: "230, Banana Island Road, Ikoyi,Lagos.",
          price: "N6,800,000",
          rooms: "4 Bedrooms",
          toilets: "3 Toilets",
          size: "1012 Sq.feet",
        },
      ],
    };
  },
};
</script>

<style scoped>
.flex {
  display: flex;
  justify-content: center;
  align-items: center;
}
.container {
  width: 100%;
  padding: 120px 0;
}

.inner-container {
  width: 90%;
}

.topic,
.sub-topic {
  text-align: center;
}
.properties {
  width: 100%;
  padding: 16px 4px;
  flex-direction: column;
  margin-top: 80px;
  background-color: #fff;
  box-shadow: 1px 4px 4px rgba(0, 0, 0, 0.363);
  border-radius: 8px 56px;
}

img {
  width: 100%;
}

.property-info {
  padding: 12px;
  width: 100%;
}

.pricing {
  flex-direction: column;
}

.details,
.pricing {
  width: 50%;
}

.details > p,
.pricing > p {
  font-size: 12px;
}
@media (min-width: 700px) {
  .properties-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  .properties {
    flex: 1 1 45%;
    margin-right: 12px;
  }
}

@media (min-width: 1000px) {
  .properties {
    flex: 1 1 30%;
    margin-right: 20px;
  }
}

@media (min-width: 1000px) {
  .properties {
    flex: 1 1 30%;
    margin-right: 20px;
  }
}
</style>
