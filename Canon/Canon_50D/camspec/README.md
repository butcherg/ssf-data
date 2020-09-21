  <pre>
Camera: Canon 50D
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
  D06 DE 0.04 DE LCh +0.01 -0.01 +0.03 (gray 20%)
  D03 DE 0.06 DE LCh -0.02 -0.03 -0.04 (gray 70%)
  A01 DE 0.08 DE LCh +0.02 +0.05 -0.06 (dark brown)
  D05 DE 0.08 DE LCh -0.02 -0.04 -0.06 (gray 40%)
  D04 DE 0.09 DE LCh -0.03 -0.01 -0.08 (gray 50%)
  D01 DE 0.61 DE LCh -0.10 -0.60 -0.04 (white)
  B04 DE 0.76 DE LCh +0.41 -0.14 +0.62 (dark purple)
  C01 DE 0.78 DE LCh +0.52 -0.75 -0.25 (dark purple-blue)
  A03 DE 0.79 DE LCh +0.51 -0.56 +0.09 (purple-blue)
  B02 DE 0.94 DE LCh +0.58 -0.70 +0.04 (purple-blue)
  A06 DE 0.97 DE LCh +0.48 -0.67 +0.51 (light cyan)
  A05 DE 1.02 DE LCh +0.71 -0.24 +0.58 (purple-blue)
  A02 DE 1.16 DE LCh +0.71 -0.83 -0.39 (red)
  B03 DE 1.16 DE LCh +0.94 -0.68 +0.04 (red)
  A04 DE 1.45 DE LCh -0.61 +0.05 -1.32 (yellow-green)
  C05 DE 1.82 DE LCh +1.51 -0.44 +0.93 (purple-red)
  B01 DE 2.15 DE LCh +0.20 -1.33 -1.68 (strong orange)
  C02 DE 2.18 DE LCh +0.15 -2.17 +0.14 (yellow-green)
  C06 DE 2.27 DE LCh +2.07 -0.86 +0.33 (blue)
  C03 DE 2.35 DE LCh +2.13 -0.66 -0.73 (strong red)
  B06 DE 2.58 DE LCh -0.35 -2.54 -0.27 (light strong orange)
  B05 DE 3.07 DE LCh -0.83 -2.96 +0.06 (light strong yellow-green)
  C04 DE 3.73 DE LCh -0.29 -3.71 -0.25 (light vivid yellow)
  </pre>
  
  (Data reported during the construction of the LUT ICC with dcamprof)
  
