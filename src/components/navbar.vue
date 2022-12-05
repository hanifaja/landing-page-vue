<template>
    <div class="p-10 max-w-full m-auto">
        <nav class="flex flex-row justify-between items-center">
            <div class="text-xl font-semibold pt-2">
                <img src="../assets/d1r.png" alt="">
            </div>
            <ul class="list-none flex flex-row justify-between space-x-3 items-center mx-2 col-span-4 col-start-5 text-black overflow-hidden shadow-lg px-5 py-2.5 backdrop-blur-xl hover:-translate-y-2 hover:shadow transition-all duration-300">
                <li class="pb-3 cursor-pointer border-b hover:border-pink-400">Home</li>
                <li class="pb-3 cursor-pointer border-b hover:border-pink-400">Blog</li>
                <li class="pb-3 cursor-pointer border-b hover:border-pink-400">Store</li>
                <li class="pb-3 cursor-pointer border-b hover:border-pink-400">About</li>
                <li class="pb-3 cursor-pointer border-b hover:border-pink-400">Contac</li>
            </ul>
            <div class="flex flex-row justify-between gap-10">
                <div class="backdrop-blur-xl hover:-translate-y-2 hover:shadow-2xl transition-all duration-300">
                    <div class="relative bg-green-600 rounded-lg overflow-hidden text-white justify-between px-5 py-2.5 group">
                        <button class="absolute w-64 h-64 mt-12 group-hover:-rotate-45 group-hover:-mt-24 transition-all ease-linear duration-500 bg-pink-600 left-0 top-0">
                            <button class="relative">Sing In</button>
                        </button>
                    </div>
                </div>
                <div class="backdrop-blur-xl hover:-translate-y-2 hover:shadow-2xl transition-all duration-300">
                    <div class="relative bg-green-600 rounded-lg overflow-hidden text-white justify-between px-5 py-2.5 group">
                        <button class="absolute w-64 h-64 mt-12 group-hover:-rotate-45 group-hover:-mt-24 transition-all ease-linear duration-500 bg-pink-600 left-0 top-0">
                            <button class="relative">Sing Out</button>
                        </button>
                    </div>
                </div>
            </div>
        </nav>
        </div>
</template>


