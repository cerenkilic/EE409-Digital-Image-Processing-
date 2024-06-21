# EE409 Digital Image Processing Mini Projects
This repo includes the homeworks I have done for EE409 course. In this course, we covered many topics that are fundamental to digital image processing and practiced them with mini project assignments using MATLAB.

I have listed the questions in the assignments below:
### Plotting the values of a pixel row
Q: In this part, you
will plot the values of the pixels in a row you select in your
double grayscale image(use subplot). From the graph, try
to find in which pixel the brightness is the highest. Then
indicate the row you have plotted by making that row
white and display using imshow (use subplot).
### Finding the horizontal 1st order derivative
Q: Take the
horizontal first order derivative of your double grayscale
image(without white line). Then plot the same row (which
you selected in Q1) of your image derivative (use subplot).
What are the meanings of positive and negative derivative
values? Draw a white line on the same row of the image derivative as in question 1 and display
(use subplot).
### Finding the horizontal 2nd order derivative
Q: Take the
horizontal second order derivative of your double
grayscale image(without white line) and take its absolute
value. Then plot the same row of your image as in Q1 (use
subplot. Draw a white line on the same row of the
derivative image as in previous questions and display (use subplot).
### High-Boost Sharpening
Q: Sharpen your double grayscale image using “High-Boost”
sharpening method with just applying a single mask to your image. Display the sharpened image
(use subplot). Try to obtain a visually pleasant sharp image as much as you can.
### Unsharp Masking
Q: Sharpen your double grayscale image using “Unsharp Masking” method
with 3x3 weighted averaging filter. First apply the weighted averaging filter to your image and
display the result (use subplot). Then use it for “Unsharp Masking” sharpening of your image and
display the sharpened image (use subplot). Try to obtain a visually pleasant sharp image as much
as you can.
### Coding Dilation
Q: Write a Matlab script with a double for
loop to implement dilation morphological operation and dilate
your binary image with the 3x3 structural element “se1=[1 1 1; 1
1 1; 1 1 1]”. (Don’t use morphological operation functions in
Matlab such as imdilate();)
### Finding the edges
Q: Write a Matlab code that finds the edges of your name by using
morphological operations.
### Removing desired text according to its “size” by using morphological operations
Q: Use morphological operations to
clear your name with smallest (10+d) font size while preserving
the others. Then clear smallest(10+d) and medium(25+d) size
texts while preserving the largest(35+d) text. Note that after the
operations the texts on your images should be readable although
there might be some distortions. Try to merge broken letters.
Show the images obtained in every step (after each operation)
using subplot.
### Detecting the longest word
Q: Write a Matlab code that automatically detects the longest
horizontal word (that has largest width) in your name by using
morphological operations.
### Removing desired text according to its “orientation” by using morphological operations
Q: Delete the horizontal text while
preserving the vertical. Show the images obtained in every step
(after each operation) using subplot.
### Finding Histogram
Q: Write the Matlab command for finding the
histogram of your double grayscale image. You will obtain a figure as given
right as an example. Display and report your grayscale image together with
its histogram side by side in the same figure window and comment on
where most of the pixels are distributed heavily.
### Finding Normalized 3 bins Histogram
Q: This time find the histogram of
your double grayscale image using 3 bins and assign the histogram output
to a variable. Normalize the histogram result by dividing it to the total
number of pixels in the image. Plot the histogram of your image by using
the "bar()" command and report the graph together with your grayscale
image side by side in the same figure window. Write the percentages of
pixels in "dark gray", "medium gray" and "light gray" bins.
### Contrast Enhancement Using Piecewise Linear Transformation
Q: Now, you will apply piecewise linear transformation with 2 linear pieces
to enhance the double grayscale image. Try a few different parameters and
report the results. Determine and report the best parameters (a and ya) as
you can to enhance your image. Remember that L=1 for double grayscale
images. Display and report the obtained images and their histogram side by
side in the same figure window.

![image](https://github.com/cerenkilic/EE409-Digital-Image-Processing-/assets/74498810/aef15351-d938-4591-af55-568bbdf4aef0)

### Contrast Enhancement Using Gamma Transformation
Q: Try to enhance the contrast of the original double grayscale image using gamma
transformation. Determine and report the best parameters as you can to
enhance your image. Display and report the transformed image and its
histogram side by side in the same figure window.
### Histogram & Adaptive Histogram Equalization
Q: Enhance the contrast of the original double
grayscale image by using the histogram equalization method and adaptive histogram
equalization method. Display and report the resultant images together with previous low contrast
image side by side in the same figure window.
### Adding Uniform Random Noise to Image
Q: Write your own Matlab code to add random values(noise) between -0.2d and +0.2d (if the last digit of your ID
is 7, then -0.27 and +0.27) to every pixel of your images. Do not use “imnoise”
function. Repeat it by adding random values between -0.3d and +0.3d. Display
and report the resultant images side by side in the same figure window. Draw
the histograms of the original and the noisy yourName _gray images side by
side in another figure. Comment on the results briefly.
### Adding Gaussian Random Noise to Image
Q: Write your own Matlab code to add Gaussian
random noise with μ=0 and σ=0.1d (if the last digit of your ID is 7, then σ=0.17) to every pixel of
your images. Do not use “imnoise” function. Repeat it with μ=0 and σ=0.2d. Display and report
the resultant images side by side in the same figure. Draw the histograms of the original and the
noisy yourName _gray images side by side in another figure. Comment on the results briefly.
### Image Smoothing by Averaging Filter
Q: Write your own Matlab code
to add 1d% (if the last digit of your ID is 7, then 17%, i.e. the probability of a
pixel to be noisy should be 0.17) salt&pepper noise to your images. Do not use
“imnoise” function. Repeat it by adding 2d% salt&pepper noise. Display and
report the resultant images side by side in the same figure. Draw the
histograms of the original and the noisy yourName _gray images side by side in another figure.
Comment on the results briefly.
### Median Filtering
Q: Write your own Matlab function(with a double for loop) to make a 3x3
pixel median filter (No padding, DO NOT USE medfilt, medfilt2, ordfilt2, imfilter, conv2
functions). Denoise your salt&pepper noised images in Part 9 with your median filter. Apply 3x3
averaging filter on the same salt&pepper noised images. Display and report the obtained images
side by side in the same figure window together with their titles. Comment and compare the
results. What can you do to filter more noise with median and averaging filters from the images?
### Generating a radial gradient image
Q: Generate a grayscale n x n image
whose pixel values have a radial gradient from the upper left corner to the
lower right corner. In other words, the value of the upper left corner pixel
should be 0 (black) and the value of the pixels should increase according to
their distance to the upper left corner. The pixel on the lower right corner
should have 1 (white) value. (n=300+d*50, where d is the last digit of your
student ID number)
### Generating a circular black frame around an image
Q: Write a Matlab code
to generate a circular black frame around your image. (Hint: The pixels with a
distance larger than a radius "r” from the center of your image must be zero)
### Changing Color of an Object in the Image
Q: Take the logo of the
university (AYBU) and change the colors of the logo according to the following
color table using your last digit of your student ID number "d". Make the
foreground color "d" and background color "9-d". (e.g. if d=3: Make
foreground orange and background Blue)

![image](https://github.com/cerenkilic/EE409-Digital-Image-Processing-/assets/74498810/0c6c7a57-7acb-43e9-a2dc-0acdc7656e3d)

### Flipping image vertically
Q: Write the Matlab commands using array indexing method that flips
your color image vertically (i.e. first row becomes last row…). Display and report the resultant
image.
### Cropping a rectangular patch from image
Q: Crop a [1ab x 2ab] (where ab is the last 2 digits of
your student ID number) pixels patch from the center of your color image using indexing method.
Display and report the resultant patch.
### Manipulating pixel groups
Q: Write the Matlab command for drawing a vertical red line at the
middle of your color image by changing the color of the corresponding pixels to just red. Write the
Matlab command (using array indexing method) for drawing a yellow square box (100 pixels
width&height) at the center of your color image by changing the color of the corresponding pixels
to yellow. Display and report the resultant images.




