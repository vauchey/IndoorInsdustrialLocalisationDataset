# Main page of dataset of person flows during an assembly phase in an industrial site with an UWB system in NLOS and a motion capture system done by [CESI](https://www.cesi.fr/), [ESIGELEC](https://www.esigelec.fr/) and [SIATECH](https://www.siatech.fr/)
<p align="center">
<img src="Front_view.jpg" width="600">
</p>

 


## Abstract :
<p style="text-align:justify";>
Improving performance and safety conditions at industrial sites remains key elements of the Group's strategy.
Major issues specifically require the ability to dynamically locate people and assets on the site. Currently, the security and regulation of access to areas with different characteristics (types of tasks, level of risk or confidentiality...) are often carried out with badge doors or barriers. These means present several weaknesses in the face of inappropriate movements of people, but also of objects or tools. Also, there is an increasing use of technological devices requiring precise localization in the industrial environment such as AGVs (mobile robots or drones) or augmented reality devices.
It is therefore becoming essential to have tools to dynamically manage these flows of people or goods associated with precise location technologies. An Ultra-Wide-Band solution will be employed to quickly and efficiently identify persons who may find themselves in unauthorized areas or perform tasks for which they are uninstructed.
Besides dynamic people tracking, this solution can overcome problems of moving objects and tools in the production workshops. We propose a new dataset to have information about the displacement of workers and evaluate performance and safety of workers.</p>

## Paper :

Mickael Delamare<sup>1</sup><sup>3</sup>, Fabrice Duval<sup>2</sup>, Remi Boutteau<sup>3</sup>.  

<sup>1</sup>[siatech](https://www.siatech.fr/) , IRSEEM, Rouen, France, Normandie Univ, UNIROUEN, mickael.delamare@siatech.fr   
<sup>2</sup>[LINEACT-CESI](https://lineact.cesi.fr/), LINEACT-CESI, Rouen campus, France, fduval@cesi.fr   
<sup>3</sup>[ESIGELEC](http://www.esigelec.fr/) , IRSEEM, Rouen, France, Normandie Univ, UNIROUEN, boutteau@esigelec.fr



Link : https://www.mdpi.com/1424-8220/20/16/4511

DOI : https://doi.org/10.3390/s20164511

Accepted to the journal Sensors (MDPI)





## Datasets :

Dataset of each position of person.

We provide two modalities : 

-A motion capture system called Mocap with an millimetric accuracy
-An Ultra Wide Band system (The MDEK1001 from Decawave) with a centimeter accuracy.

The dataset is composed of two '.zip' : 

1)  Raw_datas_UWB_Mocap.zip : Raw datas of both UWB and Mocap in the same frame of reference. It contains each person (Rig1 to Rig6).

2) Filtered_datas_UWB.zip : UWB datas filtered.

<p align="center">
<img src="IndoorUWB_Mocap.gif">
</p>

Link : <a href="https://doi.org/10.5281/zenodo.7732563"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.7732563.svg" alt="DOI"></a>

If you use this dataset, please cite us: 

@article{delamare2020new,
  title={A New Dataset of People Flow in an Industrial Site with UWB and Motion Capture Systems},
  author={Delamare, Mickael and Duval, Fabrice and Boutteau, Remi},
  journal={Sensors},
  volume={20},
  number={16},
  pages={4511},
  year={2020},
  publisher={Multidisciplinary Digital Publishing Institute}
}
