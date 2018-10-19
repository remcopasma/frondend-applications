<template>
  <div class="container">
    <form> 
      <fieldset>
        <legend>Bereken het risico op een zware maatregel</legend>
        <label><Question/></label>   
      </fieldset>
    </form>
  </div>
</template>

<script>
import Question from './Question'  // Importeer component Question.vue
export default {
  name: 'MainLeft',
  components:{
  Question
}
}
</script>
<style>
@import '../components/style.css';
</style>