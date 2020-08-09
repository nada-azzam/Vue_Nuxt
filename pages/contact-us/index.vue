<template>
  <div class="row">
    <div class="col-md-4">
      <div class="form-group">
        <input type="text" name="name" placeholder="Name" class="form-control" />
      </div>
    </div>
    <div class="col-md-4">
      <div class="form-group">
        <input type="text" name="email" placeholder="Email" class="form-control" />
      </div>
    </div>
    <div class="col-md-4">
      <div class="form-group">
        <input type="text" placeholder="Phone" class="form-control" />
      </div>
    </div>
    <div class="col-md-8">
      <div class="form-group">
        <input type="text" name="subject" placeholder="Subject" class="form-control" />
      </div>
    </div>
    <div class="col-md-4">
      <div class="form-group">
        <select class="form-control">
          <option value="0">Services</option>
          <option value="1">Html</option>
          <option value="1">Css</option>
        </select>
      </div>
    </div>
    <div class="col-md-12">
      <div class="form-group">
        <textarea rows="5" placeholder="Message" class="form-control"></textarea>
      </div>
    </div>
    <div class="col-md-2">
      <div class="product-btns">
        <button class="btn btn-secondary">Send Message</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
   head: { title: "Contact Us" } 
   };
</script>

<style>
</style>