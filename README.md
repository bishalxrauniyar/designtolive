basic page

 <!-- Testing area -->

<!-- Gallery Section -->
<div class="flex items-center justify-center py-10 md:py-24 px-6 md:px-24">
    <div class="flex flex-col md:flex-row w-full h-full">

        <!-- First Image Column (Image 1) -->
        <div class="flex items-stretch w-full md:w-1/2 h-[300px] md:h-full">
            <img src="images/img1.jpg" class="w-full h-full object-cover space-y-4">
        </div>

        <!-- Second Column with Nested Images (Image 2, Image 3, Image 4) -->
        <div class="flex flex-col w-full md:w-1/2 h-auto md:h-full space-y-4 md:space-y-0">

            <!-- Image 2 (top-right for medium screens) -->
            <div class="w-full h-[300px] md:h-1/2">
                <img src="images/img2.jpg" class="w-full h-full object-cover space-y-4">
            </div>

            <!-- Image 3 and Image 4 (bottom-right for medium screens) -->
            <div class="flex flex-row w-full h-[300px] md:h-1/2 space-x-4">
                <div class="w-1/2 h-full">
                    <img src="images/img3.jpg" class="w-full h-full object-cover">
                </div>
                <div class="w-1/2 h-full">
                    <img src="images/img3.jpg" class="w-full h-full object-cover">
                </div>
            </div>
        </div>
    </div>

</div>
