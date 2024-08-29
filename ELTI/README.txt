###################### README ######################

"""
Aspro2 simulation with extended E/VLTI baselines, including VISTA+VISTA and VISTA+ELT.
bourdarot@mpe.mpg.de

2024-03-23  	TS, Added to readme
2024-03-02	GB, added readme
2023-12-17	GB, created

"""

# Run Aspro2 with E/VLTI

- Run aspro2:
java -jar -Daspro.expertMode=true Aspro2-24.xx.y.jar

- Open 'Edit'-->'Configuration Manager' and load the EVLTI.xml file


GPS, relative coordinates:
VISTA,  X=655.685, Y=751.54, Z=1149.83
ELT, X=1877.47, Y=21612.68, Z=3814.78
E1 (extension 1, water tank 1), X=84.84, Y=1033.22, Z=-23.92 (24°37'40.9"S 70°23'40.4"W)
E2 (extension 2, water tank 2), X=-119.70, Y=1969.50, Z=-541.74 (24°37'57.0"S 70°23'08.1"W)



# Remarks on Aspro2:
- existing interferometer configurations are in:
aspro-conf/src/main/resources/fr/jmmc/aspro/model/

- contributed configurations:
https://github.com/JMMC-OpenDev/aspro-conf-contrib/

- management of configuration and associated documentation:
http://apps.jmmc.fr/~swmgr/AsproOIConfigurations/
http://apps.jmmc.fr/~swmgr/xsddoc/aspro-oi/0.1/html/


#############################################################################

