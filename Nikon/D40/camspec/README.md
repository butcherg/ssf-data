<pre>
Camera: Nikon D40
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
  D03 DE 0.15 DE LCh -0.02 +0.14 +0.04 (gray 70%)
  D05 DE 0.16 DE LCh -0.02 +0.11 +0.11 (gray 40%)
  D04 DE 0.18 DE LCh -0.03 +0.09 +0.15 (gray 50%)
  D06 DE 0.18 DE LCh +0.00 +0.18 -0.01 (gray 20%)
  A01 DE 0.30 DE LCh +0.01 +0.12 -0.28 (dark brown)
  D01 DE 0.32 DE LCh -0.13 -0.24 +0.18 (white)
  A03 DE 0.47 DE LCh +0.33 -0.33 +0.00 (purple-blue)
  C01 DE 0.49 DE LCh +0.06 -0.71 -0.69 (dark purple-blue)
  A04 DE 0.53 DE LCh -0.10 +0.52 -0.01 (yellow-green)
  B02 DE 0.61 DE LCh +0.18 -0.53 +0.07 (purple-blue)
  B05 DE 0.63 DE LCh -0.17 -0.52 +0.31 (light strong yellow-green)
  C02 DE 0.68 DE LCh +0.56 -0.39 -0.08 (yellow-green)
  B03 DE 0.69 DE LCh +0.62 -0.21 -0.22 (red)
  A06 DE 0.74 DE LCh +0.55 -0.47 +0.11 (light cyan)
  B06 DE 0.76 DE LCh -0.63 -0.40 -0.15 (light strong orange)
  B04 DE 0.77 DE LCh +0.34 -0.27 +0.63 (dark purple)
  A05 DE 0.81 DE LCh +0.39 -0.37 +0.46 (purple-blue)
  A02 DE 0.96 DE LCh +0.58 -0.01 -0.76 (red)
  C04 DE 1.07 DE LCh -0.28 -1.03 +0.07 (light vivid yellow)
  C05 DE 1.09 DE LCh +0.88 -0.47 +0.44 (purple-red)
  B01 DE 1.52 DE LCh -0.37 -0.28 -1.45 (strong orange)
  C03 DE 1.63 DE LCh +1.36 -0.75 +0.50 (strong red)
  C06 DE 2.09 DE LCh +1.66 -1.10 +0.60 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
