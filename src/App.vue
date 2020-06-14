<template>
  <div>
    <div class="q-pa-md flex flex-center">
      <q-btn round size="0px" margin="0px" padding="0px" outline="true">
        <q-circular-progress
          show-value
          font-size="10px"
          class="q-ma-md"
          :value="value"
          size="50px"
          :thickness="0.25"
          color="primary"
          track-color="grey-3"
        >
          <q-avatar size="40px">
            <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg">
          </q-avatar>
        </q-circular-progress>
      </q-btn>
    </div>
  </div>
</template>

<script>

export default {
  name: 'LayoutDefault',

  data () {
    return {
      value: 10,
      categorias:[
        {
          name: 'Alimentação', 
          percentual: 75, 
          icone: "https://img.icons8.com/plasticine/100/000000/food.png"
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  
</style>