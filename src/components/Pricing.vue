<template>
  <div class="pricing">
    <div class="container">
      <div class="pricing-wrapper">
        <div class="pricing-wrapper__title">
          Are you ready to grow your <br />business with us?
        </div>
        <div class="pricing-wrapper__subtitle">
          Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
          nonumy.
        </div>
        <div class="pricing-item">
          <button class="pricing-btn">View Pricing</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Pricing",
};
</script>

<style lang="scss" scoped>
.pricing {
  padding: 50px 0px;
  background: #cfecec;
}
.pricing-wrapper {
  display: flex;
  flex-direction: column;
  gap: 40px;
  text-align: center;
}
.pricing-wrapper__title {
  font-size: 40px;
  font-weight: bold;
  cursor: pointer;
}
.pricing-wrapper__subtitle {
  font-size: 18px;
  cursor: pointer;
}
.pricing-btn {
  cursor: pointer;
  padding: 16px 40px;
  border-radius: 10px;
  background: #1d2130;
  color: white;
  font-size: 14px;
}
.pricing-btn:active {
  color: #B2D2FB;
}
.pricing-btn:hover {
  transition: 0.3s;
  box-shadow: inset 30px 0 0 0 #4094ff;
}
@media screen and (max-width: 992px) {
  .pricing-wrapper__title {
    font-size: 30px;
  }
  .pricing-wrapper__subtitle {
    font-size: 15px;
  }
}
@media screen and (max-width: 576px) {
  .pricing-wrapper__title {
    font-size: 24px;
  }
  .pricing-wrapper__subtitle {
    font-size: 13px;
  }
  .pricing-btn {
    padding: 12px 30px;
    font-size: 12px;
  }
  .pricing-wrapper {
    gap: 20px;
  }
}
</style>
