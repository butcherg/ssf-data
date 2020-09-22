<pre>
Camera: Canon 5DMarkII
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
  D06 DE 0.05 DE LCh +0.01 -0.03 +0.03 (gray 20%)
  D03 DE 0.08 DE LCh -0.02 -0.04 -0.06 (gray 70%)
  D04 DE 0.10 DE LCh -0.03 -0.02 -0.10 (gray 50%)
  D05 DE 0.12 DE LCh -0.02 -0.04 -0.10 (gray 40%)
  A01 DE 0.22 DE LCh +0.01 +0.20 -0.10 (dark brown)
  C01 DE 0.34 DE LCh -0.11 -0.45 -0.22 (dark purple-blue)
  B02 DE 0.49 DE LCh +0.10 -0.55 -0.09 (purple-blue)
  A03 DE 0.57 DE LCh +0.36 -0.48 -0.21 (purple-blue)
  B04 DE 0.67 DE LCh +0.21 -0.14 +0.61 (dark purple)
  D01 DE 0.67 DE LCh -0.12 -0.64 -0.16 (white)
  B03 DE 0.79 DE LCh +0.63 -0.28 -0.38 (red)
  A05 DE 0.85 DE LCh +0.45 -0.24 +0.58 (purple-blue)
  A06 DE 1.13 DE LCh +0.56 -0.51 +0.84 (light cyan)
  A02 DE 1.23 DE LCh +0.64 -0.66 -0.82 (red)
  B01 DE 1.33 DE LCh -0.20 -1.05 -0.78 (strong orange)
  C05 DE 1.35 DE LCh +1.00 +0.05 +0.91 (purple-red)
  C02 DE 1.45 DE LCh +0.45 -1.31 +0.44 (yellow-green)
  A04 DE 1.51 DE LCh -0.37 -0.12 -1.46 (yellow-green)
  B06 DE 1.71 DE LCh -0.51 -1.30 -0.97 (light strong orange)
  C06 DE 1.97 DE LCh +1.81 -0.43 +0.65 (blue)
  B05 DE 2.07 DE LCh -0.40 -2.03 -0.06 (light strong yellow-green)
  C03 DE 2.15 DE LCh +1.53 -0.12 -1.50 (strong red)
  C04 DE 2.77 DE LCh -0.24 -2.58 -0.99 (light vivid yellow)
  </pre>
  
  (Data reported during the construction of the LUT ICC with dcamprof)

