<script>
export default {
  name: "Our Servive",
  data() {
    return {};
  },
};
</script>
<template>
  <div class="ourservice my-5">
    <div class="container mt-5">
      <h5 class="mb-3 text-center">Our Service</h5>
      <h2 class="mb-1 text-center">Animations, Bespoke and Beautiful</h2>
      <p class="mb-3 text-center">
        With the magic of imagination we are able to tell stories, animate
        adventures, create art,
      </p>
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card rounded-4">
            <div class="card-image mx-auto">
              <img src="/img/ourservice1.png" class="w-50 h-50" alt="" />
            </div>
            <div class="card-body text-center">
              <h5 class="card-title">Motion Graphics</h5>
              <p class="card-text">
                The best in the business, served to your audience’s eyeballs.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card rounded-4">
            <div class="card-image mx-auto">
              <img src="/img/ourservice2.png" class="w-50 h-50" alt="" />
            </div>
            <div class="card-body text-center">
              <h5 class="card-title">Character Design</h5>
              <p class="card-text">
                The best in the business, served to your audience’s eyeballs.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card rounded-4">
            <div class="card-image mx-auto">
              <img src="/img/ourservice3.png" class="w-50 h-50" alt="" />
            </div>
            <div class="card-body text-center">
              <h5 class="card-title">Storyboards</h5>
              <p class="card-text">
                The best in the business, served to your audience’s eyeballs.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card rounded-4">
            <div class="card-image mx-auto">
              <img src="/img/ourservice4.png" class="w-50 h-50" alt="" />
            </div>
            <div class="card-body text-center">
              <h5 class="card-title">Animatics</h5>
              <p class="card-text">
                The best in the business, served to your audience’s eyeballs.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card rounded-4">
            <div class="card-image mx-auto">
              <img src="/img/ourservice5.png" class="w-50 h-50" alt="" />
            </div>
            <div class="card-body text-center">
              <h5 class="card-title">Film and TV</h5>
              <p class="card-text">
                The best in the business, served to your audience’s eyeballs.
              </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card rounded-4">
            <div class="card-image mx-auto">
              <img src="/img/ourservice4.png" class="w-50 h-50" alt="" />
            </div>
            <div class="card-body text-center">
              <h5 class="card-title">Script writing</h5>
              <p class="card-text">
                The best in the business, served to your audience’s eyeballs.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped lang="scss">
h2 {
  font-size: 57px;
  font-weight: 700;
}

h5 {
  font-size: 24px;
  padding-top: 20px;
  line-height: 25px;
  font-weight: bold;
  color: #4d36dc;
}

p {
  font-size: 18px;
}
.card-image {
  width: 140px;
  height: 140px;
  background: #fff5f0;
  margin: 0 auto;
  margin-bottom: 20px;
  border-radius: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.card-title {
  font-size: 30px;
}
.card-body {
  text-align: center;
}

.card-text {
  font-size: 18px;
}

.card {
  padding: 20px;
  box-shadow: 0px 8px 18px 0px rgba(48, 5, 108, 0.05);
}
</style>
