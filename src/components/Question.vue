<template>
 <ul>
    <li v-for="Question in Questions" v-bind:key="Question">   <!-- V-for gebruikt om de code uit Questions te renderen en key om een unieke waarde mee te geven -->
        <label>{{Question.question}}</label> <!-- De vraag ophalen -->
        <select>   <!-- Een select waarin ik de antwoorden(options) ophaal en die ook weer een unieke waarde Options krijgt --> 
            <option v-for="options in Question.options" v-bind:key="options">{{options.label}}</option>
        </select>
    </li>
</ul>
</template>

<script>
import Questions from './Questions'
import risico from './risico'
export default {
data () {
    return{Questions} 
}
}
</script>
<style>
@import '../components/style.css'
</style>