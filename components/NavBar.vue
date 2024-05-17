
import { LeftSidebar } from '#build/components';
<template>
    <div class="card mb-5">
        <Menubar >
            <template #start>
                <SideBar class="lg:hidden"/>                
            </template>
            <template #end>
                <div class="flex items-center gap-2">
                    <DarkMode />
                    <InputText placeholder="Search" type="text" class="w-[8rem] sm:w-auto" />
                    <Avatar image="https://primefaces.org/cdn/primevue/images/avatar/amyelsner.png" shape="circle" />
                </div>
            </template>
        </Menubar>
        
    </div>
</template>