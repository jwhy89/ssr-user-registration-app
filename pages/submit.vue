<template>
  <div>
    <form>
      <div class="form-group">
        <label for="inputEmail">EMAIL</label>
        <input
          id="inputEmail"
          class="form-control"
          type="email"
          placeholder="kandydat@jamf.com"
          readonly
        />
        <label for="uploadAvatar">Avatar</label>
        <input
          id="input"
          class="form-control"
          type="text"
          placeholder="Group A"
          readonly
        />
        <label for="uploadAvatar">Avatar</label>
        <img
          id="uploadAvatar"
          src="~/assets/kcmpdclpdcv.png"
          alt="Avatar"
          border-radius="50%"
        />
      </div>
      <div class="btn-position">
        <button type="reset" class="btn">Cancel</button>
        <div class="divider"></div>
        <button type="submit" class="btn btn-primary">Next</button>
      </div>
    </form>
  </div>
</template>
