<pre>
Camera: Canon 1DMarkIII
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
  D03 DE 0.08 DE LCh -0.02 -0.06 -0.04 (gray 70%)
  D06 DE 0.08 DE LCh +0.00 -0.07 +0.01 (gray 20%)
  D04 DE 0.09 DE LCh -0.03 -0.01 -0.09 (gray 50%)
  D05 DE 0.13 DE LCh -0.02 -0.06 -0.12 (gray 40%)
  A01 DE 0.18 DE LCh -0.06 +0.14 +0.11 (dark brown)
  A03 DE 0.44 DE LCh +0.22 -0.40 -0.24 (purple-blue)
  B02 DE 0.60 DE LCh -0.54 -0.24 +0.03 (purple-blue)
  A05 DE 0.61 DE LCh +0.13 -0.36 +0.34 (purple-blue)
  B03 DE 0.66 DE LCh +0.48 -0.21 -0.39 (red)
  B04 DE 0.70 DE LCh -0.10 -0.30 +0.61 (dark purple)
  D01 DE 0.70 DE LCh -0.13 -0.68 -0.14 (white)
  B06 DE 0.82 DE LCh -0.50 -0.58 -0.29 (light strong orange)
  C05 DE 0.88 DE LCh +0.63 -0.18 +0.58 (purple-red)
  C01 DE 0.95 DE LCh -0.85 +0.05 +0.48 (dark purple-blue)
  A04 DE 1.15 DE LCh +0.03 +0.61 -0.97 (yellow-green)
  A06 DE 1.24 DE LCh +0.72 -0.54 +0.84 (light cyan)
  A02 DE 1.25 DE LCh +0.57 -0.59 -0.95 (red)
  B05 DE 1.27 DE LCh +0.05 -1.25 +0.20 (light strong yellow-green)
  C02 DE 1.34 DE LCh +0.97 -0.86 +0.33 (yellow-green)
  B01 DE 1.41 DE LCh -0.52 -0.61 -1.16 (strong orange)
  C03 DE 1.66 DE LCh +1.52 -0.52 -0.41 (strong red)
  C04 DE 1.83 DE LCh -0.03 -1.80 -0.31 (light vivid yellow)
  C06 DE 2.12 DE LCh +1.66 -0.56 +1.19 (blue)
  </pre>
  
  (Data reported during the construction of the LUT ICC with dcamprof)

