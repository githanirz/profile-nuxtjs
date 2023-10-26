<script>
export default {
    
}
</script>
<template>
    
    <div>
    <header class=" p-5 fixed bg-white backdrop-filter: blur(5px) top-0 left-0 w-full flex mb-4 z-10" >
        <div class="container">
            <div class=" mb-2 mt-8 flex text-sm font-light font-mono space-x-4  ">
                <div class="rounded-3xl mb-2 bg-gradient-to-r from-cyan-500 to-blue-500 px-4 " style="white-space: nowrap;">
                    <a href="/" class="font-bold text-lg text-white block py-3 ">
                        Githani Rizkyka
                    </a>
                </div>

                <nav class="  mb-2 py-2 px-4 mt-1
                space-x-4 flex bg-white rounded-lg  max-h-11 w-full">
                <nuxt-link class="font-bold font-serif text-base text-slate-700 py-2 px-4 flex hover:text-blue-500 ml-auto" to="/">Home</nuxt-link>
                 <nuxt-link class="text-base font-bold font-serif text-slate-700 py-2 px-4  flex hover:text-blue-500  " :to="{ name: 'about'}">Profile</nuxt-link>
                 <nuxt-link class=" text-base font-bold font-serif text-slate-700 py-2 px-4 flex hover:text-blue-500 ml-auto" :to="{ name: 'portofolio'}">Portofolio</nuxt-link>
                </nav>
            </div>
        </div>

    </header>

    </div>
 
</template>