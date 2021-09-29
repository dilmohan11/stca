<template>
  <section class="form-container">
      <div class="form">
          <h3 class="text-4xl text-center p-5">Fill out the Players below:</h3>
      </div>
      <form class="max-w-screen-sm my-5 mx-auto">
          <!-- <label> Player Name </label> -->
          <div class="flex  self-center py-5">
              <div class="w-1/2 flex gap-3">
                <label class="text-xl font-medium text-green-900 block ">Select Date:</label>
                <input type="date" name="date" class="block border border-green-700" v-model="date">
              </div>
              <div class="w-1/2 flex justify-end gap-2">
                <label class="text-xl font-medium text-green-900 block ">Select Time:</label>
                <select v-model="time" class="border-2 border-green-700">
                    <option value="03.00 PM">03.00 PM</option>
                    <option value="04.00 PM">04.00 PM</option>
                    <option value="05.00 PM">05.00 PM</option>
                </select>
              </div>
          </div>
          
          <label class="text-xl font-medium text-green-900">Select Number of Players</label>
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
          <div class="flex self-center" v-for="n in +playerNo" :key="n">
                <input type="text" v-model="playerName[n-1]" 
                    placeholder="Player Name" 
                    class="w-full p-2 rounded-md border-2 border-green-700 font-semibold my-3"
                    required>
               
          </div>
          <!-- <input type="text" v-model="playerName" placeholder="Player Name" class="w-full p-2 rounded-md border-2 border-green-700 font-semibold"> -->
        <div class="submit text-center">
            <button class="text-lg px-2 py-4 font-semibold rounded-xl mt-5 bg-green-700 text-white
                            hover:bg-green-900 transform transition ease-linear duration-200">
                Submit Players
            </button>
        </div>
      </form>
      <p v-for="n in +playerNo" :key="n">{{ playerName[n-1] }}</p>
      <p>{{ playerNo }}</p>
      <p>{{ date }}</p>
      <p>{{ time }}</p>
  </section>
</template>

<script>
export default {
    data() {
        return {
            playerName: [],
            playerNo: 1,
            date:'',
            time: '',
            error:''
        }
    },
   
}
</script>

<style>

</style>