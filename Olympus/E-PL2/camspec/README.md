<pre>
Camera: Olympus E-PL2
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
  D03 DE 0.05 DE LCh -0.02 +0.03 -0.03 (gray 70%)
  D04 DE 0.06 DE LCh -0.03 +0.05 +0.00 (gray 50%)
  D05 DE 0.06 DE LCh -0.02 +0.03 -0.04 (gray 40%)
  D06 DE 0.06 DE LCh -0.00 +0.06 -0.01 (gray 20%)
  A04 DE 0.43 DE LCh +0.04 +0.35 -0.24 (yellow-green)
  A03 DE 0.48 DE LCh +0.23 -0.46 -0.11 (purple-blue)
  A01 DE 0.62 DE LCh -0.03 +0.12 +0.61 (dark brown)
  D01 DE 0.62 DE LCh -0.16 -0.59 -0.07 (white)
  A05 DE 0.74 DE LCh +0.20 -0.55 +0.27 (purple-blue)
  B02 DE 0.84 DE LCh -0.25 -0.76 -1.30 (purple-blue)
  B04 DE 1.02 DE LCh -0.02 -0.90 +0.45 (dark purple)
  C01 DE 1.04 DE LCh -0.36 -0.77 -1.43 (dark purple-blue)
  A02 DE 1.24 DE LCh +0.55 +0.17 -1.10 (red)
  A06 DE 1.24 DE LCh +0.55 -0.73 +0.84 (light cyan)
  B03 DE 1.25 DE LCh +0.86 +0.54 -0.74 (red)
  C02 DE 1.69 DE LCh +0.68 -1.42 +0.62 (yellow-green)
  C05 DE 1.80 DE LCh +1.29 +0.03 +1.25 (purple-red)
  B01 DE 2.12 DE LCh +0.11 -1.31 -1.66 (strong orange)
  C06 DE 2.21 DE LCh +1.53 -0.80 +1.35 (blue)
  B06 DE 2.27 DE LCh -0.09 -2.24 -0.31 (light strong orange)
  B05 DE 2.44 DE LCh -0.10 -2.17 +1.11 (light strong yellow-green)
  C03 DE 2.71 DE LCh +2.33 +0.03 -1.37 (strong red)
  C04 DE 3.27 DE LCh +0.11 -3.26 -0.15 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
