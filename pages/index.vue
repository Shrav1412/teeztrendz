<template>
    <div>
        <div class="h-[100px] flex items-center px-10 shadow-md">
            <NuxtLink to="/"><img class="w-48" src="../assets/LOGO.jpg" alt="logo" /></NuxtLink>
        </div>
        <div class="mt-20 flex flex-col justify-center items-center">
            <img class="w-[1400px] rounded-3xl drop-shadow-md" src="../assets/BANNER.jpg" alt="banner">
            <br><br>
            <div class="flex justify-center items-center gap-5">
                <div class="bg-black/50 w-[40px] h-[8px] rounded-3xl"></div>
                <div class="bg-black/50 w-[40px] h-[8px] rounded-3xl"></div>
                <div class="bg-black/50 w-[40px] h-[8px] rounded-3xl"></div>
            </div>
        </div>
        <div class="h-screen mb-20 pt-20">
            <h1 class="text-center font-bold text-3xl">CATEGORIES</h1>
            <div class="mt-28 flex justify-evenly items-center">
                <NuxtLink to="/anime">
                    <div
                        class="duration-300 hover:scale-110 rounded-3xl w-[400px] h-[500px] bg1 flex justify-center items-center">
                        <h1 class="bg-[#f29d62] w-full text-center drop-shadow-md py-4 px-10 font-bold text-3xl">ANIME
                        </h1>
                    </div>
                </NuxtLink>
                <NuxtLink to="/casual">
                    <div
                        class="duration-300 hover:scale-110 rounded-3xl w-[400px] h-[500px] bg2 flex justify-center items-center">
                        <h1 class="bg-[#f9e09f] w-full text-center drop-shadow-md py-4 px-10 font-bold text-3xl">CASUAL
                        </h1>
                    </div>
                </NuxtLink>
                <NuxtLink to="/couple"><div
                    class="duration-300 hover:scale-110 rounded-3xl w-[400px] h-[500px] bg3 flex justify-center items-center">
                    <h1 class="bg-[#fd9f9f] w-full text-center drop-shadow-md py-4 px-10 font-bold text-3xl">COUPLE</h1>
                </div></NuxtLink>
            </div>
        </div>
        <div class="h-[100px] shad">
        </div>
    </div>
</template>

<style scoped>
.bg1 {
    background-image: url('../assets/BOX01.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.bg2 {
    background-image: url('../assets/BOX02.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.bg3 {
    background-image: url('../assets/BOX03.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.shad {
    box-shadow: 0px 5px 10px 10px rgb(0 0 0 / 0.1), 0px 5px 5px 5px rgb(0 0 0 / 0.1);
}
</style>