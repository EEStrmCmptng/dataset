This repository contains a sample dataset with energy and performance measurements collected while running Apache Flink workloads on an experimental test bed. The names of the CSV files represent the parameter setting of each test. Like "1000qps.csv" means the experiment with the parameter of 1000 queries per second, or "1000_120000.csv" means th experiment with the parameter of 1000 queries every 120 seconds.Most of the values are collected from the ITR logs of Vicitim node. We generate this dataset for the future visualization and pattern detection of the energt consumption of our system. Here is the interpretation of the values we collected.  

The first row of each CSV file contains the names of parameters recorded:

**"app i itr dvfs rapl latency joules rx_desc rx_bytes tx_desc tx_bytes instructions ref_cycles num_interrupts"**:

* **app**:app

* **i**:number of iterations 

* **itr**:NIC's interrupt delay setting 

* **dvfs**:Dynamic Voltage Frequency Scaling 

* **rapl**:Running Average Power Limit

* **latency**:average latency

* **joules**: energy consumption

* **rx_desc**:num of package received

* **rx_bytes**:num of bytes received

* **tx_desc**:num of package transfered

* **tx_bytes**:num of bytes transfered 

* **instructions**: instructions

* **ref_cycles**: cycle

* **num_interrupts**: number of interrupts




For each row below, it is the result of each iteration of the experiment.
