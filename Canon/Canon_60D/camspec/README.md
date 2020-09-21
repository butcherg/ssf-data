<pre>
Camera: Canon 60D
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
  D06 DE 0.04 DE LCh +0.01 -0.00 +0.04 (gray 20%)
  D03 DE 0.07 DE LCh -0.02 -0.03 -0.06 (gray 70%)
  D04 DE 0.09 DE LCh -0.03 -0.03 -0.08 (gray 50%)
  D05 DE 0.09 DE LCh -0.02 -0.03 -0.08 (gray 40%)
  A01 DE 0.24 DE LCh +0.04 +0.14 -0.20 (dark brown)
  C01 DE 0.56 DE LCh +0.30 -0.72 -0.55 (dark purple-blue)
  A03 DE 0.62 DE LCh +0.42 -0.46 -0.01 (purple-blue)
  D01 DE 0.63 DE LCh -0.13 -0.61 -0.10 (white)
  B02 DE 0.71 DE LCh +0.42 -0.68 -0.14 (purple-blue)
  B04 DE 0.73 DE LCh +0.35 -0.14 +0.62 (dark purple)
  A05 DE 0.95 DE LCh +0.61 -0.24 +0.58 (purple-blue)
  A06 DE 0.98 DE LCh +0.47 -0.53 +0.67 (light cyan)
  B03 DE 1.00 DE LCh +0.83 -0.39 -0.41 (red)
  A02 DE 1.15 DE LCh +0.67 -0.54 -0.76 (red)
  A04 DE 1.15 DE LCh -0.51 -0.09 -1.02 (yellow-green)
  C05 DE 1.56 DE LCh +1.31 -0.06 +0.84 (purple-red)
  C02 DE 1.66 DE LCh +0.17 -1.60 +0.42 (yellow-green)
  B01 DE 1.78 DE LCh +0.00 -1.50 -0.96 (strong orange)
  C06 DE 2.04 DE LCh +1.88 -0.67 +0.45 (blue)
  B06 DE 2.16 DE LCh -0.38 -1.93 -0.89 (light strong orange)
  C03 DE 2.40 DE LCh +1.86 -0.29 -1.50 (strong red)
  B05 DE 2.60 DE LCh -0.65 -2.51 +0.21 (light strong yellow-green)
  C04 DE 3.32 DE LCh -0.26 -3.21 -0.82 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)

