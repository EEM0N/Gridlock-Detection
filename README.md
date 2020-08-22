# Gridlock-Detection
Installation:

	python 3.5 
	PyCharm 5 


Main Files 
============================================================================================
1) sathorn_wide_tls_20160418_edited.add(LargePOI)_extendDetectorLength.xml 			- to configure the lane area detectors on each link of the whole loop


2) sathorn_wide_tls_20160418_edited.add(LargePOI)_extendDetectorLength_upsteam_100.xml		- to configure the lane area detectors in the upstream and downstream (100-m for upstream and	50-m for downstream)


3) gridlockDetection(30.04.2019).py								- to retrieve the data from the each intersection of the Sathorn loop by using lane area detectors 100-m length for upstream and 50-m length for downstream

4) gridlockDetection(30.04.2019)_loop.py					- to retrieve the data from the whole Sathorn loop by using lane area detectors



Dataset
============================================================================================
GridlockDetection(30.04.2019)_FlowAmountChange/

1) CSVData		
2) CSVData_forLoop
3) CongestionDataForEachCluster



Remark
============================================================================================
Here, we used two extra traffic routes (route171,route173) in sathorn_w_20160422-Great.rou_edited-5times.xml. 


