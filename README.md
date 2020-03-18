# ALCD

<img  title="ALCD Cloud mask mosaic" src="http://www.cesbio.ups-tlse.fr/multitemp/wp-content/uploads/2019/02/mosaique.jpg" width="300"  /> 
The Active Learning for Cloud Detection (ALCD) software enables to generate reference cloud masks which may be used to validate operational cloud masks, such as those generated by MAJA. The reference cloud masks are generated interactively using an iterative active learning procedure which enables to generate an accurate reference cloud mask in less than two hours. 
The chain may be used also for other land cover classifications, as weel as single images classifications. Improvements on finer resolution and processing optimisations have been implemented by the assesment team for a water surface chain.

The tool was written by Louis Baetens during a training period at CESBIO, funded by CNES, under supervision of Olivier Hagolle. The tool led to a publication which is provided as a reference.

ALCD is written python(v3). To run ALCD, you will need to install the [Orfeo Toolbox](https://www.orfeo-toolbox.org/) and the selection of samples relies on QGIS. A detailed [user manual](https://github.com/CNES/ALCD/blob/master/ALCD_user_manual.pdf) for ALCD is available. 

Reference :
[Baetens, L.; Desjardins, C.; Hagolle, O. Validation of Copernicus Sentinel-2 Cloud Masks Obtained from MAJA, Sen2Cor, and FMask Processors Using Reference Cloud Masks Generated with a Supervised Active Learning Procedure. Remote Sens. 2019, 11, 433.](https://www.mdpi.com/2072-4292/11/4/433)
