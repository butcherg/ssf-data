<pre>
Camera: Nikon D5100
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
  D03 DE 0.14 DE LCh -0.01 -0.11 -0.09 (gray 70%)
  D04 DE 0.15 DE LCh -0.02 -0.01 -0.15 (gray 50%)
  D06 DE 0.18 DE LCh +0.01 -0.17 +0.02 (gray 20%)
  D05 DE 0.22 DE LCh -0.01 -0.08 -0.20 (gray 40%)
  A01 DE 0.45 DE LCh -0.04 +0.22 +0.39 (dark brown)
  D01 DE 0.87 DE LCh -0.13 -0.81 -0.31 (white)
  A04 DE 0.96 DE LCh -0.69 +0.67 -0.11 (yellow-green)
  A06 DE 1.05 DE LCh +0.28 -0.53 +0.86 (light cyan)
  A03 DE 1.18 DE LCh +0.85 -0.82 -0.54 (purple-blue)
  A02 DE 1.24 DE LCh +0.60 -0.21 -1.06 (red)
  B03 DE 1.30 DE LCh +1.19 -0.39 -0.35 (red)
  B04 DE 1.39 DE LCh +0.72 -1.13 +0.34 (dark purple)
  A05 DE 1.48 DE LCh +1.03 -1.01 +0.08 (purple-blue)
  C01 DE 1.57 DE LCh +1.45 -0.91 -0.59 (dark purple-blue)
  B02 DE 1.60 DE LCh +1.42 -1.22 -0.75 (purple-blue)
  C02 DE 1.71 DE LCh -0.24 -1.45 +0.87 (yellow-green)
  B01 DE 1.84 DE LCh -0.39 -0.75 -1.64 (strong orange)
  B06 DE 1.89 DE LCh -0.91 -1.48 -0.76 (light strong orange)
  C03 DE 2.33 DE LCh +1.83 -1.14 -0.87 (strong red)
  C05 DE 2.60 DE LCh +1.91 -1.22 +1.28 (purple-red)
  B05 DE 2.67 DE LCh -1.13 -2.25 +0.90 (light strong yellow-green)
  C06 DE 2.73 DE LCh +2.19 -0.85 +1.37 (blue)
  C04 DE 2.88 DE LCh -0.78 -2.75 -0.35 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
