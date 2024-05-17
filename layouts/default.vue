
import { RightSidebar } from '#build/components';

import { LeftSidebar } from '#build/components';
<template>
    <NavBar class="fixed w-full top-0 left-0 z-50 "/>
    
    <div class="flex flex-row p-5  mx-auto max-w-[1720px] pt-[4rem]">
        <div class="w-[25%] pt-5 hidden lg:block mt-4 ">
            <LeftSidebar />
        </div>
        
        <slot />
        <div class="w-[40%] pt-5 hidden md:flex gap-3 md:flex-col">
            <RightSidebar />
        </div>
    </div>
    <FooterSection />
</template>