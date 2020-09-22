<pre>
Camera: Nikon D80
Contributor: Jun Jiang, Dengyu Liu, Jinwei Gu and Sabine Süsstrunk, http://www.gujinwei.org/research/camspec/db.html
DatasetRangeIntervalNM: 400,720,10
MeasurementMethod: Monochromator, multiple-image
Copyright:(C) Rochester Institute of Technology. All rights reserved.
License:Creative Commons BY-NC-SA 4.0, https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode
</pre>

- .csv file contains comma-separated data, column-major.
- .json file contains data formatted for ingestion by dcamprof.
- .icc file contains a A0toB0 LUT to apply a linear, perceptual intent transform.

deltaE report, comparison of profile-generated patches to CC24 reference patches:
<pre>
  D02 DE 0.00 DE LCh +0.00 +0.00 +0.00 (gray 80%)
  D03 DE 0.13 DE LCh -0.01 -0.09 -0.08 (gray 70%)
  D04 DE 0.14 DE LCh -0.02 -0.01 -0.14 (gray 50%)
  D06 DE 0.14 DE LCh +0.00 -0.14 +0.01 (gray 20%)
  D05 DE 0.21 DE LCh -0.01 -0.07 -0.20 (gray 40%)
  C01 DE 0.33 DE LCh -0.04 -0.47 -0.46 (dark purple-blue)
  B02 DE 0.40 DE LCh -0.22 -0.46 -0.57 (purple-blue)
  A03 DE 0.61 DE LCh +0.27 -0.53 -0.43 (purple-blue)
  B03 DE 0.61 DE LCh +0.39 +0.05 -0.47 (red)
  A05 DE 0.63 DE LCh +0.19 -0.51 +0.15 (purple-blue)
  B06 DE 0.67 DE LCh -0.52 -0.41 +0.01 (light strong orange)
  A01 DE 0.71 DE LCh -0.03 +0.34 +0.62 (dark brown)
  D01 DE 0.80 DE LCh -0.13 -0.75 -0.25 (white)
  B05 DE 1.03 DE LCh +0.06 -0.77 +0.68 (light strong yellow-green)
  A04 DE 1.07 DE LCh +0.14 +1.06 -0.07 (yellow-green)
  C02 DE 1.13 DE LCh +0.79 -0.72 +0.36 (yellow-green)
  A06 DE 1.19 DE LCh +0.56 -0.61 +0.85 (light cyan)
  A02 DE 1.21 DE LCh +0.42 -0.02 -1.14 (red)
  B04 DE 1.24 DE LCh +0.08 -1.13 +0.45 (dark purple)
  C04 DE 1.30 DE LCh -0.10 -1.29 +0.17 (light vivid yellow)
  C03 DE 1.41 DE LCh +1.29 -0.52 -0.22 (strong red)
  C05 DE 1.61 DE LCh +0.70 -0.58 +1.33 (purple-red)
  B01 DE 1.74 DE LCh -0.51 -0.27 -1.64 (strong orange)
  C06 DE 1.96 DE LCh +1.38 -0.28 +1.36 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
