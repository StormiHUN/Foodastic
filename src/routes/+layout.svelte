<style>
    @import "tailwindcss";
</style>
<div class="flex flex-col min-w-full overflow-hidden min-h-full">
    <div class="w-2/10 bg-[#F5ECD5] w-full flex justify-center group">
        <div class="mr-auto">
            <a href="/" class="flex">
                <img class="m-2 w-[64px] h-[64px] border-2 rounded-full bg-[#01805e]" src="logo.png" alt="logo">
                <p class="text-xl mt-[15%]">Foodastic</p>
            </a>
        </div>
        <a class="p-6 text-xl hover:bg-[#edd391] border-b-2 border-[#F5ECD5] hover:border-[#debe6d] transition-all" href="/">
            Home
        </a>
        <a class="p-6 text-xl hover:bg-[#edd391] border-b-2 border-[#F5ECD5] hover:border-[#debe6d] transition-all" href="/menu">
            Menu
        </a>
        <a class="p-6 text-xl hover:bg-[#edd391] border-b-2 border-[#F5ECD5] hover:border-[#debe6d] transition-all" href="/login">
            Login
        </a>
    </div>
    <slot/>
    <div class="w-full bg-[#a34303] p-4 text-[#f27827] flex justify-center h-fit mt-auto">
        MakeHealthy by Kandó
    </div>
</div>
