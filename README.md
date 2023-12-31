# Undergraduate Astrophysics Thesis
by Jessica Syafaq Muthmaina
## The Implementation of Allan Standard Deviation Technique in Variability Analysis of 4C31.61 Quasar Position Based On Geodetic VLBI Data
### Abstract
Quasars are one of the extra-galactic objects that have diverse applications in the fields of astronomy and astrophysics. Quasars serve as celestial reference frames, allowing for the determination of the positions of celestial objects. The stability of a quasar's position is a prerequisite for it to be used as a reference point. This study aims to analyze the stability of the position of a quasar known as 4C31.61 (2201+315). The position of the quasar object 4C31.61 (2201+315) is obtained through the processing of Very-Long Baseline Interferometry (VLBI) observations, which is a technique used in radio astronomy. The data used spans from 1990 to 2023. The VLBI observation results are further analyzed using the Vienna VLBI Software (VieVS). The stability of the quasar's position is examined using a statistical technique called the Allan standard deviation. Based on the Allan standard deviation analysis, the quasar 4C31.61 (2201+315) exhibits a stable position with a predominance of white noise across almost all time scales. This quasar can then be classified as an AV0-type quasar, which is the most stable type of quasar.
### Research Objective
This research is conducted to fulfill the following objectives:
1. To obtain the position of the quasar object 4C31.61 (2201+315) over a long time span (1990-2023) using VLBI observation data.
2. To determine the utility of the Allan deviation method in analyzing the variations in the position of the quasar object 4C31.61 (2201+315).
### Allantools
Allantools is a Python-based computational tool for calculating Allan deviation and related time and frequency statistics (Wallin et al., 2018). It requires input data with equal spacing between observation points, and can handle fractional frequency or phase in seconds. Allantools also offers noise generators for creating synthetic data sets, useful for simulations or algorithm testing.

In VLBI observations, Allan deviation and related statistics play a crucial role in data analysis. Allantools facilitates this analysis by providing the necessary functions. This study specifically uses the overlapping Allan deviation method, which efficiently measures Allan deviation based on overlap (Riley and Howe, 2008).
### Result and Discussion
In this study, the quasar object 4C31.61 (2201+315) has been successfully observed using VLBI (Very Long Baseline Interferometry) from 1990 to 2023. The observation results were further processed using the MATLAB-based VieVS software to determine the position of the quasar object 4C31.61 (2201+315). Additionally, this research also utilized positional data of the quasar object 4C31.61 (2201+315) from the Paris Observatory VLBI Center. Furthermore, computational calculations using the Allan variance method were performed to analyze the stability level of the quasar's position. Correlation analysis was also conducted between the Allan variance values and related physical phenomena.
#### Comparison of VieVS Data Set and Paris Observatory VLBI Center
The comparison between VieVS and Paris Observatory VLBI Center data for quasar 4C31.61 (2201+315) from 1990 to 2023 shows discrepancies. The VieVS data has gaps, especially around 2006-2014 due to processing issues. Redoing the data processing may cause research schedule delays. While using VieVS software has advantages in independent data production, it also has shortcomings like lower accuracy and the presence of outliers, requiring moving average techniques to handle non-uniform time steps for calculating Allan standard deviation.

#### Calculation of Allan Variance and Result Analysis
The Allan standard deviation calculation was performed using Allantools to analyze position fluctuations in quasars from 1990 to 2023. Outliers were removed, and a moving average process was applied before the Allan deviation computation. The results showed dominant white noise, indicating stable positions, for most quasars.

Gattano et al. (2018) categorized quasars into AV0, AV1, and AV2 based on noise patterns. AV0 represents stable positions, AV1 shows moderate stability, and AV2 indicates the most unstable behavior.

The position variability observed in quasars could be attributed to ejections from the quasar nucleus or the presence of Binary Black Holes (BBH). However, the dominance of white noise suggests other sources may contribute as well. Further research is needed to validate these hypotheses and understand the relationship between quasar position variability, its causes, and white noise observed in the Allan deviation.
### Conclusion
Based on the research and discussion conducted, the following conclusions can be drawn:

1. The position of the quasar object 4C31.61 (2201+315) has been determined by processing Very Long Baseline Interferometry (VLBI) observations, especially for data spanning from 1990 to 2023. The obtained quasar position using the Vie-VS software is quite similar to that obtained from the Paris Observatory dataset, despite having lower accuracy. The data includes important information such as the right ascension of 330.8123990589822° and the declination of 31.7606305185240°.
2. The Allan variance technique can be used to analyze the stability of the quasar object 4C31.61 (2201+315). Quasar 4C31.61 (2201+315) exhibits a stable position with dominant noise of white noise type. This quasar can be categorized as an AV0-type quasar.
