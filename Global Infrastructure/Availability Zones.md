Availability Zone's (AZ) is a phyiscal location made up of one or more datacenter
A datacenter is a secured building that contains hundreds of thousands of computers

A region will *Generally* contain 3 Availability Zones

Datacenters within a region will be isolated from each other (different buildings). But they will be close enough to provide low-latency (<10ms).

It is common practice to run worklaods in at least 3 AZs to ensure services remain available in case one or two datacenters fail (High Availability).


Represented by a regional code followed by a letter.

I.e us-east1a


A subnet is assocaited with an Availability Zone.

You never chose the AZ when launching resources. You choose the subnet which is associated to the AZ.


#global-infrastructure #high-availability