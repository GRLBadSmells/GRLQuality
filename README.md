# This repository contains an extension to jUCMNav Eclipse plugin. It contains a set of OCL rules.

*Important notes:

(1) This tool works on GRL models created with jUCMNav tool. Therefore, jUCMNav plugin needs to be installed before downloading and using this extension

(2) This extension is developed and tested on Eclipse neon.3 (4.6.3)

(3) This extension is a beta version

*Installation Instructions:

(1) Download GRLBSModelCheckingOCLRules file from this repository to your machine

(2) Expand the downloaded RAR. It contains an XML file

(3) Go to Window Menu -> Preferences -> jUCMNav -> static semantics checking preferences analysis

(4) Click on "import" button to import the download XML file.

(5) The downloaded file will be imported as a list of bad smells grouped under the "Imported" category

*Usage Guide

(1) OGo to Window Menu -> Preferences -> jUCMNav -> static semantics checking preferences analysis

(2) Expand the "Imported" category

(3) Select the bad smells that needed to be detected and close window

(4) open the GRL model that is needed to be investigated

(5) Go to Eclipse menu bar -> jUCMNav menu -> Verify static semantics

(6) The detected instances of bad smells will be reported to the problems view in Eclipse framework
