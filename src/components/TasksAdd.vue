<template>
<div class="container">
    <form>
        <div class="form-group row">
            <label for="input_id" class="col-sm-2 col-form-label">Id Task</label>
            <div class="col-sm-4">
                <input type="numer" class="form-control" id="input_id" placeholder="Id">
                <input type="text" class="form-control" placeholder="Name">
                <input type="number" class="form-control" placeholder="Estimated">
                <input type="number" class="form-control" placeholder="Spent Hours">

                <textarea name="form-control" placeholder="Description" id="description_form" cols="30" rows="3"></textarea>
            </div>
        </div>
        <div class="form-group row">
            <div class="col-sm-4 offset-sm-2">
            <button type="submit" class="btn btn-primary">Add</button>
            </div>

        </div>
    </form>
</div>
</template>

<script>
export default {
  name: 'TasksAdd',
  props: {
    msg: String
  }
}
</script>
