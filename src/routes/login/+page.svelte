<script>
    async function login() {
        
    }
</script>
<main class="flex justify-center my-4">
    <div class="w-fit h-fit border-2 rounded-lg p-4 flex flex-col gap-16 bg-[#F5ECD5]">
        <div class="flex flex-col justify-center">
            <img class="border-2 rounded-full bg-[#01805e]" src="logo.png" alt="logo">
            <p class="text-xl">Foodastic</p>
        </div>
        <div class="flex flex-col gap-4">
            <input class="border-2 rounded-lg p-4 bg-white hover:border-[#8c4a1d] transition-all" placeholder="Email" type="text">
            <input class="border-2 rounded-lg p-4 bg-white hover:border-[#8c4a1d] transition-all" placeholder="Password" type="password">
        </div>
        <div class="w-full">
            <button class="w-full border-2 rounded-lg bg-white p-4 hover:rounded-xl hover:border-[#8c4a1d] transition-all cursor-pointer" on:click={() => login()}>Login</button>
            <p class="text-sm">Don't have an account? You can register one <a class="hover:text-blue-500 hover:underline transition-all" href="/register">Here</a>!</p>
        </div>
    </div>
</main>