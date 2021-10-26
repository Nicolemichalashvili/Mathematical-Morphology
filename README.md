# Mathematical-Morphology
Mathematical morphology is a term for several methods and techniques in the field of image processing which are used to alter, extract and transform the geometric shapes of images and objects.
The main idea in all morphological operators is to use simple binary shapes (usually much smaller than the image) called “structuring elements” of size m x n and compare them with all m x n sub-matrices of the image. The way in which these “structuring elements” interact with the sub-matrices of the image allows us to draw conclusions and perform several operations such as removing small objects, filling holes, completing lines and so on.

# Morphological Operations
The primary morphological operations are **Dilation** and **Erosion**.

More complicated morphological operators can be designed by means of **combining** erosions and dilations.

![image](https://user-images.githubusercontent.com/90917375/138886220-f2292bd4-003a-42de-8070-cce2f9881d85.png)

Erosion is one of the fundamental morphological operations (the other being Dilation).
The Erosion of a binary image A by structuring element B produces a new binary image.
In practice, erosion tends to shrink large objects, widen holes and gaps, remove small objects and eliminate unnecessary noise.
The larger the structuring element, the more noticeable the effect will be.

![image](https://user-images.githubusercontent.com/90917375/138885262-b794f0ca-606c-4523-92fb-411c9eda284d.png)

Dilation is the other fundamental morphological operation and is the dual operator to Erosion.
The dilation of a binary image A by structuring element B produces a new binary image.
In practice, dilation tends to enlarge objects, fill up holes and gaps, widen lines and “fatten” shapes.

![image](https://user-images.githubusercontent.com/90917375/138885482-c3bfe9e0-c07c-4fcc-8c2c-635c82147a60.png)

![image](https://user-images.githubusercontent.com/90917375/138885726-51e33229-7481-4dc3-a9b3-64bc3f2b6b33.png)

The opening of A by B is the erosion of A by B followed by dilation by B.
Opening tends to widen gaps and holes and remove small objects, while maintaining the original size of larger objects without “fattening” them as in dilation.

![image](https://user-images.githubusercontent.com/90917375/138885798-4e1f42ab-4444-4d02-b5ed-bd35b03bcb02.png)

The Closing of A by B is the dilation of A by B followed by erosion by B.
Closing tends to bridge gaps and close holes while still maintaining the original size of larger objects without shrinking them as in erosion.

![image](https://user-images.githubusercontent.com/90917375/138885843-6dd9dd93-6a27-465c-84a8-589d92c47b37.png)







  





