# COLORTREE

<p align="center">
  <img src="https://github.com/suhyuuk/COLORTREE/blob/main/opposite.jpg"  img width="300px"/>
<p/>
(PHOTO by 'https://www.smithsonianmag.com/smart-news/the-scientific-reason-complementary-colors-look-good-together-114030051/')

***
1. For every pixels of image, find **hue, saturation, value**
2. Scatterplot H(hue), S(saturation), V(value) in **cartesian coordinates**
3. **Clusterize** the scattered points (H, S, V) (Method : K - means, clusternumber = 1 % of datasize)
4. Scatterplot the centroids in **cylindrical coordinates**
5. Add branches, column of the *cylindrical* colortree

***

<p align="center">
  <img src="https://github.com/suhyuuk/COLORTREE/blob/main/cartesian_opposite.png"  img width="600px"/>
<p/>

Scatterplot of **all** HSV points in *cartesian coordinates*



<p align="center">
  <img src="https://github.com/suhyuuk/COLORTREE/blob/main/cylindrical_opposite.png"  img width="600px"/>
<p/>

Scatterplot of **all** HSV points in *cylindrical coordinates*



<p align="center">
  <img src="https://github.com/suhyuuk/COLORTREE/blob/main/cylindrical_opposite_1per_centroids.png"  img width="600px"/>
<p/>

Scatterplot of **centroids** of HSV derived with K-means cluster analysis(K = 1% of pixel num)
