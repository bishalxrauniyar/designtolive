Design to HTML CODE

<!--Gallery section-->

<div class="flex items-center justify-center md:h-screen h-[500px] w-screen md:py-24 py-10 md:px-24">
    <div class="flex flex-row items-stretch justify-center md:space-x-6 space-x-2 w-full h-full">
        <!-- First Image Column -->
        <div class="flex items-stretch w-1/2 h-full">
            <img src="images/img1.png" alt="Image 1" class="w-full h-full object-cover">
        </div>

        <!-- Second Column with Nested Images -->
        <div class="flex flex-col items-center space-y-4 w-1/2 h-full">
            <div class="w-full h-1/2">
                <img src="images/img2.png" alt="Image 2" class="w-full h-full object-cover">
            </div>
            <div class="flex items-center justify-center md:space-x-6 space-x-2 w-full h-1/2">
                <div class="flex-1 h-full">
                    <img src="images/img3.png" alt="Image 3" class="w-full h-full object-cover">
                </div>
                <div class="flex-1 h-full">
                    <img src="images/img4.png" alt="Image 4" class="w-full h-full object-cover">
                </div>
            </div>
        </div>
    </div>

</div>

  <div class="bg-slate-100 md:h-screen h-auto w-full md:p-16 p-4 flex flex-wrap md:flex-nowrap items-center gap-2 md:gap-4 m-2 mt-0 mb-0 mr-2">
            <!-- Left Image -->
            <div class="w-full md:w-1/2 h-64 md:h-full">
                <img src="images/img1.jpg" class="w-full h-full object-cover" alt="Image 1" />
            </div>
            <!-- Right Content -->
            <div class="w-full md:w-1/2 flex flex-col md:gap-4 gap-2">
                <!-- Top Right Image -->
                <div class="w-full h-64 md:h-1/2">
                    <img src="images/img2.jpg" class="w-full h-full object-cover" alt="Image 2" />
                </div>
                <!-- Bottom Right Images -->
                <div class="flex w-full h-64 md:h-1/2 gap-2">
                    <div class="w-1/2 h-full">
                        <img src="images/img2.jpg" class="w-full h-full object-cover" alt="Image 3" />
                    </div>
                    <div class="w-1/2 h-full">
                        <img src="images/img1.jpg" class="w-full h-full object-cover" alt="Image 4" />
                    </div>
                </div>
            </div>
        </div>
