<pre>
Camera: Nikon D3
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
  D03 DE 0.11 DE LCh -0.02 -0.09 -0.07 (gray 70%)
  D04 DE 0.12 DE LCh -0.02 -0.01 -0.12 (gray 50%)
  D06 DE 0.13 DE LCh +0.00 -0.13 +0.01 (gray 20%)
  D05 DE 0.17 DE LCh -0.02 -0.06 -0.16 (gray 40%)
  A01 DE 0.38 DE LCh -0.01 +0.21 +0.32 (dark brown)
  A03 DE 0.48 DE LCh +0.19 -0.39 -0.38 (purple-blue)
  A05 DE 0.48 DE LCh +0.12 -0.41 +0.10 (purple-blue)
  B02 DE 0.53 DE LCh -0.28 -0.37 -0.69 (purple-blue)
  B06 DE 0.56 DE LCh -0.46 -0.29 +0.11 (light strong orange)
  C01 DE 0.56 DE LCh +0.18 -0.64 -0.81 (dark purple-blue)
  B03 DE 0.67 DE LCh +0.52 +0.16 -0.39 (red)
  D01 DE 0.73 DE LCh -0.12 -0.69 -0.21 (white)
  A04 DE 0.75 DE LCh +0.07 +0.71 -0.21 (yellow-green)
  B05 DE 1.09 DE LCh +0.06 -0.95 +0.52 (light strong yellow-green)
  A06 DE 1.14 DE LCh +0.61 -0.51 +0.82 (light cyan)
  C02 DE 1.14 DE LCh +0.82 -0.75 +0.22 (yellow-green)
  A02 DE 1.16 DE LCh +0.54 -0.08 -1.02 (red)
  C05 DE 1.20 DE LCh +0.56 -0.35 +1.00 (purple-red)
  B04 DE 1.29 DE LCh -0.11 -1.14 +0.56 (dark purple)
  C03 DE 1.35 DE LCh +1.25 -0.44 -0.28 (strong red)
  C04 DE 1.38 DE LCh -0.07 -1.37 -0.04 (light vivid yellow)
  B01 DE 1.65 DE LCh -0.36 -0.33 -1.57 (strong orange)
  C06 DE 2.14 DE LCh +1.48 -0.64 +1.39 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
