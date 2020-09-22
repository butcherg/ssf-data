<pre>
Camera: Nikon D50
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
  D03 DE 0.12 DE LCh -0.02 +0.12 -0.02 (gray 70%)
  D05 DE 0.13 DE LCh -0.02 +0.11 +0.06 (gray 40%)
  D04 DE 0.15 DE LCh -0.03 +0.12 +0.09 (gray 50%)
  D06 DE 0.17 DE LCh +0.00 +0.17 -0.00 (gray 20%)
  A01 DE 0.30 DE LCh +0.04 +0.16 +0.25 (dark brown)
  D01 DE 0.36 DE LCh -0.14 -0.33 +0.03 (white)
  B02 DE 0.44 DE LCh -0.01 -0.56 -0.16 (purple-blue)
  A03 DE 0.47 DE LCh +0.22 -0.35 +0.13 (purple-blue)
  A04 DE 0.60 DE LCh +0.09 +0.46 -0.38 (yellow-green)
  B03 DE 0.77 DE LCh +0.52 +0.12 -0.55 (red)
  B04 DE 0.77 DE LCh +0.42 -0.14 +0.62 (dark purple)
  B06 DE 0.77 DE LCh -0.42 -0.59 +0.26 (light strong orange)
  B01 DE 0.81 DE LCh -0.33 -0.22 -0.70 (strong orange)
  B05 DE 0.81 DE LCh +0.03 -0.78 +0.21 (light strong yellow-green)
  A05 DE 0.83 DE LCh +0.30 -0.26 +0.62 (purple-blue)
  C01 DE 0.85 DE LCh -0.06 -0.79 -1.28 (dark purple-blue)
  C05 DE 1.05 DE LCh +0.83 +0.06 +0.65 (purple-red)
  A02 DE 1.11 DE LCh +0.53 +0.20 -0.96 (red)
  C02 DE 1.23 DE LCh +0.66 -1.02 -0.22 (yellow-green)
  C04 DE 1.28 DE LCh -0.08 -1.28 +0.07 (light vivid yellow)
  A06 DE 1.30 DE LCh +0.54 -1.00 +0.62 (light cyan)
  C03 DE 1.50 DE LCh +1.46 -0.19 -0.34 (strong red)
  C06 DE 2.17 DE LCh +1.37 -0.98 +1.35 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
