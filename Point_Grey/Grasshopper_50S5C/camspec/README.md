<pre>
Camera: Point Grey Grasshopper 50S5C
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
  D06 DE 0.23 DE LCh +0.01 +0.12 +0.20 (gray 20%)
  D05 DE 0.77 DE LCh -0.02 +0.30 -0.71 (gray 40%)
  D03 DE 0.81 DE LCh -0.02 +0.49 -0.65 (gray 70%)
  A05 DE 0.92 DE LCh +0.57 -0.24 +0.58 (purple-blue)
  D04 DE 0.96 DE LCh -0.03 +0.74 -0.60 (gray 50%)
  A06 DE 1.22 DE LCh -0.47 -0.74 +0.85 (light cyan)
  C01 DE 1.24 DE LCh +0.50 -0.47 -1.46 (dark purple-blue)
  A03 DE 1.30 DE LCh -0.07 -0.94 +0.60 (purple-blue)
  C06 DE 1.50 DE LCh -0.58 -0.28 +1.35 (blue)
  D01 DE 1.61 DE LCh -0.22 -1.11 -1.14 (white)
  B02 DE 1.90 DE LCh +0.54 -2.51 -0.95 (purple-blue)
  B03 DE 2.11 DE LCh +1.41 +0.44 -1.51 (red)
  B04 DE 2.16 DE LCh +2.06 -0.14 +0.62 (dark purple)
  A02 DE 2.18 DE LCh +0.53 -0.17 -2.10 (red)
  C02 DE 2.52 DE LCh -0.71 -2.39 +0.34 (yellow-green)
  A01 DE 2.55 DE LCh +0.44 +0.68 +2.42 (dark brown)
  A04 DE 2.91 DE LCh -0.20 -0.58 -2.85 (yellow-green)
  B05 DE 3.06 DE LCh -0.34 -3.02 -0.30 (light strong yellow-green)
  B01 DE 3.10 DE LCh +1.36 -1.51 +2.35 (strong orange)
  B06 DE 3.16 DE LCh +1.03 -2.04 +2.19 (light strong orange)
  C03 DE 3.37 DE LCh +2.68 +0.15 -2.05 (strong red)
  C05 DE 4.61 DE LCh +4.34 -0.03 +1.57 (purple-red)
  C04 DE 4.70 DE LCh +0.47 -4.42 -1.53 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
