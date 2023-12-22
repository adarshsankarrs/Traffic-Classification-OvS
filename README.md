# Traffic-classifier-SDN
A system having the ability to classify machine learning algorithms like logistic regression, K-Means clustering, K nearest neighbors, SVC, Gaussian NB, and Random Forest Classifier in order to identify DNS, Telnet, Ping, Voice, Game, and Video traffic flows based on packet and byte information simulated by the Distributed Internet Traffic Generator (D-ITG) tool in an Open vSwitch (OVS) based network topology.

## Installation steps

#### D-IGT

```
https://github.com/jbucar/ditg
```


#### Mininet

```
http://mininet.org/download/
```

#### Open vSwitch

```
https://www.openvswitch.org/download/
```

#### Start Mininet topology

```
sudo mn --topo single,3 --mac --switch ovsk --controller remote

```
#### Start Real time prediction

```
python3 traffic_classifier_python3.py supervised 
```
