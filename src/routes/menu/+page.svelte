<script>

    let t = [
        {
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        },{
            id : "sk",
            image : "https://tinyurl.com/mpvces9x",
            name : "sajtoskifli"
        }
    ]

        async function kepSwitch(item, id){
            console.log(id)
            if(document.getElementById(id).children.length > 1){
                document.getElementById(id).innerHTML = '<img class="rounded-lg min-w-[240px] max-w-[240px] min-h-[360px] max-h-[3600px] mx-auto"  src='+item.image+' alt="placeholder">'
                return
            }
            document.getElementById(id).innerHTML = "<p>lófasz</p><p></p>"
        }

</script>
<main>
    <div class="grid grid-cols-7 p-4 gap-4">
        {#each t as item, index}
            <div class="flex flex-col gap-2 bg-[#F5ECD5] border-[#3D3D3D] border-2 p-2 w-fit rounded-lg hover:bg-[#d9ccab] transition-all">
                <div id={"item"+index} on:click={() => kepSwitch(item, "item"+index)} class="min-w-[240px] max-w-[240px] min-h-[360px] max-h-[3600px] mx-auto transition-all">
                    <img class="rounded-lg min-w-[240px] max-w-[240px] min-h-[360px] max-h-[3600px] mx-auto"  src={item.image} alt="placeholder">
                </div>
                <div class="flex justify-between">
                    <p class="">{item.name}</p>
                    <button class="hover:bg-[#F6ECD6] hover:rounded-lg p-2 transition-all">
                        <img src="/addshoppingcart.svg" alt="cart">
                    </button>
                </div>
            </div>
        {/each}
    </div>
</main>