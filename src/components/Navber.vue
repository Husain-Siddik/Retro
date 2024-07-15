<script setup>

import 'primeicons/primeicons.css'

</script>

<template>

    <div class="navbar bg-base-100">
        <div class="navbar-start">
            <div class="dropdown">
                <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h8m-8 6h16" />
                    </svg>
                </div>
                <ul tabindex="0"
                    class="menu menu-sm dropdown-content bg-base-100 rounded-box z-[1] mt-3 w-52 p-2 shadow">

                    <li><a>Home</a></li>
                    <li><a>Edit</a></li>
                    <li><a>Add User</a></li>
                    <li><a>About</a></li>
                </ul>
            </div>
            <a class="btn btn-ghost text-xl lg:text-4xl ">ReTro</a>
        </div>
        <div class=" w-1/2 place-content-center  hidden lg:flex">
            <ul class="menu menu-horizontal px-1">
                <button class="btn p-4  ml-4"><i class="pi pi-home" style="font-size: 1.5rem"></i></button>
                <button class="btn p-4  ml-4"><i class="pi pi-pencil" style="font-size: 1.5rem"></i></button>
                <button class="btn p-4  ml-4"><i class="pi pi-user-plus" style="font-size: 1.5rem"></i></button>


            </ul>
        </div>
        <div class="navbar-end">
            <a class="btn btn-accent">Log In </a>
        </div>
    </div>
</template>
