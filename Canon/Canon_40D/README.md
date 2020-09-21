  <pre>
Camera: Canon 40D
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
  D06 DE 0.12 DE LCh +0.01 -0.10 +0.06 (gray 20%)
  D03 DE 0.17 DE LCh -0.03 -0.05 -0.16 (gray 70%)
  D04 DE 0.20 DE LCh -0.03 -0.07 -0.18 (gray 50%)
  D05 DE 0.20 DE LCh -0.03 -0.04 -0.20 (gray 40%)
  A01 DE 0.27 DE LCh +0.04 +0.03 +0.26 (dark brown)
  B04 DE 0.70 DE LCh +0.25 -0.14 +0.63 (dark purple)
  B03 DE 0.80 DE LCh +0.59 -0.34 -0.40 (red)
  A05 DE 0.82 DE LCh +0.33 -0.25 +0.60 (purple-blue)
  D01 DE 0.90 DE LCh -0.14 -0.83 -0.33 (white)
  A03 DE 1.00 DE LCh +0.25 -0.61 +0.56 (purple-blue)
  A04 DE 1.21 DE LCh -0.14 +0.04 -1.20 (yellow-green)
  C01 DE 1.29 DE LCh -0.66 +0.07 +1.16 (dark purple-blue)
  A06 DE 1.31 DE LCh +0.69 -0.73 +0.84 (light cyan)
  A02 DE 1.37 DE LCh +0.70 -0.62 -1.00 (red)
  B02 DE 1.42 DE LCh -0.30 -0.28 +1.15 (purple-blue)
  B01 DE 1.55 DE LCh -0.15 -1.52 -0.28 (strong orange)
  C05 DE 1.65 DE LCh +0.96 +0.09 +1.34 (purple-red)
  B06 DE 1.80 DE LCh -0.34 -1.76 +0.11 (light strong orange)
  C02 DE 1.88 DE LCh +0.78 -1.69 +0.23 (yellow-green)
  B05 DE 2.29 DE LCh -0.13 -2.25 +0.42 (light strong yellow-green)
  C06 DE 2.33 DE LCh +1.78 -0.59 +1.37 (blue)
  C03 DE 2.34 DE LCh +1.83 -0.09 -1.46 (strong red)
  C04 DE 3.00 DE LCh -0.02 -3.00 -0.04 (light vivid yellow)
  </pre>
  
  (Data reported during the construction of the LUT ICC with dcamprof)
  
