<template>
    <NavBar class="fixed w-full top-0 left-0 z-50 "/>
    
    <div class="flex flex-row p-5  mx-auto max-w-[1720px] pt-[4rem]">
        <div class="w-[30%] pt-5 hidden lg:block mt-4 ">
            <LeftSidebar />
        </div>
        
        <slot />
       
    </div>
    <FooterSection />
</template>