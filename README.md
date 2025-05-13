# ceng391-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [CENG391 Homework 3 Solved](https://www.ankitcodinghub.com/product/ceng391-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92746&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CENG391 Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Exercise 1 Gaussian Image Pyramid

Write a new class ImagePyr in a file named as image pyr.cc that represents a Gaussian Pyramid with the following properties:

<ol>
<li>It should have the following private fields:

• an integer m n levels storing number of pyramid levels (octaves).

• an Image pointer m levels storing pyramid levels in an array of Images.
</li>
<li>The constructor must take the desired number of levels, a pointer to the base image to create the pyramid levels for and the initial sigma, sigma0, for the base image.</li>
<li>The destructor must deallocate all memory allocated by the construc- tor.</li>
<li>A getter for the number of levels.</li>
<li>A getter for the ith level image.</li>
<li>Level 0 is a copy of the base image given in the constructor (do not just copy the pointer, create a new image that is a copy of the base image).</li>
<li>Level i is created by first Gaussian smoothing the image at level i − 1 so that its scale (sigma value) is doubled. And then it is downsampled by two in x and y dimensions so that its width and height are the half of the width and height of the image at level i − 1 (Downsample by throwing out every other row and column of the smoothed image).
1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Exercise 2 Gaussian Image Pyramid Tester

Write the code for a new executable image-pyr-test in a file named as image pyr test.cc that reads an image from a file given as the first com- mand line argument and creates an image pyramid with number of levels equal to the number given as the second command line argument. It should than save each pyramid level in files named as “/tmp/pyr level i.png” where i is the level number. The test program should display a usage mes- sage if there is a missing argument or it is given an argument with an invalid value. Modify CMakeLists.txt so that this test executable is compiled along with the existing executables in the project.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
