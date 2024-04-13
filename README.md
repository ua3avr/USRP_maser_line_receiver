USRP maser line receiver is intended for amateur radio astronomy.

Virtual instrument (VI) files were done in LabVIEW 2016. Later versions did not tested, but expected to work.

USRP devices require the UHD drivers preinstalled, see https://files.ettus.com/manual/page_install.html

NI-USRP Configuration Utility is very desirable for device handling, see video https://www.youtube.com/watch?v=Hyo1ZWcO61Y. This utility allows to retrieve or change device ID for succesful work of the receiver.

USRP_RA_molecularLine_monitor_multSamples.vi - contains the receiver itself; Postprocessing_utility_RA_molecularLine_fileSum.vi - the postprocessing utility; Spectrum_data_bundle_Jy_linear.vi - the subVI used by both previous VIs; USRP_line_monitor.cfg - the configuration file for the receiver. Its data are used also by the postprocessing utility. All files must be located in one directory.

