<template>
  <article class="media">
    <figure class="media-left">
      <i class="fas fa-6x" :class='myClass'></i>
    </figure>
    <div class="media-content">
      <div class="content tempature">
        <p>100 &#176;</p>

        
      </div>
    </div>
    <div class="media-content">
      <div class="content">
        <p>John Smith</p>
      </div>
      <div class="content">
        <p>John Smith</p>
      </div>
      <div class="content">
        <p>John Smith</p>
      </div>
    </div>
  </article>
</template>

<script>
export default {
  data() {
    return {
      myClass: "fa-home"
    }
  }
};
</script>

<style>
.icon {
  color: black !important;
}
.tempature {
  font-size: 70px;
  font-weight: 100;
}
</style>