<pre>
Camera: Pentax K-5
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
  D06 DE 0.07 DE LCh +0.02 -0.05 +0.04 (gray 20%)
  D03 DE 0.11 DE LCh -0.02 -0.04 -0.10 (gray 70%)
  D04 DE 0.13 DE LCh -0.03 -0.04 -0.12 (gray 50%)
  D05 DE 0.15 DE LCh -0.01 -0.03 -0.14 (gray 40%)
  A01 DE 0.33 DE LCh -0.10 +0.27 +0.16 (dark brown)
  D01 DE 0.70 DE LCh -0.15 -0.65 -0.21 (white)
  A04 DE 0.96 DE LCh -0.89 +0.36 -0.10 (yellow-green)
  A02 DE 1.10 DE LCh +0.57 -0.01 -0.94 (red)
  A06 DE 1.12 DE LCh +0.30 -0.67 +0.84 (light cyan)
  B03 DE 1.31 DE LCh +1.26 -0.24 -0.27 (red)
  B04 DE 1.45 DE LCh +1.29 -0.14 +0.62 (dark purple)
  A03 DE 1.55 DE LCh +1.17 -1.07 -0.18 (purple-blue)
  C02 DE 1.62 DE LCh -0.52 -1.28 +0.85 (yellow-green)
  A05 DE 1.67 DE LCh +1.49 -0.26 +0.61 (purple-blue)
  B01 DE 2.07 DE LCh -0.75 -0.94 -1.69 (strong orange)
  B06 DE 2.23 DE LCh -1.29 -1.64 -0.79 (light strong orange)
  C01 DE 2.32 DE LCh +2.19 -0.96 -0.29 (dark purple-blue)
  B02 DE 2.48 DE LCh +2.18 -1.24 -0.06 (purple-blue)
  C03 DE 2.58 DE LCh +2.44 -0.57 -0.64 (strong red)
  B05 DE 2.83 DE LCh -1.48 -2.15 +1.09 (light strong yellow-green)
  C04 DE 3.08 DE LCh -1.14 -2.83 -0.37 (light vivid yellow)
  C05 DE 3.12 DE LCh +2.59 -0.79 +1.54 (purple-red)
  C06 DE 3.34 DE LCh +2.62 -1.50 +1.38 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
