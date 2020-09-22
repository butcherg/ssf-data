<pre>
Camera: Sony NEX-5N
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
  D05 DE 0.05 DE LCh -0.00 +0.00 +0.05 (gray 40%)
  D03 DE 0.08 DE LCh -0.01 +0.05 +0.06 (gray 70%)
  D06 DE 0.08 DE LCh +0.02 +0.08 +0.02 (gray 20%)
  D04 DE 0.09 DE LCh -0.02 +0.00 +0.09 (gray 50%)
  A01 DE 0.31 DE LCh -0.07 +0.16 -0.25 (dark brown)
  D01 DE 0.38 DE LCh -0.12 -0.31 +0.17 (white)
  A06 DE 0.75 DE LCh +0.19 -0.33 +0.65 (light cyan)
  A02 DE 1.07 DE LCh +0.57 -0.26 -0.87 (red)
  A04 DE 1.07 DE LCh -0.95 +0.50 +0.07 (yellow-green)
  A03 DE 1.34 DE LCh +1.09 -0.83 -0.33 (purple-blue)
  B03 DE 1.47 DE LCh +1.26 -0.70 -0.28 (red)
  C02 DE 1.49 DE LCh -0.61 -1.12 +0.78 (yellow-green)
  B04 DE 1.72 DE LCh +1.10 -1.11 +0.66 (dark purple)
  A05 DE 1.78 DE LCh +1.36 -1.08 +0.11 (purple-blue)
  B01 DE 1.91 DE LCh -0.56 -0.67 -1.70 (strong orange)
  B06 DE 2.14 DE LCh -1.20 -1.42 -1.06 (light strong orange)
  B02 DE 2.34 DE LCh +2.08 -1.64 -0.79 (purple-blue)
  C01 DE 2.40 DE LCh +2.10 -1.81 -1.50 (dark purple-blue)
  C03 DE 2.41 DE LCh +1.89 -1.49 -0.16 (strong red)
  B05 DE 2.63 DE LCh -1.50 -2.00 +0.78 (light strong yellow-green)
  C06 DE 2.72 DE LCh +2.40 -1.20 +0.40 (blue)
  C05 DE 2.79 DE LCh +2.30 -1.39 +0.73 (purple-red)
  C04 DE 2.88 DE LCh -1.13 -2.61 -0.43 (light vivid yellow)
</pre>

(Data reported during the construction of the LUT ICC with dcamprof)
