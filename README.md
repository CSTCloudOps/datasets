We have formatted the raw data into a unified format to enable the model to conveniently read and process the data. All missing values are filled using linear interpolation.

All Datasets are available online. The ways to obtain the dataset are as follows：

- AIOPS: https://github.com/iopsai/iops
- WSD: https://github.com/alumik/AnoTransfer-data
- NAB: https://www.kaggle.com/datasets/boltzmannbrain/nab
- Yahoo: https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70
- UCR: https://wu.renjie.im/research/anomaly-benchmarks-are-flawed/#ucr-time-series-anomaly-archive
- TODS: https://github.com/datamllab/tods/tree/master/datasets

NOTE: The original data generation process in TODS makes too navie anomalies. We modify the generation code to create more smoother, longer and more reasonable anomalies that are aligned with the description in their papers.

Now we add new MTS datasets. The ways to obtain the dataset are as follows：

- SMD: https://github.com/NetManAIOps/OmniAnomaly
- SWaT: https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/#swat
- SMAP & MSL: https://www.kaggle.com/datasets/patrickfleith/nasa-anomaly-detection-dataset-smap-msl
- PSM: https://github.com/eBay/RANSynCoders

NOTE: We use methods in CAD Anomaly Detection to process data in SMD and SWaT. Please refer to https://github.com/dawnvince/MTS_CAD to see more information.
