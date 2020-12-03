<template>
  <div class="container my-5">
    <div class="row">
      <div class="col-md-4">
        <div class="card mb-4 shadow-sm">
          <div class="bg-dark w-100" style="height:200px;"></div>
          <div class="card-body">
            <p class="card-text">
              {{contentText}}
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <div class="btn-group">
                <button type="button" class="btn btn-sm btn-outline-secondary">
                  View
                </button>
                <button type="button" class="btn btn-sm btn-outline-secondary">
                  Edit
                </button>
              </div>
              <small class="text-muted">10 mins</small>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props:{
    contentText: String,
  }
};
</script>

<style>
@import "../../node_modules/bootstrap/dist/css/bootstrap.min.css";
</style>