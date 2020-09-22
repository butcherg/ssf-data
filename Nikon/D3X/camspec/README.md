<pre>
Camera: Nikon D3X
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
  D03 DE 0.09 DE LCh -0.01 -0.07 -0.04 (gray 70%)
  D06 DE 0.09 DE LCh +0.01 -0.09 +0.00 (gray 20%)
  D04 DE 0.10 DE LCh -0.02 -0.01 -0.10 (gray 50%)
  D05 DE 0.15 DE LCh -0.01 -0.05 -0.14 (gray 40%)
  A01 DE 0.43 DE LCh -0.04 +0.26 +0.34 (dark brown)
  D01 DE 0.65 DE LCh -0.13 -0.62 -0.14 (white)
  A04 DE 0.68 DE LCh -0.31 +0.59 +0.08 (yellow-green)
  A03 DE 0.74 DE LCh +0.49 -0.58 -0.34 (purple-blue)
  B02 DE 0.80 DE LCh +0.55 -0.85 -0.99 (purple-blue)
  A05 DE 0.89 DE LCh +0.54 -0.70 +0.00 (purple-blue)
  A06 DE 0.97 DE LCh +0.34 -0.44 +0.80 (light cyan)
  C01 DE 1.05 DE LCh +0.69 -1.04 -1.20 (dark purple-blue)
  B03 DE 1.07 DE LCh +0.89 +0.12 -0.60 (red)
  A02 DE 1.18 DE LCh +0.49 +0.17 -1.05 (red)
  C02 DE 1.19 DE LCh +0.13 -0.96 +0.69 (yellow-green)
  B04 DE 1.20 DE LCh +0.23 -1.15 +0.21 (dark purple)
  B06 DE 1.33 DE LCh -0.57 -1.15 -0.35 (light strong orange)
  C05 DE 1.64 DE LCh +1.22 -0.53 +0.94 (purple-red)
  B01 DE 1.76 DE LCh -0.31 -0.56 -1.64 (strong orange)
  C03 DE 1.83 DE LCh +1.48 -0.63 -0.88 (strong red)
  B05 DE 1.92 DE LCh -0.56 -1.55 +0.98 (light strong yellow-green)
  C04 DE 2.30 DE LCh -0.39 -2.26 -0.14 (light vivid yellow)
  C06 DE 2.34 DE LCh +1.63 -0.92 +1.39 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
