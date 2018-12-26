<template lang="html">
  <section class="section">
   <div class="container">
     <div id="videoCardy">
       <videoCards></videoCards>

     </div>
     <div>
       <a
         role="button"
         class="navbar-burger has-text-black is-pulled-left"
         aria-label="menu"
         aria-expanded="false">
         <span aria-hidden="true"/>
         <span aria-hidden="true"/>
         <span aria-hidden="true"/>
       </a>
     </div>
     <div class="container">
       <div class="container has-text-centered image iconed  is-128x128 badge is-badge-bottom is-badge-large  is-badge-dark" data-badge="7">
            <img class="iconed is-paddingless fee is-rounded"src="~assets/images/obama.jpg"lt="">
       </div>
       <div class="container has-text-centered">
        <h1 class="is-size-3 falsePadding"> {{name}} Barack Obama</h1>
        <p> Class of {{classOfyear}} 1983</p>
       </div>
     </div>
   </div>

<div class="container falsePadding2">
  <b-tabs position="is-centered">
   <b-tab-item label="ALL VIDEOS">


   </b-tab-item>
   <b-tab-item label="FAVORITE VIDEO">
     nig
   </b-tab-item>
</b-tabs>
</div>


  </section>
</template>

<script>
export default {
  component:{videoCards}
}
</script>

<style lang="css">
.falsePadding{
  margin-top:8vh;
}

.falsePadding2{
  margin-top:3vh;
}


@-webkit-keyframes spinAround{from{-webkit-transform:rotate(0);transform:rotate(0)}to{-webkit-transform:rotate(359deg);transform:rotate(359deg)}}@keyframes spinAround{from{-webkit-transform:rotate(0);transform:rotate(0)}to{-webkit-transform:rotate(359deg);transform:rotate(359deg)}}.badge{position:relative;white-space:nowrap;position:relative}.badge[data-badge]::after{position:absolute;left:100%;margin:0;background:#00d1b2;background-clip:padding-box;border-radius:1rem;box-shadow:0 0 0 .1rem #fff;color:#fff;content:attr(data-badge);display:inline-block}.badge:not([data-badge=""])::after{padding:.3rem .5rem;text-align:center;white-space:nowrap}.badge[data-badge=""]::after{display:inline-block;vertical-align:inherit}.badge.is-badge-white:not([data-badge])::after,.badge.is-badge-white[data-badge]::after{background:#fff;color:#0a0a0a}.badge.is-badge-black:not([data-badge])::after,.badge.is-badge-black[data-badge]::after{background:#0a0a0a;color:#fff}.badge.is-badge-light:not([data-badge])::after,.badge.is-badge-light[data-badge]::after{background:#f5f5f5;color:#363636}.badge.is-badge-dark:not([data-badge])::after,.badge.is-badge-dark[data-badge]::after{background:#363636;color:#f5f5f5}.badge.is-badge-primary:not([data-badge])::after,.badge.is-badge-primary[data-badge]::after{background:#00d1b2;color:#fff}.badge.is-badge-link:not([data-badge])::after,.badge.is-badge-link[data-badge]::after{background:#3273dc;color:#fff}.badge.is-badge-info:not([data-badge])::after,.badge.is-badge-info[data-badge]::after{background:#209cee;color:#fff}.badge.is-badge-success:not([data-badge])::after,.badge.is-badge-success[data-badge]::after{background:#23d160;color:#fff}.badge.is-badge-warning:not([data-badge])::after,.badge.is-badge-warning[data-badge]::after{background:#ffdd57;color:rgba(0,0,0,.7)}.badge.is-badge-danger:not([data-badge])::after,.badge.is-badge-danger[data-badge]::after{background:#ff3860;color:#fff}.badge.is-badge-outlined[data-badge]::after{background-color:#fff;box-shadow:none;border:.1rem solid #00d1b2;color:#00d1b2}.badge.is-badge-outlined.is-badge-white[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #fff;color:#fff}.badge.is-badge-outlined.is-badge-black[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #0a0a0a;color:#0a0a0a}.badge.is-badge-outlined.is-badge-light[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #f5f5f5;color:#f5f5f5}.badge.is-badge-outlined.is-badge-dark[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #363636;color:#363636}.badge.is-badge-outlined.is-badge-primary[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #00d1b2;color:#00d1b2}.badge.is-badge-outlined.is-badge-link[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #3273dc;color:#3273dc}.badge.is-badge-outlined.is-badge-info[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #209cee;color:#209cee}.badge.is-badge-outlined.is-badge-success[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #23d160;color:#23d160}.badge.is-badge-outlined.is-badge-warning[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #ffdd57;color:#ffdd57}.badge.is-badge-outlined.is-badge-danger[data-badge]::after{background:#fff;box-shadow:none;border:.1rem solid #ff3860;color:#ff3860}.badge[data-badge]::after{top:calc(0px - (1rem / 2));left:calc(100% - (1rem / 2));min-height:1rem;min-width:1rem}.badge:not([data-badge=""])::after{font-size:.75rem;line-height:.5rem}.badge[data-badge=""]::after{width:1rem}.badge.is-badge-left::after{left:calc(0px - (1rem / 2))}.badge.is-badge-bottom::after{top:calc(100% - (1rem / 2))}.badge.is-badge-bottom-left::after{left:calc(0px - (1rem / 2));top:calc(100% - (1rem / 2))}.badge.is-badge-small[data-badge]::after{top:calc(0px - (.75rem / 2));left:calc(100% - (.75rem / 2));min-height:.75rem;min-width:.75rem}.badge.is-badge-small:not([data-badge=""])::after{font-size:.5625rem;line-height:.375rem}.badge.is-badge-small[data-badge=""]::after{width:.75rem}.badge.is-badge-small.is-badge-left::after{left:calc(0px - (.75rem / 2))}.badge.is-badge-small.is-badge-bottom::after{top:calc(100% - (.75rem / 2))}.badge.is-badge-small.is-badge-bottom-left::after{left:calc(0px - (.75rem / 2));top:calc(100% - (.75rem / 2))}.badge.is-badge-medium[data-badge]::after{top:calc(0px - (1.25rem / 2));left:calc(100% - (1.25rem / 2));min-height:1.25rem;min-width:1.25rem}.badge.is-badge-medium:not([data-badge=""])::after{font-size:.9375rem;line-height:.625rem}.badge.is-badge-medium[data-badge=""]::after{width:1.25rem}.badge.is-badge-medium.is-badge-left::after{left:calc(0px - (1.25rem / 2))}.badge.is-badge-medium.is-badge-bottom::after{top:calc(100% - (1.25rem / 2))}.badge.is-badge-medium.is-badge-bottom-left::after{left:calc(0px - (1.25rem / 2));top:calc(100% - (1.25rem / 2))}.badge.is-badge-large[data-badge]::after{top:calc(0px - (1.5rem / 2));left:calc(100% - (1.5rem / 2));min-height:1.5rem;min-width:1.5rem}.badge.is-badge-large:not([data-badge=""])::after{font-size:1.125rem;line-height:.75rem}.badge.is-badge-large[data-badge=""]::after{width:1.5rem}.badge.is-badge-large.is-badge-left::after{left:calc(0px - (1.5rem / 2))}.badge.is-badge-large.is-badge-bottom::after{top:calc(100% - (1.5rem / 2))}.badge.is-badge-large.is-badge-bottom-left::after{left:calc(0px - (1.5rem / 2));top:calc(100% - (1.5rem / 2))}

</style>
