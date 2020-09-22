<pre>
Camera: Nikon D200
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
  D03 DE 0.12 DE LCh -0.02 -0.08 -0.08 (gray 70%)
  D04 DE 0.13 DE LCh -0.02 -0.00 -0.12 (gray 50%)
  D06 DE 0.14 DE LCh +0.00 -0.14 +0.02 (gray 20%)
  D05 DE 0.18 DE LCh -0.01 -0.06 -0.17 (gray 40%)
  B02 DE 0.34 DE LCh +0.02 -0.50 -0.59 (purple-blue)
  A01 DE 0.35 DE LCh -0.03 +0.19 +0.29 (dark brown)
  C01 DE 0.59 DE LCh +0.36 -0.68 -0.66 (dark purple-blue)
  A03 DE 0.63 DE LCh +0.35 -0.54 -0.35 (purple-blue)
  B06 DE 0.71 DE LCh -0.66 -0.21 +0.14 (light strong orange)
  A05 DE 0.74 DE LCh +0.32 -0.53 +0.24 (purple-blue)
  B03 DE 0.74 DE LCh +0.64 +0.11 -0.36 (red)
  D01 DE 0.75 DE LCh -0.13 -0.70 -0.23 (white)
  A04 DE 0.77 DE LCh -0.00 +0.77 -0.08 (yellow-green)
  C02 DE 0.94 DE LCh +0.67 -0.63 +0.20 (yellow-green)
  B05 DE 0.99 DE LCh -0.12 -0.75 +0.63 (light strong yellow-green)
  A02 DE 1.14 DE LCh +0.53 -0.02 -1.01 (red)
  A06 DE 1.16 DE LCh +0.57 -0.57 +0.83 (light cyan)
  C04 DE 1.26 DE LCh -0.25 -1.24 +0.04 (light vivid yellow)
  B04 DE 1.31 DE LCh +0.09 -1.14 +0.60 (dark purple)
  C05 DE 1.52 DE LCh +0.88 -0.47 +1.15 (purple-red)
  C03 DE 1.53 DE LCh +1.44 -0.47 -0.21 (strong red)
  B01 DE 1.77 DE LCh -0.55 -0.29 -1.66 (strong orange)
  C06 DE 2.35 DE LCh +1.64 -0.92 +1.38 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
