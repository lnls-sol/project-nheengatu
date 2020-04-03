# Nheengatu

"Nheengatu" is a tupi-guarani (language from brazilian indians) word and means "good language"/"easy language".

In this project, a set of libraries to communicate with LabVIEW VIs running on the Compact RIO ( tested versions are 9035/9045 ) from applications
running on the LinuxRT user space were developed. Furthermore, EPICS device support to communicate with these libraries was
also developed. The developed device support together with the devised libraries allow access to Compact RIO VI variables 
whether implemented on the FPGA, or on LinuxRT as a LabVIEW-RT VI. Other helper projects such as setting up a clean compactRIO
and configuration generation scripts were also developed.

## Core repositories

* [crio-labview](https://github.com/lnls-sol/nheengatu-labview.git)
* [crio-linux-libs](https://github.com/lnls-sol/nheengatu-linuxlibs.git)
* [crio-epics-dev-sup](https://github.com/lnls-sol/nheengatu-devsup.git)
* [crio-epics-ioc](https://github.com/lnls-sol/nheengatu-ioc.git) 
* [ni-fpga-helper](https://github.com/lnls-sol/nheengatu-nifpga.git)
* [Autogeneration Scripts](https://github.com/lnls-sol/nheengatu-autogenscripts.git)
* [CRIO first setup](https://github.com/lnls-sol/nheengatu-criofirstsetup.git)
