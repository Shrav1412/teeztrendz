<template>
    <div>
        <div class="h-[100px] flex items-center px-10 shadow-md">
            <NuxtLink to="/"><img class="w-48" src="../assets/LOGO.jpg" alt="logo" /></NuxtLink>
        </div>
        <div class="mt-20">
            <h1 class="text-center font-bold text-3xl">ANIME</h1>
        </div>
        <div class="my-20 grid grid-cols-3 place-items-center gap-y-40">
            <div>
                <NuxtLink to="/product">
                <div
                    class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg1 flex justify-center items-center">
                </div>
                <div class="mt-5">
                    <h1 class="text-xs">TEEZ TRENDZ</h1>
                    <h1 class="text-lg font-semibold">Naruto Printed Cotton T-Shirt</h1>
                    <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub class="text-green-500"> (30% OFF)</sub></h1>
                </div></NuxtLink>
            </div>
            <div>
                <NuxtLink to="/product">
                <div
                    class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg2 flex justify-center items-center">
                </div>
                <div class="mt-5">
                    <h1 class="text-xs">TEEZ TRENDZ</h1>
                    <h1 class="text-lg font-semibold">Kakashi Printed Cotton T-Shirt</h1>
                    <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub class="text-green-500"> (30% OFF)</sub></h1>
                </div></NuxtLink>
            </div>
            <div>
                <NuxtLink to="/product">
                <div
                    class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg3 flex justify-center items-center">
                </div>
                <div class="mt-5">
                    <h1 class="text-xs">TEEZ TRENDZ</h1>
                    <h1 class="text-lg font-semibold">Naruto Printed Cotton T-Shirt</h1>
                    <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub class="text-green-500"> (30% OFF)</sub></h1>
                </div></NuxtLink>
            </div>
            <div>
                <NuxtLink to="/product">
                <div
                    class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg4 flex justify-center items-center">
                </div>
                <div class="mt-5">
                    <h1 class="text-xs">TEEZ TRENDZ</h1>
                    <h1 class="text-lg font-semibold">Itachi Printed Cotton T-Shirt</h1>
                    <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub class="text-green-500"> (30% OFF)</sub></h1>
                </div></NuxtLink>
            </div>
            <div>
                <NuxtLink to="/product">
                <div
                    class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg5 flex justify-center items-center">
                </div>
                <div class="mt-5">
                    <h1 class="text-xs">TEEZ TRENDZ</h1>
                    <h1 class="text-lg font-semibold">Naruto Printed Cotton T-Shirt</h1>
                    <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub class="text-green-500"> (30% OFF)</sub></h1>
                </div></NuxtLink>
            </div>
            <div>
                <NuxtLink to="/product">
                <div
                    class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg6 flex justify-center items-center">
                </div>
                <div class="mt-5">
                    <h1 class="text-xs">TEEZ TRENDZ</h1>
                    <h1 class="text-lg font-semibold">Eren Printed Cotton T-Shirt</h1>
                    <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub class="text-green-500"> (30% OFF)</sub></h1>
                </div></NuxtLink>
            </div>
        </div>
    </div>
</template>


<style scoped>
.bg1 {
    background-image: url('../assets/0010.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.bg2 {
    background-image: url('../assets/0011.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.bg3 {
    background-image: url('../assets/0010.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.bg4 {
    background-image: url('../assets/0013.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.bg5 {
    background-image: url('../assets/0014.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

.bg6 {
    background-image: url('../assets/T009.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}

/* .shad {
    box-shadow: 0px 5px 10px 10px rgb(0 0 0 / 0.1), 0px 5px 5px 5px rgb(0 0 0 / 0.1);
} */
</style>