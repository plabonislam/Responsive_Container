<script setup></script>

<template>
  <div class="card">
    <div class="card-header">
      <img
        src="https://img.freepik.com/premium-vector/angry-wolf-vector-illustration_222085-317.jpg" />
    </div>
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk
        of the card's content.
      </p>

      <button type="button" class="area btn btn-outline-primary">Submit</button>
      <button type="button" class="area btn btn-outline-primary">Cancel</button>
    </div>
  </div>
</template>
<style scoped>
img {
  width: 100%;
  object-fit: cover;
}

.area {
  width: 180px;
}

.card {
  container-type: inline-size;
  container-name:parent
}

.card-bod {
 container-type:inline-size;
}

@container (min-width: 300px) {
  .area {
    width: 100px;
    color:pink;
  }
}

@container parent (max-width: 300px) {
  .area {
    width: 100px;
    text-align:left;
    color:red;
  }
}
</style>
