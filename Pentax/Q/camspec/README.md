<pre>
Camera: Pentax Q
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
  D05 DE 0.05 DE LCh -0.03 +0.03 -0.03 (gray 40%)
  D03 DE 0.07 DE LCh -0.03 +0.04 -0.04 (gray 70%)
  D04 DE 0.09 DE LCh -0.04 +0.07 -0.04 (gray 50%)
  D06 DE 0.09 DE LCh +0.01 +0.08 +0.04 (gray 20%)
  D01 DE 0.62 DE LCh -0.14 -0.60 +0.02 (white)
  A01 DE 0.73 DE LCh -0.04 +0.37 -0.63 (dark brown)
  A06 DE 0.81 DE LCh +0.56 -0.58 -0.03 (light cyan)
  B04 DE 0.89 DE LCh +0.63 -0.14 +0.61 (dark purple)
  A02 DE 1.08 DE LCh +0.93 +0.00 -0.55 (red)
  A03 DE 1.20 DE LCh +0.89 -0.76 +0.12 (purple-blue)
  A04 DE 1.30 DE LCh -0.96 -0.21 -0.86 (yellow-green)
  C01 DE 1.38 DE LCh +1.20 -0.96 -0.98 (dark purple-blue)
  B02 DE 1.41 DE LCh +1.23 -1.12 -0.71 (purple-blue)
  A05 DE 1.55 DE LCh +1.14 -0.62 +0.61 (purple-blue)
  B03 DE 1.56 DE LCh +1.56 +0.10 +0.03 (red)
  C02 DE 1.92 DE LCh -0.14 -1.91 +0.04 (yellow-green)
  B01 DE 2.14 DE LCh +0.37 -1.31 -1.65 (strong orange)
  C05 DE 3.09 DE LCh +2.73 -0.04 +1.45 (purple-red)
  B05 DE 3.28 DE LCh -1.33 -2.94 +0.61 (light strong yellow-green)
  C06 DE 3.42 DE LCh +2.95 -1.75 -0.09 (blue)
  B06 DE 3.44 DE LCh -0.58 -3.18 -1.17 (light strong orange)
  C04 DE 3.75 DE LCh -0.60 -3.69 -0.25 (light vivid yellow)
  C03 DE 4.10 DE LCh +3.72 -0.29 -1.70 (strong red)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
