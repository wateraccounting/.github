## Hi there 👋

Welcome to the github page of the Water Accounting and Water Productivity team at [IHE Delft Institute for Water Education](https://www.un-ihe.org/)! 

This github page contains several repositories for analyses at river basin scale (Water Accounting Plus) and for agricultural areas (Water Productivity). We also provide tools for downloading various datasets, including scripts for downloading data from the FAO portal to monitor water productivity through open access of remotely sensed derived data ([WaPOR](https://wapor.apps.fao.org/home/WAPOR_2/1))

**Water Accounting Plus**

The water accounting team at IHE Delft was established in 2014 and has been working with the Food and Agricultural Organisation of the United Nations (FAO) and the International Water Management Institute (IWMI) to develop the Water Accounting Plus framework and supporting tools. Water Accounting Plus is a water accounting framework using global-scale, public domain datasets with a strong focus on satellite-based remote sensing data. In addition to providing spatially explicit data, it allows users to overcome a lack of data or poor data quality at the local level. The WA+ framework uses fact sheets, which provide systematic overview of different aspects of water accounting, focusing on the following elements: resource base; evapotranspiration; agricultural services; utilized flow; surface water; groundwater; ecosystem services and sustainability. The underlying (spatial) data for these factsheets can be used to visualize spatial and temporal trends through graphs and maps. The WA+ framework is supported by the development of open-source Python scripts to automatically compile data from multiple sources to produce water accounting indicators and factsheets.
![image](https://wateraccounting.un-ihe.org/sites/wateraccounting.un-ihe.org/files/waframework.png)
 
The following repositories are available to support the development of water accounts: IHEWACollect repository provides support to downloading relevant remote sensing data sets, the [IHEWAEngine](https://github.com/wateraccounting/IHEWAEngine) repository provides scripts for calculating soil water balance at pixel scale using the remote sensing products, and the [WA_Hyperloop](https://github.com/wateraccounting/WA_Hyperloop) repository provides the scripts to translate the data into the typical WA+ sheets. 

**Water Productivity**

Availability of periodical data from satellites globally in the public domain has increased the opportunities to develop monitoring systems for agricultural water management. Recent advances in remote sensing techniques to extract indicators like water productivity has been developed as a reliable source of information to support decision making. Toward this, a platform called FAO portal to monitor Water Productivity through Open access of Remotely sensed derived data (WaPOR) was launched offering derived products from satellite data explicitly for monitoring water use, biomass and water productivity covering Africa and Near East. The water productivity assessment is increasingly benefiting from the near-real time RS datasets. At IHE Delft, the RS based water productivity assessment are conducted for multiple projects and contribute towards research in developing practical workflows for multi-scalar assessments.

![image](https://github.com/wateraccounting/WAPORWP/blob/master/ReadmeIMG/Figmd_1.png)
 
Two open source libraries ([WaPORWP](https://github.com/wateraccounting/WAPORWP) and [PySEBAL](https://github.com/wateraccounting/pySEBAL_dev)) for assessing RS based water productivity and related performance indicators are available to facilitate further uptake of these approaches. The Python library WaPORWP is a collection of scripts to execute standard protocol developed by IHE Delft for assessing spatiotemporal land and water productivity and other irrigation performance indicators using the FAO WaPOR data ([Chukalla et al., 2022](https://hess.copernicus.org/articles/26/2759/2022/)). [PySEBAL](https://github.com/wateraccounting/pySEBAL_dev) is a python library developed in IHE Delft which computes water use and biomass production based on surface energy balance model and subsequently compute seasonal water productivity.

**Open access and remote sensing derived data**

IHE Delft developed an open source library for downloading various open access remote sensing datasets [IHEWACollect](https://github.com/wateraccounting/IHEWACollect). Scripts for downloading WaPOR data sets are integrated in the [WaPOROCW](https://github.com/wateraccounting/WAPOROCW), [WaPORWP](https://github.com/wateraccounting/WAPORWP) and [WaPORWA](https://github.com/wateraccounting/WAPORWA) repositories. 

**Capacity building**

IHE Delft Institute for Water Education (IHE Delft) and the Food and Agriculture Organization of the United Nations (FAO) developed an open online course titled “Water Productivity and Water Accounting using WaPOR”, which is available in three languages [English](https://ocw.un-ihe.org/course/view.php?id=92), [French](https://ocw.un-ihe.org/course/view.php?id=117) and [Arabic](https://ocw.un-ihe.org/course/view.php?id=118).
The jupyternotebooks for this open online course are compiled in the [WaPOROCW](https://github.com/wateraccounting/WAPOROCW) repository

More information can be found on our [webpage](https://wateraccounting.un-ihe.org/)
