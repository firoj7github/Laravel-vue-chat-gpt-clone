<template>
<div class="w-full ">
      <div class="grid lg:grid-cols-2 gap-2">
        <div class="w-56 h-screen bg-black"></div>
               <div class="ove">
                <div class="">
                    <h1 class="text-center mb-8 mt-8 text-bold text-2xl text-orange-500">Laravel ChatGPT</h1>
                </div>
                <div class="grid grid-cols-3 ml-2">
                    <div>
                        <h2 class="ml-32 mb-4">Examples</h2>
                        <p class="w-80 rounded pt-4 text-center h-16 bg-gray-100 mb-4">Got any creative idea</p>
                        <p class="w-80 rounded pt-4 text-center h-16 bg-gray-100">Explain simple task</p>
                    </div>
                    <div>
                        <h2 class="ml-32 mb-4">Capabilities</h2>
                       
                        <p class="w-80 rounded pt-4 text-center h-16 bg-gray-100 mb-4">Got any creative idea</p>
                        <p class="w-80 rounded pt-4 text-center h-16 bg-gray-100">Explain simple task</p>
                    </div>
                    <div>
                        <h2 class="ml-32 mb-4">Limitations</h2>
                       
                        <p class="w-80 rounded pt-4 text-center h-16 bg-gray-100 mb-4">Got any creative idea</p>
                        <p class="w-80 rounded pt-4 text-center h-16 bg-gray-100">Explain simple task</p>
                    </div>
                    <div>
    <form class="p-4 from-input" action="/" method="post">
    @csrf
    <label for="message">Laravel Question:</label>
    <input id="message" type="text" name="message" autocomplete="off" class="border rounded-md  p-2 flex-1" />
    <a class="bg-gray-800 text-white p-2 w-32 rounded-md" href="/reset">Reset Conversation</a>
</form>
                    </div>

                    

                </div>
            </div>
            
      </div>
           
        </div>

        
</template>
<style>
.ove{
    width: 1000px;
    height: auto;
    margin-left: -450px;
}
.from-input{
    width: 1000px;
}
</style>