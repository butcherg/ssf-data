<pre>
Camera: Canon 300D
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
  D05 DE 0.09 DE LCh -0.02 +0.06 +0.07 (gray 40%)
  D03 DE 0.10 DE LCh -0.02 +0.08 +0.05 (gray 70%)
  D06 DE 0.12 DE LCh +0.00 +0.12 -0.02 (gray 20%)
  D04 DE 0.13 DE LCh -0.03 +0.05 +0.12 (gray 50%)
  A01 DE 0.32 DE LCh -0.00 +0.30 +0.09 (dark brown)
  D01 DE 0.48 DE LCh -0.14 -0.45 +0.07 (white)
  A03 DE 0.65 DE LCh +0.42 -0.45 -0.41 (purple-blue)
  B02 DE 0.75 DE LCh +0.45 -1.00 -0.66 (purple-blue)
  C01 DE 0.88 DE LCh +0.42 -1.19 -0.87 (dark purple-blue)
  A05 DE 0.90 DE LCh +0.53 -0.69 +0.08 (purple-blue)
  A04 DE 0.95 DE LCh -0.35 +0.89 -0.05 (yellow-green)
  A06 DE 0.96 DE LCh +0.40 -0.32 +0.82 (light cyan)
  A02 DE 1.11 DE LCh +0.53 -0.32 -0.93 (red)
  B04 DE 1.15 DE LCh +0.24 -0.96 +0.54 (dark purple)
  B03 DE 1.22 DE LCh +0.74 -0.57 -0.79 (red)
  B06 DE 1.38 DE LCh -0.47 -1.11 -0.68 (light strong orange)
  C02 DE 1.44 DE LCh +0.20 -1.04 +0.97 (yellow-green)
  C05 DE 1.47 DE LCh +1.15 -0.74 +0.53 (purple-red)
  B05 DE 1.81 DE LCh -0.56 -1.61 +0.64 (light strong yellow-green)
  B01 DE 1.83 DE LCh -0.29 -0.73 -1.66 (strong orange)
  C06 DE 1.95 DE LCh +1.66 -0.57 +0.82 (blue)
  C03 DE 2.19 DE LCh +1.57 -1.11 -1.05 (strong red)
  C04 DE 2.58 DE LCh -0.27 -2.54 -0.36 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)

