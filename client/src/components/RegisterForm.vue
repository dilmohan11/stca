<template>
  <section class="form-container">
      <div class="form">
          <h3 class="text-4xl text-center p-10">Fill out the Players below:</h3>
      </div>
      <form class="max-w-screen-sm my-8 mx-auto">
          <!-- <label> Player Name </label> -->
          <label>Select Number of Players</label>
          <select v-model="playerNo" class="w-full border-2 p-2 mb-5 border-green-700 bg-white">
              <option value="1">1</option>
              <option value="2">2</option>
              <option value="3">3</option>
              <option value="4">4</option>
              <option value="5">5</option>
              <option value="6">6</option>
              <option value="7">7</option>
              <option value="8">8</option>
              <option value="9">9</option>
              <option value="10">10</option>
              <option value="11">11</option>
          </select>
          <div class="" v-for="n in +playerNo" :key="n">
                <input type="text" v-model="playerName" placeholder="Player Name" class="w-full p-2 rounded-md border-2 border-green-700 font-semibold my-2">
          </div>
          <!-- <input type="text" v-model="playerName" placeholder="Player Name" class="w-full p-2 rounded-md border-2 border-green-700 font-semibold"> -->
      </form>
      <p>{{ playerName }}</p>
      <p>{{ playerNo }}</p>
  </section>
</template>

<script>
export default {
    data() {
        return {
            playerName: '',
            playerNo: '1'
        }
    }
}
</script>

<style>

</style>