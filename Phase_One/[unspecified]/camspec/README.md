<pre>
Camera: Phase One (unspecified model)
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
  D06 DE 0.07 DE LCh -0.00 +0.05 -0.06 (gray 20%)
  D05 DE 0.12 DE LCh -0.01 -0.04 +0.11 (gray 40%)
  D03 DE 0.17 DE LCh -0.01 +0.07 +0.16 (gray 70%)
  D04 DE 0.19 DE LCh -0.01 -0.08 +0.17 (gray 50%)
  B02 DE 0.41 DE LCh -0.15 -0.36 +0.02 (purple-blue)
  D01 DE 0.44 DE LCh -0.07 -0.35 +0.26 (white)
  A01 DE 0.55 DE LCh -0.08 +0.51 -0.18 (dark brown)
  A05 DE 0.57 DE LCh +0.01 -0.09 -0.61 (purple-blue)
  A03 DE 0.61 DE LCh +0.15 -0.02 -0.60 (purple-blue)
  A04 DE 1.00 DE LCh -0.14 +0.79 +0.60 (yellow-green)
  A06 DE 1.10 DE LCh +0.45 +0.55 +0.85 (light cyan)
  C01 DE 1.16 DE LCh +0.10 -0.58 +0.66 (dark purple-blue)
  A02 DE 1.24 DE LCh +0.23 -0.98 -0.72 (red)
  B04 DE 1.27 DE LCh -0.32 -1.09 -0.62 (dark purple)
  B03 DE 1.65 DE LCh -0.22 -1.62 -0.13 (red)
  C06 DE 1.78 DE LCh +1.12 +1.17 -0.73 (blue)
  C02 DE 1.90 DE LCh +0.71 -1.05 +1.41 (yellow-green)
  B01 DE 2.10 DE LCh +0.35 -1.24 -1.65 (strong orange)
  C05 DE 2.25 DE LCh -0.39 -1.97 -1.00 (purple-red)
  B06 DE 2.69 DE LCh +0.10 -2.14 -1.64 (light strong orange)
  C03 DE 2.92 DE LCh -0.32 -2.88 +0.36 (strong red)
  B05 DE 3.16 DE LCh -0.13 -3.10 +0.61 (light strong yellow-green)
  C04 DE 3.69 DE LCh +0.12 -3.68 -0.23 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
