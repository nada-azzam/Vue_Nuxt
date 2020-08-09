<template>
  <div class="row">
    <div class="col-md-4">
      <div class="card mb-3">
        <img src="https://bw.kioncm.com/storage/6/3.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card {{homeDate}} </h5>
          <p
            class="card-text"
          >This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card mb-3">
        <img src="https://bw.kioncm.com/storage/6/3.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p
            class="card-text"
          >This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card mb-3">
        <img src="https://bw.kioncm.com/storage/6/3.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p
            class="card-text"
          >This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import axios from 'axios'
export default {
  head: { title: "Home" },
  // data() {
  //   return { project: 'default' }
  // },
  asyncData(context) {
    return axios.get( process.env.baseUrl + "/settings" ).then((res) => {
      console.log(res)
      return {homeDate:res.data}
    });
  },
};
</script>

<style>
</style>