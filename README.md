<h1>Content-Aware-Seam-Carving</h1>

Effective resizing of images should not only use geometric constraints, but also consider the image content as well.
We implement a method of content aware seam carving proposed by Shamir et al.[1] for reduction, expansion and object removal of the image.

<p align="center">
  <img src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/Gif_progress.gif" alt="animated" />
</p>

<h2>
  Requirements
</h2>
<p>
  1. OpenCV</br>
  2. Numpy</br>
  3. Matplotlib</br>
  4. Imageio
</p>

<h2>
  Results
</h2>

  
<h3>Width Reduction and object removal</h3>
<p>
<img title="Original Image" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/1.jpg" alt="Original Image">  <img  title ="Sobel Energy" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/1_EnergySobel.jpg" >  <img title="WidthReduce" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/1_ImageReduce.jpg" >  <img title="ObjectRemoval" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/1_ObjectRemoval.jpg" >
</p>

<h3>Width Enlarge and object removal</h3>
<p>
<img title="Original Image" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/3.jpg" alt="Original Image">  <img  title ="Sobel Energy" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/3_EnergySobel.jpg" >  <img title="Width enlarge" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/result_increase_width.jpg" >  <img title="ObjectRemoval" src="https://github.com/pantDevesh/Content-Aware-Seam-Carving/blob/master/Results/3_ObjectRemoval.jpg" >
</p>



Reference-
1. https://perso.crans.org/frenoy/matlab2012/seamcarving.pdf



