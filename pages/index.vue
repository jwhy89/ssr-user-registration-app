<template>
  <div class="specific-page">
    <form>
      <div class="form-group">
        <label for="inputEmail">EMAIL</label>
        <input
          id="inputEmail"
          type="email"
          class="form-control"
          aria-describedby="emailHelp"
          placeholder="[Required]"
        />
      </div>
      <div class="form-group">
        <label for="inputPassword">PASSWORD</label>
        <input
          id="inputPassword"
          type="password"
          class="form-control"
          placeholder="[Required]"
        />
      </div>
      <div class="form-group">
        <label for="verifyInputPassword">VERIFY PASSWORD</label>
        <input
          id="verifyInputPassword"
          type="password"
          class="form-control"
          placeholder="[Required]"
        />
      </div>
      <button type="reset" class="btn">Cancel</button>
      <button type="submit" class="btn btn-primary">Next</button>
    </form>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style></style>
