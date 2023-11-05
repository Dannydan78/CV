<script setup>

const data = {
    tel: '06.26.37.09.15',
    mail: 'danny.darragon.konki@gmail.com',
    github: 'http://github.com/Dannydan78',

}

</script>

<template>
    <div class="flex m-5">
        <div class="flex-1 mt-5">
            <h2 class="text-4xl font-extrabold dark:text-white">DARRAGON-KONKI</h2>
            <h2 class="text-4xl dark:text-white">Danny</h2>
            <p class="my-4 text-lg text-gray-700">Développeur Web junior</p>
        </div>

        <div class="flex-1">
            <div class="mt-7 text-blue-500">
                <a href="tel:0626370915">
                <ion-icon name="call"></ion-icon> {{ data.tel }}
                </a>
            </div>
            <div class="mt-5 text-blue-500"> 
                <a href="mailto:danny.darragon.konki@gmail.com">
                <ion-icon name="mail"></ion-icon> {{ data.mail }}
                </a>    
            </div>
            <div class="mt-5  text-blue-500">
                <a href="http://github.com/Dannydan78">
                <ion-icon name="logo-github"></ion-icon> {{ data.github }}
                </a>
            </div>
           
            





        </div>
    </div>
    <div class=" border border-gray-500 mt-10"></div>
</template>
  



  