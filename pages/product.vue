<template>
    <div>
        <div class="h-[100px] flex items-center px-10 shadow-md">
            <NuxtLink to="/"><img class="w-48" src="../assets/LOGO.jpg" alt="logo" /></NuxtLink>
        </div>
        <div class="grid grid-cols-2 m-20 place-items-stretch">
            <div class=" justify-self-center">
                <div
                    class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg6 flex justify-center items-center">
                </div>
            </div>
            <div>
                <h1 class="text-xl font-semibold">TEEZ TRENDZ</h1><br>
                <h1 class="text-2xl font-semibold">EREN YEAGER Printed Cotton T-Shirt</h1><br>
                <h1 class="text-3xl font-semibold">Rs.499 <sub class="line-through">Rs.999</sub><sub
                        class="text-green-500"> (30% OFF)</sub></h1><br><br>
                <h1>COLOUR</h1><br>
                <div class="flex gap-5">
                    <div class="w-5 h-5 rounded-full bg-white border-2 border-[#f29d62]"></div>
                    <h1 class="font-medium">White</h1>
                </div>
                <br>
                <div class="flex gap-10 font-medium">
                    <h1>SELECT SIZE</h1>
                    <h1 class="flex">SIZE CHART <img class="mt-[-10px] w-10 h-10" src="../assets/SIZE CHART.jpg"
                            alt="size-chart"></h1>
                </div><br>
                <div class="flex gap-5">
                    <div
                        class="w-10 h-10 rounded-full border-2 border-black font-medium flex justify-center items-center">
                        M</div>
                    <div
                        class="w-10 h-10 rounded-full border-2 border-black font-medium flex justify-center items-center">
                        L</div>
                    <div
                        class="w-10 h-10 rounded-full border-2 border-black font-medium flex justify-center items-center">
                        XL</div>
                </div>
                <br><br>
                <button class="bg-[#fb4a4a] text-white w-[250px] h-[60px] rounded-xl font-semibold">ADD TO
                    BAG</button><br><br>
                <button class="bg-[#fb4a4a] text-white w-[250px] h-[60px] rounded-xl font-semibold">BUY
                    NOW</button><br><br><br>
                <div>
                    <h1 class="text-lg font-semibold">DELIVERY OPTIONS</h1><br>
                    <div class="">
                        <input class="border-2 border-black/50 w-[250px] h-[50px] rounded-xl pl-5"
                            placeholder="Enter Pincode" type="text">
                        <button class="ml-5 text-lg font-semibold ">Check</button>
                    </div>
                    <h1>Please enter PIN code to check availability.</h1>
                </div>
                <br><br>
                <div class="text-lg ">
                    <h1>100% Original Products</h1>
                    <h1>Pay on delivery might be available</h1>
                    <h1>Easy 14 days returns and exchanges</h1>
                </div>
                <br>
                <div class="text-lg">
                    <h1 class="text-xl font-semibold">PRODUCT DETAILS</h1>

                    <h1>White T-shirt for unisex</h1>
                    <h1>Graphic printed</h1>
                    <h1>Regular length</h1>
                    <h1>Round neck</h1>
                    <h1>Short, regular sleeves</h1>
                    <h1>Cotton fabric</h1>
                </div>
                <br>
                <div class="text-lg">
                    <h1 class="text-xl font-semibold">Size & Fit</h1>

                    <h1>Regular Fit</h1>
                    <h1>The model (hieght 6') is wearing a size 6XL</h1>
                </div>
                <br>
                <div class="text-lg">
                    <h1 class="text-xl font-semibold">Material & Care</h1>

                    <h1>Cotton</h1>
                    <h1>Machine wash</h1>
                    <h1>Cold and air dry only</h1>
                    <h1>Do not iron over print and wash inside out</h1>
                </div>
            </div>
        </div>
        <div>
            <h1 class="text-xl font-semibold ml-20">SIMILAR PRODUCTS</h1>
            <div class="my-20 grid grid-cols-3 place-items-center gap-y-40">
                <div>
                    <div
                        class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg6 flex justify-center items-center">
                    </div>
                    <div class="mt-5">
                        <h1 class="text-xs">TEEZ TRENDZ</h1>
                        <h1 class="text-lg font-semibold">Naruto Printed Cotton T-Shirt</h1>
                        <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub
                                class="text-green-500"> (30% OFF)</sub></h1>
                    </div>
                </div>
                <div>
                    <div
                        class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg6 flex justify-center items-center">
                    </div>
                    <div class="mt-5">
                        <h1 class="text-xs">TEEZ TRENDZ</h1>
                        <h1 class="text-lg font-semibold">Kakashi Printed Cotton T-Shirt</h1>
                        <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub
                                class="text-green-500"> (30% OFF)</sub></h1>
                    </div>
                </div>
                <div>
                    <div
                        class="duration-300 hover:scale-105 rounded-3xl w-[400px] h-[500px] bg6 flex justify-center items-center">
                    </div>
                    <div class="mt-5">
                        <h1 class="text-xs">TEEZ TRENDZ</h1>
                        <h1 class="text-lg font-semibold">Naruto Printed Cotton T-Shirt</h1>
                        <h1 class=" text-base font-medium">Rs.499 <sub class="line-through">Rs.999</sub><sub
                                class="text-green-500"> (30% OFF)</sub></h1>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.bg6 {
    background-image: url('../assets/anime/black/B4.jpg');
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
}
</style>