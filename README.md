# Machine-Learning-for-Botnet-Detection
\
\
This folder includes Jupyter Notebooks sheets with implemented Machine Learning methods K-Nearest Neighbors, Naїve Bayes, and Decision Trees. The algorithms used for the detection of network-based botnets.
\
A dataset used may be found by the link: http://205.174.165.80/CICDataset/ISCX-Bot-2014/Dataset/
\
Information about dataset present by following link: https://www.unb.ca/cic/datasets/botnet.html
\
\
First of all the dataset was processed by CICFlowMeter in Unix-based OS (in my case it`s CentOS 7). 
\
The flow generator may be found by the link: https://www.researchgate.net/publication/326991554_CICFlowmeter-V40_formerly_known_as_ISCXFlowMeter_is_a_network_traffic_Bi-flow_generator_and_analyser_for_anomaly_detection_httpsgithubcomISCXCICFlowMeter/link/5b717144a6fdcc87df742e3e/download
\
It retrieves more than 80 columns from *.PCAP files and converts them to *.CSV files. 
\
\
The mentioned *.CSV files used as end-files by the program.
\
\
Values that used for results validation are Accurracy, Prescision, Recall, and F1-Score. Also, a confusion matrix used to determine False Positive/Negative, True Positive/Negative rate.
\
Results illustrated in Results.zip file.
