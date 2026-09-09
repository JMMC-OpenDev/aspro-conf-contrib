###################### README ######################

"""
Aspro2 support for the XUYI interferometer (Chile-China collaboration).

Requested by mhadjara at uchile.cl :

During our participation in the SPIE Astronomical Telescopes + Instrumentation 2026 conference, held in Copenhagen (Denmark) from July 5–10, 2026, we presented the latest developments of our first long-baseline optical interferometer in China, entitled: "XuYi’s Interferometer Observation Simulator"
...
Our colleague Dr. Ferréol Soulez (CRAL, in copy) kindly suggested that we contact you regarding the possibility of implementing the XuYi interferometer configuration within the JMMC ASPRO2 software.

Would you be willing to help us with this integration? If so, please let me know, and I will promptly provide all the necessary information and technical parameters required for this purpose.
We would greatly appreciate your support and expertise, and we look forward to your feedback.

Thank you very much in advance.

Best regards,
Massinissa Hadjara,
on behalf of all members of the Chile–China Optical Interferometry Team.

---

I will share with you the geocentric XYZ coordinates of the interferometer and its fixed stations (T1, T2, and T3) as soon as possible. Our team will carry out new and more accurate GPS measurements this week.

In the meantime, I am sharing with you the previous GPS data that I used in our work in China. These were the coordinates I used in our own code, which follows an approach similar to that implemented in ASPRO2 but for our interferometer.

The coordinates I previously had and used were the following:
Telescope	Latitude (°)	Longitude (°)	Altitude (m)
T1	32.736786	118.464223	178
T2	32.736918	118.463593	178
T3	32.736301	118.464372	178

From these coordinates, I was able to derive the barycentre of the three stations:
[[image.png]]

and subsequently implement the XuYi Interferometer Observation Simulator (XIOS).

The final SPIE 2026 paper can be accessed here:
https://spie.org/submissions/approval/manuscript/46fce53a-e9da-4cfd-a750-187b569903ea.pdf

The corresponding poster is available here:
https://www.spiedigitallibrary.org/posterpreview/d62d8bd2-2ccf-f011-a9ae-00505691c5e1

I will send you the updated and more accurate coordinates as soon as they become available.

Thank you very much in advance.

Best regards,
Massinissa.
"""

# Run Aspro2 with custom config:
- Open 'Edit'-->'Configuration Manager' and load this xml file



# Remarks on Aspro2:
- existing interferometer configurations are in:
https://github.com/JMMC-OpenDev/aspro-conf/tree/master/src/main/resources/fr/jmmc/aspro/model/

- contributed configurations:
https://github.com/JMMC-OpenDev/aspro-conf-contrib/

- management of configuration and associated documentation:
http://apps.jmmc.fr/~swmgr/AsproOIConfigurations/
http://apps.jmmc.fr/~swmgr/xsddoc/aspro-oi/0.1/html/


#############################################################################

