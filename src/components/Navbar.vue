<template>
   <div class="md:flex md:flex-col">
          <div class="md:flex md:flex-col md:h-screen">

            <!-- HEADER -->
            <div class="md:flex md:flex-shrink-0">
              <div class="flex items-center justify-between px-6 py-4 bg-red-800 text-white md:flex-shrink-0 md:justify-center md:w-56">
                <img src="../assets/images/2-removebg-preview.png" class="w-40">
              </div>
              <div class="md:text-md flex items-center justify-between p-3 w-full text-sm bg-white border-b md:px-12 md:py-0">
                
                <div class="mr-4 mt-1">Usuario</div>
                <div >
                  <svg class="text-white bg-red-700 rounded-md hover:bg-red-600 md:hidden block w-7 mr-" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"></path>
                </svg>
                <!--<button class="md:hidden block bg-indigo-400 p-1 border-b-2 border-r-2 rounded-md hover:bg-indigo-200 hover:border-blue-700 border-blue-950">Menú</button>
                -->
              </div>
              </div>
            </div>
             <!-- BODY -->
             <div class="md:flex md:flex-grow md:overflow-hidden">
              <div class="hidden flex-shrink-0 p-12 w-56 bg-red-700 text-white overflow-y-auto md:block">
                <div class=" flex  p-2 w-96 bg-white text-red-700">
                  <svg class=" w-5" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 21h16.5M4.5 3h15M5.25 3v18m13.5-18v18M9 6.75h1.5m-1.5 3h1.5m-1.5 3h1.5m3-6H15m-1.5 3H15m-1.5 3H15M9 21v-3.375c0-.621.504-1.125 1.125-1.125h3.75c.621 0 1.125.504 1.125 1.125V21"></path>
                  </svg>
                  <a href="admin.html">
                    Hoteles
                  </a> 
                </div>
                <div class=" flex p-2 w-96  hover:bg-red-600 hover:border-l hover:border-l-white">
                  <svg class="w-5" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M21.752 15.002A9.718 9.718 0 0118 15.75c-5.385 0-9.75-4.365-9.75-9.75 0-1.33.266-2.597.748-3.752A9.753 9.753 0 003 11.25C3 16.635 7.365 21 12.75 21a9.753 9.753 0 009.002-5.998z"></path>
                  </svg>
                  <a href="grafico.html">
                  Graficos
                </a> 
                </div>
               
              </div>
         
              
                <div class="text-2xl px-4 py-8 md:flex-1 md:p-12 md:overflow-y-auto">
                    <div class="mb-5"> Registro de Hoteles </div>
                    <div class=" bg-white p-8 rounded shadow-2xl ">

                  
                      <form action="admin.html">
                        <div class="grid md:grid-cols-2 md:gap-6">
                          <div class="relative z-0 w-full mb-6 group">
                              <input type="text" name="Ciudad" id="Ciudad" class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
                              <label for="floating_first_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Ciudad</label>
                              <p class="mt-2 text-sm text-red-600 dark:text-red-500"><span class="font-medium"></span> Campo obligatorio</p>
                            </div>
                          <div class="relative z-0 w-full mb-6 group">
                              <input type="text" name="NombreHotel" id="NombreHotel" class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
                              <label for="floating_last_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Nombre Hotel</label>
                              <p class="mt-2 text-sm text-red-600 dark:text-red-500"><span class="font-medium"></span> Campo obligatorio</p>
                            </div>
                        </div>
                        <div class="grid md:grid-cols-2 md:gap-6">
                          <div class="relative z-0 w-full mb-6 group">
                              <input type="text" name="NIT" id="NIT" class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
                              <label for="floating_first_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">NIT</label>
                              <p class="mt-2 text-sm text-red-600 dark:text-red-500"><span class="font-medium"></span> Campo obligatorio</p>
                            </div>
                          <div class="relative z-0 w-full mb-6 group">
                              <input type="text" name="Direccion" id="Direccion" class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
                              <label for="floating_last_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Direccion</label>
                              <p class="mt-2 text-sm text-red-600 dark:text-red-500"><span class="font-medium"></span> Campo obligatorio</p>
                            </div>
                        </div>
                        <div class="grid md:grid-cols-2 md:gap-6">
                          <div class="relative z-0 w-full mb-6 group">
                              <input type="number" name="nhabitacion" id="nhabitacion" class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer" placeholder=" " required />
                              <label for="floating_first_name" class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">N Habitaciones</label>
                              <p class="mt-2 text-sm text-red-600 dark:text-red-500"><span class="font-medium"></span> Campo obligatorio</p>
                            </div>
                          
                        </div>
                        <div class="flex items-center mt-4">
                          <button type="submit" class=" text-white text-xl  bg-red-700 p-2 rounded-lg hover:bg-white hover:text-red-500 hover:border hover:border-red-500">Enviar</button>
                        </div>
                        <br>
                    <div class="p-4 mb-4 text-sm text-red-800 rounded-lg bg-red-50 dark:bg-gray-800 dark:text-red-400" role="alert">
                      <span class="font-medium">Estas presentando error al guardar los cambios! </span>  Por favor intenta de nuevo
                    </div>
                    <div class="p-4 mb-4 text-sm text-green-800 rounded-lg bg-green-50 dark:bg-gray-800 dark:text-green-400" role="alert">
                      <span class="font-medium">Registro Guardado con exito!</span>
                    </div>
                    
                      </form>
                    </div>
                  
                    
                 
                  </div>
  
                  
        </div>

          </div>
        </div>
    


  </template>