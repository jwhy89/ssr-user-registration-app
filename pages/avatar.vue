<template>
  <div>
    <form>
      <label for="uploadAvatar">Avatar</label>
      <small id="avatarHelp" class="form-text text-muted"
        >User Avatar. It is recommended that you use a file with the GIF or PNG
        format. The recommended size is 512x512 pixels</small
      >
      <div class="form-group">
        <img src="~/assets/kcmpdclpdcv.png" alt="Avatar" border-radius="50%" />
        <input id="uploadAvatar" type="file" class="form-control-file" />
      </div>
      <div class="btn-position">
        <button type="reset" class="btn">Cancel</button>
        <div class="divider" />
        <nuxt-link to="/submit" prefetch>
          <button type="submit" class="btn btn-primary">Next</button>
        </nuxt-link>
      </div>
    </form>
  </div>
</template>
