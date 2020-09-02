This is a collection of spectral sensitivity data for digital cameras, with
the aim of improving the construction of camera profiles for raw processing
digital images.  

In making an image from a digital camera's raw capture, a
transform of the data to some defined colorspace, such as AdobeRGB or sRGB,
is required to make the image look right to the viewer.  The input data
description to this transform is usually a 3x3 matrix defining some sort of
chromatic bound, often called a "compromise matrix"  These matrices are
usually determined from a camera image of a color target, where the
reference values of the color patches are used to determine the matrix
extents.  This process is fraught with collection errors, primarily due to
the presence of 'glare' on the target. Additionally, while the 3x3 matrix is
usually sufficient to transform to pleasing colors, extreme colors with
gradation are not handled well by that simplistic transform.

To transition extreme colors and retain some sense of their gradation, a 
non-linear transform is required.  This is enabled in the transform
mechanisms by the replacement of the matrix with a lookup table, or LUT.
But, to effectively support the non-linear lookups, larger patch-count
targets are required, or in the best case, data representing the camera's
spectral sensitivity in each of the three bandpass filters comprising the
sensor mosaic.  This collection supports that best case.

The collection starts with the three cameras I own, using a DIY spectroscope
to capture the sensitivity measurements.  The data is reduced with software
I wrote specifically for the purpose, ssftool:
https://github.com/butcherg/ssftool.  The included ICC profiles were
produced from that data using dcamprof: https://github.com/Beep6581/dcamprof 

The collection is organized in subdirectories for each manufacturer, with
corresponding subdirectories for each camera.  As I find the oppurtunity to 
measure more cameras they will be added, and if a subsequent measurement for
a particular camera improves the profile max deltaE of the posted data, 
it will be replaced.  Data history can be regarded using git log; commits
will always identify the affected make and model of each camera being
updated.  Data from other collections may be added depending receiving
permission to do so, but all data posted to this repository will carry this
Creative Commons license:

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:cc="http://creativecommons.org/ns#" class="license-text"><span rel="dct:title">ssf-data</span> by <span property="cc:attributionName">Glenn Butcher</span> is licensed under <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" /><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" /></a></p>
