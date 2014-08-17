#Benchmark results by [iombench](https://github.com/yongkun/iombench).

__Please note that these results may not represent the optimal performance of measured devices or systems.__ Your results might be different with your configurations.

**Table of Contents**  *generated with [DocToc](http://doctoc.herokuapp.com/)*

- [Devices](#user-content-devices)
	- [Hitachi HGST HDS72107 750GB](#user-content-hitachi-hgst-hds72107-750gb)
	- [Intel X25-E 64GB](#user-content-intel-x25-e-64gb)
	- [Mtron PRO 7500 32GB](#user-content-mtron-pro-7500-32gb)
	- [OCZ Vertex EX 120GB](#user-content-ocz-vertex-ex-120gb)
- [Cloud Systems](#user-content-cloud-systems)
	- [AWS EC2 t2.micro](#user-content-aws-ec2-t2micro)
	- [AWS EC2 i2.xlarge](#user-content-aws-ec2-i2xlarge)
	- [Linux Container](#user-content-linux-container)
	- [Vsphere VM](#user-content-vsphere-vm)
- [Contact](#user-content-contact)

#Devices

##Hitachi HGST HDS72107 750GB

##Intel X25-E 64GB

Configuration and explanation: [IEICE Yongkun Wang](http://www.tkl.iis.u-tokyo.ac.jp/~yongkun/paper/ieice-yongkun-wang-final.pdf)

### Sequential Throughput
![iombench-intel-seq-thrpt-1.png](./intel-x25e/iombench-intel-seq-thrpt-1.png)
### Random Throughput
![iombench-intel-rnd1-iops-1.png](./intel-x25e/iombench-intel-rnd1-iops-1.png)
### Random Throughput (30 threads)
![iombench-intel-rnd30-iops-1.png](./intel-x25e/iombench-intel-rnd30-iops-1.png)
### Sequential Performance with mixed Reads/Writes
![iombench-mix-seq-intel.png](./intel-x25e/iombench-mix-seq-intel.png)
![iombench-mix-seq-intel-throughput.png](./intel-x25e/iombench-mix-seq-intel-throughput.png)
### Random Performance with mixed Reads/Writes
![iombench-mix-rnd-intel.png](./intel-x25e/iombench-mix-rnd-intel.png)
![iombench-mix-rnd-intel-iops.png](./intel-x25e/iombench-mix-rnd-intel-iops.png)

##Mtron PRO 7500 32GB

Configuration and explanation: [IEICE Yongkun Wang](http://www.tkl.iis.u-tokyo.ac.jp/~yongkun/paper/ieice-yongkun-wang-final.pdf)

### Sequential Throughput
![iombench-mtron-seq-thrpt-1.png](./mtron-pro-7500/iombench-mtron-seq-thrpt-1.png)
### Random Throughput
![iombench-mtron-rnd1-iops-1.png](./mtron-pro-7500/iombench-mtron-rnd1-iops-1.png)
### Random Throughput (30 threads)
![iombench-mtron-rnd30-iops-1.png](./mtron-pro-7500/iombench-mtron-rnd30-iops-1.png)
### Sequential Performance with mixed Reads/Writes
![iombench-mix-seq-mtron.png](./mtron-pro-7500/iombench-mix-seq-mtron.png)
![iombench-mix-seq-mtron-throughput.png](./mtron-pro-7500/iombench-mix-seq-mtron-throughput.png)
### Random Performance with mixed Reads/Writes
![iombench-mix-rnd-mtron.png](./mtron-pro-7500/iombench-mix-rnd-mtron.png)
![iombench-mix-rnd-mtron-iops.png](./mtron-pro-7500/iombench-mix-rnd-mtron-iops.png)

##OCZ Vertex EX 120GB

Configuration and explanation: [IEICE Yongkun Wang](http://www.tkl.iis.u-tokyo.ac.jp/~yongkun/paper/ieice-yongkun-wang-final.pdf)

### Sequential Throughput
![iombench-ocz-seq-thrpt-1.png](./ocz-vertex-ex/iombench-ocz-seq-thrpt-1.png)
### Random Throughput
![iombench-ocz-rnd1-iops-1.png](./ocz-vertex-ex/iombench-ocz-rnd1-iops-1.png)
### Random Throughput (30 threads)
![iombench-ocz-rnd30-iops-1.png](./ocz-vertex-ex/iombench-ocz-rnd30-iops-1.png)
### Sequential Performance with mixed Reads/Writes
![iombench-mix-seq-ocz.png](./ocz-vertex-ex/iombench-mix-seq-ocz.png)
![iombench-mix-seq-ocz-throughput.png](./ocz-vertex-ex/iombench-mix-seq-ocz-throughput.png)
### Random Performance with mixed Reads/Writes
![iombench-mix-rnd-ocz.png](./ocz-vertex-ex/iombench-mix-rnd-ocz.png)
![iombench-mix-rnd-ocz-iops.png](./ocz-vertex-ex/iombench-mix-rnd-ocz-iops.png)


#Cloud Systems

##AWS EC2 t2.micro

##AWS EC2 i2.xlarge

##Linux Container

##Vsphere VM

#Contact
yongkun at gmail.com

