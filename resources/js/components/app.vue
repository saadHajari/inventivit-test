<script>
    export default {
      data() {
        return {
          nbr1: 0,
          nbr2: 0,
          operateur:""
        };
      },
    }
</script>



<template>
<section>
  <input name="nb1" placeholder="num1" type="number" >
<select v-model="operateur" > 
  <option value="+"> + </option>
  <option value="-"> - </option>
  <option value="*"> * </option>
  <option value="/"> / </option>
</select>
<input name="nb2" placeholder="num2" type="number" >
<button type="submit" class="btn btn-primary">Calculer</button>
     <div><span>Reponse : {{$result}}</span></div>
 </section>

</template>


