<pre>
Camera: Nikon D90
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
  D06 DE 0.09 DE LCh +0.01 -0.09 +0.02 (gray 20%)
  D03 DE 0.10 DE LCh -0.01 -0.08 -0.06 (gray 70%)
  D04 DE 0.11 DE LCh -0.02 -0.01 -0.11 (gray 50%)
  D05 DE 0.16 DE LCh -0.01 -0.05 -0.15 (gray 40%)
  A01 DE 0.56 DE LCh -0.06 +0.39 +0.41 (dark brown)
  D01 DE 0.63 DE LCh -0.11 -0.59 -0.17 (white)
  B02 DE 0.68 DE LCh +0.33 -0.85 -1.04 (purple-blue)
  A03 DE 0.72 DE LCh +0.45 -0.56 -0.41 (purple-blue)
  A04 DE 0.73 DE LCh -0.09 +0.72 -0.08 (yellow-green)
  A05 DE 0.85 DE LCh +0.44 -0.67 +0.12 (purple-blue)
  B03 DE 0.87 DE LCh +0.68 +0.18 -0.51 (red)
  A06 DE 1.08 DE LCh +0.50 -0.49 +0.82 (light cyan)
  A02 DE 1.19 DE LCh +0.48 +0.21 -1.07 (red)
  C01 DE 1.27 DE LCh +0.85 -1.30 -1.43 (dark purple-blue)
  B04 DE 1.32 DE LCh +0.19 -1.14 +0.59 (dark purple)
  B06 DE 1.40 DE LCh -0.57 -1.20 -0.42 (light strong orange)
  C02 DE 1.42 DE LCh +0.49 -1.14 +0.70 (yellow-green)
  C05 DE 1.53 DE LCh +0.99 -0.46 +1.07 (purple-red)
  C03 DE 1.62 DE LCh +1.35 -0.53 -0.71 (strong red)
  B01 DE 1.79 DE LCh -0.39 -0.55 -1.66 (strong orange)
  B05 DE 1.89 DE LCh -0.31 -1.65 +0.87 (light strong yellow-green)
  C06 DE 2.34 DE LCh +1.68 -0.82 +1.39 (blue)
  C04 DE 2.46 DE LCh -0.30 -2.43 -0.22 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
