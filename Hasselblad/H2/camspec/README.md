<pre>
Camera: Hasselblad H2
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
  D05 DE 0.11 DE LCh -0.03 +0.09 -0.06 (gray 40%)
  D03 DE 0.14 DE LCh -0.03 +0.08 -0.11 (gray 70%)
  D06 DE 0.14 DE LCh +0.00 +0.14 -0.01 (gray 20%)
  D04 DE 0.15 DE LCh -0.03 +0.14 -0.01 (gray 50%)
  A03 DE 0.48 DE LCh +0.12 -0.49 -0.23 (purple-blue)
  D01 DE 0.59 DE LCh -0.14 -0.54 -0.19 (white)
  B04 DE 0.74 DE LCh +0.36 -0.14 +0.63 (dark purple)
  A05 DE 0.77 DE LCh +0.17 -0.25 +0.60 (purple-blue)
  A04 DE 0.85 DE LCh +0.36 +0.33 -0.70 (yellow-green)
  B02 DE 0.85 DE LCh -0.34 -0.81 -1.30 (purple-blue)
  C01 DE 1.14 DE LCh -0.01 -0.47 -1.47 (dark purple-blue)
  A06 DE 1.25 DE LCh +0.58 -0.73 +0.84 (light cyan)
  A01 DE 1.39 DE LCh +0.01 +0.11 +1.38 (dark brown)
  A02 DE 1.53 DE LCh +0.48 -0.07 -1.46 (red)
  B03 DE 1.71 DE LCh +0.63 +0.39 -1.55 (red)
  C06 DE 1.80 DE LCh +1.15 -0.28 +1.36 (blue)
  C05 DE 1.95 DE LCh +0.96 +0.67 +1.55 (purple-red)
  B01 DE 2.12 DE LCh -0.06 -1.31 -1.66 (strong orange)
  B06 DE 2.15 DE LCh +0.06 -2.14 +0.04 (light strong orange)
  C02 DE 2.73 DE LCh +0.89 -2.41 +0.92 (yellow-green)
  C03 DE 2.86 DE LCh +1.98 +0.14 -2.06 (strong red)
  B05 DE 3.23 DE LCh +0.26 -3.06 +0.99 (light strong yellow-green)
  C04 DE 3.72 DE LCh +0.28 -3.68 -0.48 (light vivid yellow)
 </pre>

(Data reported during the construction of the LUT ICC with dcamprof)
