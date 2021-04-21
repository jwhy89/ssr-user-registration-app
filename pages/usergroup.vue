<template>
  <div>
    <form>
      <div class="form-group">
        <label for="userGroupFormControl">Choose the User Group</label>
        <p>
          <medium class="text-muted">Hello</medium>
          <small id="emailHelp" class="form-text text-muted"
            >User Group to add the users to</small
          >
        </p>
        <select id="userGroupFormControl" class="form-control">
          <option>None</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </div>
      <div class="btn-position">
        <button type="reset" class="btn">Cancel</button>
        <div class="divider"></div>
        <button type="submit" class="btn btn-primary">Next</button>
      </div>
    </form>
  </div>
</template>
