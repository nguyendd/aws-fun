<template>
    <div>
        <div class="tl">{{favoriteColor}}</div>
        <div class="tr">{{favoriteColor}}</div>
        <div class="bl">{{favoriteColor}}</div>
        <div class="br">{{favoriteColor}}</div>
    </div>
</template>

<script>
export default {
  name: 'Quadrant',
  props: {
    favoriteColor: String
  }
}
</script>

<style>
    .tl {
        background: red;
        position: absolute;
        top: 0;
        left: 0;
        right: 50%;
        bottom: 50%;
        border: 10px solid black;
        margin: 0px -1px;
        /* border:solid #000; 
        border-width: 0 10px 10px 0;  */
        /** TOP RIGHT BOTTOM LEFT*/
    }

    .tr {
        background: blue;
        position: absolute;
        top: 0;
        left: 50%;
        right: 0;
        bottom: 50%;
        border: 10px solid black;
        margin: 0px -1px;
    }

    .bl {
        background: yellow;
        position: absolute;
        top: 50%;
        left: 0;
        right: 50%;
        bottom: 0;
        border: 10px solid black;
        margin: 0px -1px;
    }

    .br {
        background: green;
        position: absolute;
        top: 50%;
        left: 50%;
        right: 0;
        bottom: 0;
        border: 10px solid black;
        margin: 0px -1px;
    }
    /* .tl { position: absolute; top: 0; left: 0; right: 30%; bottom: 30%; 
        background: red; border:solid #000; border-width: 0 10px 10px 0; }
    .tr { position: absolute; top: 0; left: 70%; right: 0; bottom: 30%; 
        background: blue; border:solid #000; border-width: 0 0 10px 0; }
    .bl { position: absolute; top: 70%; left: 0; right: 30%; bottom: 0; 
        background: yellow; border:solid #000; border-width: 0 10px 0 0; }
    .br { position: absolute; top: 70%; left: 70%; right: 0; bottom: 0; 
        background: green; }  */
</style>