<pre>
Camera: Nikon D300s
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
  D06 DE 0.08 DE LCh +0.00 -0.08 +0.01 (gray 20%)
  D03 DE 0.09 DE LCh -0.01 -0.07 -0.05 (gray 70%)
  D04 DE 0.10 DE LCh -0.02 -0.01 -0.10 (gray 50%)
  D05 DE 0.15 DE LCh -0.01 -0.05 -0.14 (gray 40%)
  A03 DE 0.55 DE LCh +0.24 -0.46 -0.41 (purple-blue)
  B02 DE 0.58 DE LCh -0.08 -0.72 -0.99 (purple-blue)
  A05 DE 0.61 DE LCh +0.20 -0.56 +0.04 (purple-blue)
  D01 DE 0.64 DE LCh -0.11 -0.61 -0.17 (white)
  A01 DE 0.72 DE LCh +0.01 +0.38 +0.61 (dark brown)
  A04 DE 0.88 DE LCh +0.02 +0.87 -0.05 (yellow-green)
  C01 DE 0.95 DE LCh +0.43 -1.14 -1.29 (dark purple-blue)
  B03 DE 0.99 DE LCh +0.63 +0.17 -0.74 (red)
  A06 DE 1.00 DE LCh +0.46 -0.22 +0.86 (light cyan)
  A02 DE 1.22 DE LCh +0.49 +0.16 -1.11 (red)
  B04 DE 1.29 DE LCh +0.02 -1.15 +0.54 (dark purple)
  B06 DE 1.29 DE LCh -0.30 -1.22 -0.29 (light strong orange)
  C05 DE 1.29 DE LCh +0.74 -0.38 +0.98 (purple-red)
  B01 DE 1.65 DE LCh -0.17 -0.55 -1.55 (strong orange)
  C02 DE 1.65 DE LCh +0.61 -1.26 +0.87 (yellow-green)
  B05 DE 1.82 DE LCh -0.09 -1.60 +0.86 (light strong yellow-green)
  C03 DE 1.86 DE LCh +1.28 -0.59 -1.20 (strong red)
  C06 DE 1.95 DE LCh +1.31 -0.41 +1.38 (blue)
  C04 DE 2.52 DE LCh -0.06 -2.51 -0.13 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
