<pre>
Camera: Canon 600D
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
  D06 DE 0.08 DE LCh +0.01 -0.07 +0.05 (gray 20%)
  D03 DE 0.12 DE LCh -0.02 -0.06 -0.11 (gray 70%)
  D04 DE 0.15 DE LCh -0.03 -0.04 -0.14 (gray 50%)
  D05 DE 0.16 DE LCh -0.02 -0.04 -0.15 (gray 40%)
  A01 DE 0.29 DE LCh +0.04 +0.29 -0.04 (dark brown)
  A03 DE 0.69 DE LCh +0.47 -0.51 -0.35 (purple-blue)
  C01 DE 0.72 DE LCh +0.45 -0.77 -0.85 (dark purple-blue)
  B02 DE 0.77 DE LCh +0.58 -0.76 -0.40 (purple-blue)
  D01 DE 0.78 DE LCh -0.13 -0.73 -0.25 (white)
  B04 DE 0.82 DE LCh +0.51 -0.14 +0.62 (dark purple)
  A05 DE 1.00 DE LCh +0.69 -0.24 +0.58 (purple-blue)
  B03 DE 1.02 DE LCh +0.87 -0.30 -0.44 (red)
  A06 DE 1.07 DE LCh +0.43 -0.49 +0.84 (light cyan)
  A02 DE 1.20 DE LCh +0.67 -0.45 -0.89 (red)
  A04 DE 1.25 DE LCh -0.56 -0.08 -1.11 (yellow-green)
  C05 DE 1.74 DE LCh +1.45 -0.04 +0.96 (purple-red)
  C02 DE 1.90 DE LCh +0.10 -1.80 +0.61 (yellow-green)
  B01 DE 1.94 DE LCh +0.01 -1.49 -1.25 (strong orange)
  C06 DE 2.07 DE LCh +1.89 -0.49 +0.67 (blue)
  B06 DE 2.35 DE LCh -0.40 -1.98 -1.20 (light strong orange)
  C03 DE 2.62 DE LCh +1.91 -0.22 -1.78 (strong red)
  B05 DE 2.86 DE LCh -0.72 -2.77 +0.14 (light strong yellow-green)
  C04 DE 3.58 DE LCh -0.30 -3.38 -1.16 (light vivid yellow)
  </pre>

(Data reported during the construction of the LUT ICC with dcamprof)

