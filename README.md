# Nheengatu

"Nheengatu" is a tupi-guarani (language from brazilian indians) word and means "good language"/"easy language".

In this project, a set of libraries to communicate with LabVIEW VIs running on the Compact RIO 9035/9045 from applications
running on the LinuxRT user space were developed. Furthermore, EPICS device support to communicate with these libraries was
also developed. The developed device support together with the devised libraries allow access to Compact RIO VI variables 
whether implemented on the FPGA, or on LinuxRT as a LabVIEW-RT VI. Other helper projects such as setting up a clean compactRIO
and configuration generation scripts were also developed.

## Core repositories

* [crio-labview](https://gitlab.cnpem.br/SOL/LabViewRT/crio-linux-labview)
* [crio-linux-libs](https://gitlab.cnpem.br/SOL/Projetos/crio-linux-libs)
* [crio-epics-dev-sup](https://gitlab.cnpem.br/SOL/EpicsApps/crio-linux/crio-dev-sup)
* [crio-epics-ioc](https://gitlab.cnpem.br/SOL/EpicsApps/crio-linux/crio-ioc.git) 
* [ni-fpga-helper](https://gitlab.cnpem.br/SOL/CRIO/ni-fpga-helper)
* [Autogeneration Scripts](https://gitlab.cnpem.br/SOL/CRIO/crio-utils.git)

## Supporting repositories

* [CRIO first setup](https://gitlab.cnpem.br/SOL/Projetos/crio-first-setup)
* [NFS setup on CRIO](https://gitlab.cnpem.br/SOL/Network/nfs-epics-scripts)
* [CRIO development Container](https://gitlab.cnpem.br/SOL/Docker/dev-crio.git)
* [CRIO compiled libs](https://gitlab.cnpem.br/SOL/CRIO/crio-compiled-libs)
* [Nheengatu beta tests](https://gitlab.cnpem.br/SOL/CRIO/nheengatu-beta-tests.git)