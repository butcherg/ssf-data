<pre>
Camera: Nikon D7000
Lens: AF-S DX Nikkor 18-140mm f/3.5-5.6G ED VR
Contributor: Glenn Butcher, glenn.butcher@gmail.com
DatasetRangeIntervalNM: 400,715,5
MeasurementDate: 2020-08-26
MeasurementMethod: Transmissive glass-substrate ruled diffraction grating spectroscope, single-image
DataReductionSoftware: ssftool
Copyright:2020 Glenn Butcher, all rights reserved
License:Creative Commons BY-NC-SA 4.0, https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode
</pre>

This dataset is the first one produced from my spectroscope experiment.  Actually, I ran a little more than a dozen collections, comparing results from different lens focal lengths and alignment attempts, and selected the attempt that produced the best deltaE. This collection is significant in that I used this camera as the performance standard for constructing the spectrometer, as I had monochromator SSF data with which to compare, courtesy the ACES rawtoaces project: https://github.com/ampas/rawtoaces

deltaE report, comparison of profile-generated patches to CC24 reference patches:
<pre>
  D02 DE 0.00 DE LCh +0.00 +0.00 +0.00 (gray 80%)
  D03 DE 0.12 DE LCh -0.01 -0.11 -0.03 (gray 70%)
  D04 DE 0.13 DE LCh -0.02 -0.04 -0.12 (gray 50%)
  D06 DE 0.16 DE LCh +0.01 -0.16 +0.00 (gray 20%)
  D05 DE 0.18 DE LCh -0.01 -0.09 -0.16 (gray 40%)
  A01 DE 0.35 DE LCh -0.08 +0.22 +0.27 (dark brown)
  D01 DE 0.70 DE LCh -0.11 -0.66 -0.19 (white)
  A06 DE 0.87 DE LCh +0.18 -0.18 +0.83 (light cyan)
  A02 DE 1.14 DE LCh +0.58 -0.20 -0.96 (red)
  A04 DE 1.15 DE LCh -0.85 +0.77 -0.02 (yellow-green)
  A03 DE 1.16 DE LCh +0.99 -0.46 -0.60 (purple-blue)
  B04 DE 1.37 DE LCh +0.74 -1.14 -0.26 (dark purple)
  B03 DE 1.39 DE LCh +1.31 -0.43 -0.14 (red)
  A05 DE 1.53 DE LCh +1.17 -1.10 -0.32 (purple-blue)
  C02 DE 1.64 DE LCh -0.51 -1.24 +0.95 (yellow-green)
  B01 DE 1.82 DE LCh -0.47 -0.43 -1.71 (strong orange)
  C03 DE 1.83 DE LCh +1.68 -0.65 -0.34 (strong red)
  B02 DE 1.88 DE LCh +1.78 -1.06 -0.75 (purple-blue)
  B06 DE 1.88 DE LCh -1.09 -1.23 -0.91 (light strong orange)
  C01 DE 2.12 DE LCh +2.05 -0.82 -0.52 (dark purple-blue)
  B05 DE 2.69 DE LCh -1.42 -2.09 +0.92 (light strong yellow-green)
  C05 DE 2.75 DE LCh +2.04 -1.47 +1.13 (purple-red)
  C06 DE 2.75 DE LCh +2.29 -0.95 +1.15 (blue)
  C04 DE 2.80 DE LCh -1.03 -2.57 -0.43 (light vivid yellow)
</pre>
(Data reported during the construction of an ICC LUT matrix with dcamprof)


