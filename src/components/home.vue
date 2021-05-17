<template>
<div class="flex flex-col items-center">
<div class="flex flex-col container mx-auto shadow-2xl w-full bg-gradient-to-b from-green-500 to-blue-500 items-center p-5" id="home">
        
<img class="h-40 w-40 rounded-full object-cover border-double border-white border-8  bg-green-500" src="https://scontent.fdac11-1.fna.fbcdn.net/v/t1.6435-9/131243672_1314493388925746_197719383945329023_n.jpg?_nc_cat=108&ccb=1-3&_nc_sid=09cbfe&_nc_eui2=AeH1OwJ60W3eEG9ZIWv-Dj2wC9FA0CyYD90L0UDQLJgP3T41FyRy-OAF0Fo9pmjxzqutzOVFhVWjJMLdTQuyKUuo&_nc_ohc=cuwqOnnafQQAX99dqIJ&_nc_ht=scontent.fdac11-1.fna&oh=ae526263889aabe0f29efbb15836c175&oe=60C83030"/>
        <h1 class="text-2xl text-white hover:text-red-500">Tahmid</h1>
        <p class="text-white p-2">Amar name tahmid islam</p>
        <div class="grid grid-cols-2 divide-x divide-white">
            <div class="p-2 text-l text-white">
                <a href="https://www.facebook.com/tahmid.rifat73" target="_blank">Facebook</a>
            </div>
            <div class="p-2 px-2">
                <a class="text-l text-white" href="https://www.instagram.com/tahmidrifat/" target="_blank">Instagram</a>
            </div>
        </div>
    </div>
    </div>
</template>

methods:{
    facebook(){
        window.location.href("https://www.instagram.com/tahmidrifat/")
    }
}