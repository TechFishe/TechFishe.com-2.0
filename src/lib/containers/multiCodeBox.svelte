<!-- <script lang="ts">
    function copy(){
        navigator.clipboard.writeText(text);
        alert("Copied text: " + text);
    }

    export let text:string = "no text :(";
</script> -->

<div class="items-center flex space-x-2">
    <div class="bg-gray-900 dark:bg-gray-300 pb-1 max-w-max pl-3 pr-6 rounded-md flex-col shadow-sm tracking-wider">
        <slot />
    </div>
    <!-- <button class="flex p-1.5 rounded-full mr-4 hover:scale-110 hover:text-fuchsia-500 hover:bg-gray-700 dark:hover:bg-gray-300 shadow-sm hover:shadow-md dark:shadow-gray-600 transition ease-in-out" on:click={copy}>
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 7.5V6.108c0-1.135.845-2.098 1.976-2.192.373-.03.748-.057 1.123-.08M15.75 18H18a2.25 2.25 0 002.25-2.25V6.108c0-1.135-.845-2.098-1.976-2.192a48.424 48.424 0 00-1.123-.08M15.75 18.75v-1.875a3.375 3.375 0 00-3.375-3.375h-1.5a1.125 1.125 0 01-1.125-1.125v-1.5A3.375 3.375 0 006.375 7.5H5.25m11.9-3.664A2.251 2.251 0 0015 2.25h-1.5a2.251 2.251 0 00-2.15 1.586m5.8 0c.065.21.1.433.1.664v.75h-6V4.5c0-.231.035-.454.1-.664M6.75 7.5H4.875c-.621 0-1.125.504-1.125 1.125v12c0 .621.504 1.125 1.125 1.125h9.75c.621 0 1.125-.504 1.125-1.125V16.5a9 9 0 00-9-9z" />
          </svg>
    </button> -->
</div>