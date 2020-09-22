<pre>
Camera: Canon 500D
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
  D03 DE 0.05 DE LCh -0.02 -0.03 -0.04 (gray 70%)
  D05 DE 0.06 DE LCh -0.02 -0.04 -0.05 (gray 40%)
  D04 DE 0.08 DE LCh -0.03 -0.01 -0.07 (gray 50%)
  A01 DE 0.39 DE LCh +0.01 +0.17 -0.35 (dark brown)
  D01 DE 0.57 DE LCh -0.10 -0.56 -0.05 (white)
  A03 DE 0.82 DE LCh +0.61 -0.57 -0.08 (purple-blue)
  B04 DE 0.89 DE LCh +0.62 -0.14 +0.61 (dark purple)
  A06 DE 0.95 DE LCh +0.39 -0.55 +0.67 (light cyan)
  A05 DE 1.15 DE LCh +0.87 -0.25 +0.60 (purple-blue)
  C01 DE 1.15 DE LCh +0.90 -1.03 -0.56 (dark purple-blue)
  A02 DE 1.23 DE LCh +0.63 -0.79 -0.70 (red)
  B03 DE 1.24 DE LCh +0.87 -0.85 -0.26 (red)
  B02 DE 1.27 DE LCh +0.96 -0.92 -0.10 (purple-blue)
  A04 DE 1.55 DE LCh -0.73 +0.03 -1.36 (yellow-green)
  C05 DE 1.89 DE LCh +1.64 -0.55 +0.77 (purple-red)
  B01 DE 2.12 DE LCh +0.18 -1.31 -1.66 (strong orange)
  C06 DE 2.14 DE LCh +2.05 -0.59 +0.12 (blue)
  C02 DE 2.36 DE LCh -0.08 -2.34 +0.24 (yellow-green)
  C03 DE 2.50 DE LCh +2.00 -0.80 -1.26 (strong red)
  B05 DE 3.16 DE LCh -1.02 -2.98 -0.16 (light strong yellow-green)
  B06 DE 3.47 DE LCh -0.37 -3.15 -1.39 (light strong orange)
  C04 DE 4.01 DE LCh -0.38 -3.68 -1.56 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)


