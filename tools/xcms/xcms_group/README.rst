
Changelog/News
--------------

**Version 2.1.0 - 07/02/2017**

- IMPROVEMENT: Add an option to export the peak list at this step without have to wait camara.annotate

- IMPROVEMENT: xcms.group can deal with merged individual data from "xcms.xcmsSet Merger"

- BUGFIX: the default value of "density" -> "Maximum number of groups to identify in a single m/z slice" which was of 5 have been changed to fix with the XMCS default values to 50

**Version 2.0.6 - 06/07/2016**

- UPGRADE: upgrate the xcms version from 1.44.0 to 1.46.0

**Version 2.0.5 04/04/2016**

- TEST: refactoring to pass planemo test using conda dependencies


**Version 2.0.4 - 10/02/2016**

- BUGFIX: better management of errors. Datasets remained green although the process failed

- UPDATE: refactoring of internal management of inputs/outputs

- UPDATE: refactoring to feed the new report tool


**Version 2.0.2 - 02/06/2015**

- IMPROVEMENT: new datatype/dataset formats (rdata.xcms.raw, rdata.xcms.group, rdata.xcms.retcor ...) will facilitate the sequence of tools and so avoid incompatibility errors.

- IMPROVEMENT: parameter labels have changed to facilitate their reading.
