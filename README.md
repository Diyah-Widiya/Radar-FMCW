# Overview
This section discusses the utilization of FMCW radar for vital sign detection. Two types of data are employed: one sourced from a public dataset and the other collected independently using Texas Instruments' 77 GHz FMCW radar, specifically the IWR1843 radar series.

**Two Types of Data:**
1. Public dataset from: [https://doi.org/10.6084/m9.figshare.13515977.v1](https://doi.org/10.6084/m9.figshare.13515977.v1)
2. IWR1843-Texas Instrument

# Documentation Content
* For beginners interested in processing FMCW radar, you can download the dataset [link](https://figshare.com/articles/dataset/Radar_recorded_child_vital_sign_dataset_and_deep_learning-based_age_group_classifier_for_vehicular_application/13515977/1), [paper](https://www.mdpi.com/1424-8220/21/7/2412) and process it in MATLAB. However, in this document, I attempt to process it using Python. The dataset processing program can be found in the code: `Read_Dataset_main.ipynb`.
* Code-2 represents one of the radar applications for respiratory detection. In this program, I independently collect data using IWR1843. The raw data is named `RAW_S3_24bpm_0.m.bin`, and you can learn how to read it by running the `Read_RawData.ipynb` program.

# Our Publication
If you use our code, please cite us in our publication :
[https://doi.org/10.1109/ISESD56103.2022.9980599](https://doi.org/10.1109/ISESD56103.2022.9980599)

Feel free to contact me through my account or email: [diyahwidiya52@gmail.com](mailto:diyahwidiya52@gmail.com)
