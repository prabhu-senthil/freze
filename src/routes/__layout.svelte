<script>
  import "../app.css";
</script>
<div class="bg-black flex px-4 py-2 ">
<img class="h-10 ml-4" src="/static/freeze.png" />
<h1 class="text-white ml-6 mt-2 uppercase tracking-widest text-xl font-bold  ">Freeze</h1>
<div class="container flex mx-auto ml-64">
    <div class="flex border-2 rounded">
        <button class="flex items-center justify-center bg-white px-4 border-r">
            <svg class="w-6 h-6 text-black " fill="currentColor" xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24">
                <path
                    d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z">
                </path>
            </svg>
        </button>
        <input type="text" class=" w-96 px-4 py-2 " placeholder="Search...">
    </div>
</div>
<button class="py-4 px-1 relative border-2 border-transparent text-gray-800 rounded-full hover:text-gray-400 focus:outline-none focus:text-gray-500 transition duration-150 ease-in-out" aria-label="bell">
    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mb-4 mr-16 text-white origin-top-right absolute right-4" viewBox="0 0 20 20" fill="currentColor">
        <path d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z" />
      </svg>
    <span class="absolute inset-0 object-right-top -mr-6">
      <div class="inline-flex items-center px-1.5 py-0.5 border-2 origin-top-right absolute right-24 border-white rounded-full text-xs font-semibold leading-4 bg-indigo-500 text-white">
        6
      </div>
    </span>
  </button>
  <div class="relative group">
    <div class="flex items-center cursor-pointer text-sm text-blue  group-hover:border-grey-light rounded-t-lg ">
  
  <img class="h-10  rounded-full mt-1 border-2 mr-8  border-gray-200" src="/static/user.jfif" alt="user" />
  <h2 class="text-white text-xl mt-2 mr-9">Yogeshwaran</h2>
  <div class="items-center absolute  p-1 bg-white p-2 mt-48 invisible group-hover:visible w-full">
    <a href="/view" class="px-4 py-2 block rounded-lg text-black  hover:bg-indigo-300  hover:font-extrabold">View Profile</a>
    <a href="/account_setting" class="px-4 py-2 block rounded-lg text-black  hover:bg-indigo-300 hover:font-extrabold">Account Settings</a>
    
    <a href="/login" class="px-4 py-2 block rounded-lg text-black  hover:bg-indigo-300 hover:font-extrabold">Logout</a>
   </div>
 </div>
 
</div>
</div>



<div class="flex">
  <aside class="w-60  ">
  <div class="overflow-y-auto h-full py-4 px-3 border-r border-gray-300  ">
     <ul class="text-xl" >
        <li>
           <a href="#" class="flex  p-2  text-gray-500 hover:text-gray-900  rounded-lg hover:bg-indigo-100 ">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                 <path d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z" />
               </svg>
              <span class="ml-3">Home</span>
           </a>
        </li>
        <li>
           <a href="#" class="flex  p-2  text-gray-500 hover:text-gray-900 rounded-lg  hover:bg-indigo-100 ">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                 <path fill-rule="evenodd" d="M6 2a2 2 0 00-2 2v12a2 2 0 002 2h8a2 2 0 002-2V7.414A2 2 0 0015.414 6L12 2.586A2 2 0 0010.586 2H6zm2 10a1 1 0 10-2 0v3a1 1 0 102 0v-3zm2-3a1 1 0 011 1v5a1 1 0 11-2 0v-5a1 1 0 011-1zm4-1a1 1 0 10-2 0v7a1 1 0 102 0V8z" clip-rule="evenodd" />
               </svg>
              <span class=" ml-3 ">Dashboard</span>
           </a>
        </li>
        <li>
           <a href="#" class="flex  p-2  text-gray-500 hover:text-gray-900 rounded-lg  hover:bg-indigo-100 ">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                 <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd" />
               </svg>
              <span class=" ml-3">About</span>
           </a>
        </li>
        <li>
           <a href="#" class="flex  p-2   text-gray-500 hover:text-gray-900 rounded-lg  hover:bg-indigo-100 ">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                 <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z" />
               </svg>
              <span class=" ml-3 ">Contact</span>
           </a>
        </li>
     
     </ul>
  </div>
</aside>


<slot />
</div>
