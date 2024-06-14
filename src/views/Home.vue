<template>
  <div class="home">
    <h1>My Recipes</h1>
    <button>Add new Recipe</button>
    <div class="recipes">

    </div>

    <div class="add-recipe-popup">
      <div class="popup-content">
        <h2>Add new recipe</h2>

        <form @submit.prevent="">
          <div class="group">
            <label>Title</label>
            <input type="text">
          </div>

        </form>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Home'
}
</script>
