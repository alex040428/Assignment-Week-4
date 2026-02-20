# GEOL0069_Week4

## Getting Started

The Week 4 assignment for GEOL0069 Artificial Intelligence for Earth Observation focuses on applying unsupervised learning to a real Earth-observation problem: classifying Sentinel-3 SAR altimetry echoes over polar regions. Each radar measurement contains a returned “echo” (waveform) whose shape depends on surface type. In sea-ice zones, echoes can come from sea ice or from leads .  

In this project, I extract a small set of waveform-derived features (including backscatter strength and shape descriptors), then use clustering to separate echoes into two groups. I then summarise the two classes by computing an mean echo shape and a standard deviation envelope. Finally, I evaluate how well the unsupervised clusters match the ESA official classification using a confusion matrix. 

<p align="right">(<a href="#geol0069_week4">back to top</a>)</p>

