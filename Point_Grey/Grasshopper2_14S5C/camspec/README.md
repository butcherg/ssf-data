<pre>
Camera: Point Grey Grasshopper2 14S5C
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
  D06 DE 0.12 DE LCh +0.01 +0.12 +0.04 (gray 20%)
  D05 DE 0.23 DE LCh -0.03 +0.14 -0.18 (gray 40%)
  D03 DE 0.26 DE LCh -0.03 +0.12 -0.22 (gray 70%)
  D04 DE 0.29 DE LCh -0.04 +0.26 -0.13 (gray 50%)
  D01 DE 0.81 DE LCh -0.20 -0.67 -0.42 (white)
  A05 DE 0.86 DE LCh +0.41 -0.25 +0.60 (purple-blue)
  A03 DE 0.92 DE LCh +0.13 -0.48 +0.62 (purple-blue)
  C01 DE 0.92 DE LCh -0.53 -0.83 -0.11 (dark purple-blue)
  B04 DE 1.05 DE LCh +0.83 -0.14 +0.61 (dark purple)
  B03 DE 1.07 DE LCh +0.74 -0.20 -0.75 (red)
  A04 DE 1.17 DE LCh +0.27 +0.10 -1.14 (yellow-green)
  A06 DE 1.19 DE LCh +0.44 -0.73 +0.83 (light cyan)
  A01 DE 1.27 DE LCh +0.18 +0.19 +1.24 (dark brown)
  A02 DE 1.48 DE LCh +0.54 -0.02 -1.38 (red)
  C06 DE 1.69 DE LCh +0.97 -0.28 +1.35 (blue)
  B06 DE 1.75 DE LCh -0.06 -0.59 +1.64 (light strong orange)
  B02 DE 1.80 DE LCh -0.20 -0.83 +1.06 (purple-blue)
  B05 DE 2.01 DE LCh +0.14 -1.87 +0.73 (light strong yellow-green)
  B01 DE 2.03 DE LCh -0.26 -1.16 +1.65 (strong orange)
  C05 DE 2.33 DE LCh +1.75 -0.04 +1.55 (purple-red)
  C02 DE 2.52 DE LCh +0.64 -2.41 +0.32 (yellow-green)
  C04 DE 2.72 DE LCh +0.21 -2.33 +1.39 (light vivid yellow)
  C03 DE 3.49 DE LCh +2.81 +0.15 -2.08 (strong red)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
