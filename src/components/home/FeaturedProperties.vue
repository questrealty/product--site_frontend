<template>
  <div class="container">
    <div>
      <h1>Our Featured Properties</h1>
      <p>
        This shows the list of our featured properties, they inlclude houses for
        sale and apartments for rent.
      </p>
      <div>
        <div class="properties">
          <img src="" alt="" />
          <div class="flex">
            <div class="details">
              <h4>5 Bedroom Bungalow</h4>
              <p>104 Banana</p>
            </div>
            <div class="pricing"></div>
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

<style></style>
