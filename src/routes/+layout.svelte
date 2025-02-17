<style>
    @import "tailwindcss";
</style>
<div class="flex flex-col min-w-full overflow-hidden">
    <div class="w-2/10 bg-[#F5ECD5] w-full flex justify-center group">
        <a class="p-6 text-xl hover:bg-[#edd391] border-b-2 border-[#F5ECD5] hover:border-[#debe6d] transition-all" href="/">
            Home
        </a>
        <a class="p-6 text-xl hover:bg-[#edd391] border-b-2 border-[#F5ECD5] hover:border-[#debe6d] transition-all" href="/menu">
            Menu
        </a>
        <a class="p-6 text-xl hover:bg-[#edd391] border-b-2 border-[#F5ECD5] hover:border-[#debe6d] transition-all" href="/order">
            Order
        </a>
    </div>
    <slot/>
    <div class="w-full bg-[#a34303] p-4 text-[#f27827] flex justify-center">
        MakeHealthy by Kandó
    </div>
</div>
