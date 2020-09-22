<pre>
Camera: Canon 20D
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
  D06 DE 0.14 DE LCh +0.00 -0.14 +0.05 (gray 20%)
  D03 DE 0.19 DE LCh -0.02 -0.08 -0.17 (gray 70%)
  D04 DE 0.21 DE LCh -0.02 -0.05 -0.20 (gray 50%)
  D05 DE 0.26 DE LCh -0.02 -0.06 -0.25 (gray 40%)
  A03 DE 0.54 DE LCh +0.13 -0.52 -0.37 (purple-blue)
  B02 DE 0.64 DE LCh -0.50 -0.52 -0.69 (purple-blue)
  B04 DE 0.66 DE LCh +0.12 -0.14 +0.63 (dark purple)
  A05 DE 0.76 DE LCh +0.13 -0.25 +0.60 (purple-blue)
  C01 DE 0.77 DE LCh -0.58 -0.34 -0.71 (dark purple-blue)
  B03 DE 0.81 DE LCh +0.42 +0.12 -0.69 (red)
  A01 DE 0.91 DE LCh +0.03 +0.46 +0.78 (dark brown)
  D01 DE 0.94 DE LCh -0.13 -0.84 -0.42 (white)
  A04 DE 1.02 DE LCh +0.11 +0.42 -0.93 (yellow-green)
  B06 DE 1.02 DE LCh -0.21 -0.99 -0.12 (light strong orange)
  A06 DE 1.23 DE LCh +0.53 -0.73 +0.84 (light cyan)
  B01 DE 1.31 DE LCh -0.24 -0.82 -0.99 (strong orange)
  A02 DE 1.38 DE LCh +0.47 -0.12 -1.29 (red)
  C05 DE 1.71 DE LCh +0.72 -0.04 +1.55 (purple-red)
  C06 DE 1.81 DE LCh +1.16 -0.28 +1.36 (blue)
  B05 DE 1.93 DE LCh +0.11 -1.88 +0.41 (light strong yellow-green)
  C02 DE 1.93 DE LCh +0.79 -1.60 +0.73 (yellow-green)
  C03 DE 2.23 DE LCh +1.51 +0.05 -1.64 (strong red)
  C04 DE 2.43 DE LCh +0.11 -2.38 -0.49 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)


