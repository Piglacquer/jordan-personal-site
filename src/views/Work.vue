<template>
  <div class='work'>
    <div class='work-block'>
      <div class='work-stacked'>
        <div class='stack-1'></div>
        <div class='stack-2'></div>
      </div>
      <div></div>
    </div>
  </div>
</template>
//  https://vimeo.com/jordantexalona    My Vimeo profile page

// https://vimeo.com/316501174     Red Music- "Nostalgia" (Editing/Color grading/Color Correction/ VFX)       

// https://vimeo.com/274867503    "Words Unspoken" Short Film (DP/Camera)

// https://vimeo.com/222848548    "Texalona 2" Trailer (Direct/DP/Edit)

// https://vimeo.com/109371768    Blaze Supply - Flo Marfaing - Aloe Vera Kush Pro Model Advert

// https://vimeo.com/240745254    Yawwn & John Debt - "Debt Done Did It Again" (Directing/DP/Editing)

// https://vimeo.com/234875827    "Shit Luck" Short Film (Writer/Director)

// https://vimeo.com/274884685    "Window Screen" Short Film (DP)

// https://vimeo.com/270184093    "Stairs Berlin" Documentary (DP)

// https://vimeo.com/297917501/06783389db    PH Flavours Germany 2018 (2nd Camera)

// https://vimeo.com/297916116/b8183b11d1    Mama Sita's "Flavors of The Philippine Islands" (2nd Camera)

// https://vimeo.com/270190507    EpicTV "Shred The List" EP #1 Morocco (Director/DP/Editor)
<script>

export default {
  name: 'work',
  components: {}
}
</script>

<style scoped>
  .work {
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    height: auto;
  }
  .work-block {
    display: flex;
    flex-flow: row nowrap;
    height: 50vh;
    width: 75vw;
    background-color: white;
  }
  .work-stacked {
    display: flex;
    flex-flow: column nowrap;
    width: 33%;
    height: 100%
  }
  .stack-1 {
    background-color: green;
    height: 50%
  }
  .stack-2 {
    background-color: red;
    height: 50%
  }
</style>
