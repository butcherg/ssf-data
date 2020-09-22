<pre>
Camera: Nokia N900
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
  A01 DE 0.20 DE LCh +0.01 +0.19 -0.07 (dark brown)
  D03 DE 0.20 DE LCh -0.02 +0.19 +0.02 (gray 70%)
  D04 DE 0.23 DE LCh -0.03 +0.16 +0.17 (gray 50%)
  D05 DE 0.24 DE LCh -0.03 +0.19 +0.15 (gray 40%)
  D06 DE 0.28 DE LCh -0.00 +0.28 -0.04 (gray 20%)
  D01 DE 0.46 DE LCh -0.14 -0.38 +0.22 (white)
  B04 DE 0.47 DE LCh -0.05 +0.19 +0.44 (dark purple)
  A03 DE 0.51 DE LCh +0.16 -0.25 +0.33 (purple-blue)
  B02 DE 0.63 DE LCh -0.30 -0.42 -0.84 (purple-blue)
  A05 DE 0.73 DE LCh +0.15 -0.18 +0.61 (purple-blue)
  A04 DE 0.81 DE LCh -0.02 +0.18 -0.79 (yellow-green)
  A06 DE 0.98 DE LCh +0.48 -0.82 +0.25 (light cyan)
  C01 DE 0.98 DE LCh -0.40 -0.64 -1.28 (dark purple-blue)
  A02 DE 0.99 DE LCh +0.59 +0.07 -0.80 (red)
  B03 DE 1.21 DE LCh +1.14 +0.37 -0.18 (red)
  C05 DE 1.70 DE LCh +1.35 +0.30 +0.99 (purple-red)
  C02 DE 2.12 DE LCh +0.63 -2.02 -0.14 (yellow-green)
  B01 DE 2.49 DE LCh +1.24 -1.35 -1.69 (strong orange)
  C06 DE 2.50 DE LCh +1.37 -1.56 +1.36 (blue)
  B05 DE 3.10 DE LCh -0.14 -3.02 +0.70 (light strong yellow-green)
  B06 DE 3.48 DE LCh +0.61 -3.14 -1.36 (light strong orange)
  C03 DE 3.74 DE LCh +3.34 -0.69 -1.54 (strong red)
  C04 DE 3.85 DE LCh +0.50 -3.69 +0.98 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
