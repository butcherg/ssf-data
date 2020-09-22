<pre>
Camera: Nikon D700
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
  D03 DE 0.11 DE LCh -0.02 -0.08 -0.08 (gray 70%)
  D06 DE 0.11 DE LCh +0.00 -0.11 +0.02 (gray 20%)
  D04 DE 0.13 DE LCh -0.02 -0.01 -0.12 (gray 50%)
  D05 DE 0.17 DE LCh -0.02 -0.05 -0.16 (gray 40%)
  A01 DE 0.41 DE LCh -0.00 +0.30 +0.28 (dark brown)
  A03 DE 0.45 DE LCh +0.19 -0.39 -0.32 (purple-blue)
  B02 DE 0.52 DE LCh -0.22 -0.42 -0.75 (purple-blue)
  A05 DE 0.55 DE LCh +0.15 -0.40 +0.20 (purple-blue)
  D01 DE 0.69 DE LCh -0.12 -0.65 -0.20 (white)
  B03 DE 0.70 DE LCh +0.49 +0.19 -0.46 (red)
  A04 DE 0.71 DE LCh +0.05 +0.67 -0.24 (yellow-green)
  C01 DE 0.71 DE LCh +0.22 -0.72 -1.03 (dark purple-blue)
  B06 DE 0.73 DE LCh -0.44 -0.57 -0.14 (light strong orange)
  B05 DE 1.02 DE LCh +0.04 -0.91 +0.45 (light strong yellow-green)
  B04 DE 1.10 DE LCh -0.05 -0.88 +0.63 (dark purple)
  C02 DE 1.11 DE LCh +0.75 -0.80 +0.15 (yellow-green)
  A06 DE 1.14 DE LCh +0.58 -0.56 +0.80 (light cyan)
  A02 DE 1.15 DE LCh +0.52 +0.11 -1.02 (red)
  C05 DE 1.16 DE LCh +0.58 -0.23 +0.98 (purple-red)
  C03 DE 1.35 DE LCh +1.24 -0.34 -0.43 (strong red)
  C04 DE 1.47 DE LCh -0.08 -1.46 -0.12 (light vivid yellow)
  B01 DE 1.55 DE LCh -0.35 -0.32 -1.47 (strong orange)
  C06 DE 2.12 DE LCh +1.43 -0.69 +1.38 (blue)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
