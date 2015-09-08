# setup_a_3node_cluster
Setup a 3-Node Cluster from Scratch

This is to start a 3-node cluster using Amazon EC2 machine using "ubuntu" as a user across the 3 machines.

I wrote a 3-part files explaining what steps need to take for a person who is totally new to Amazon EC2 to learn how to set up a 3-node Hadoop cluster. Here are the 3 steps I provisioned:

Step 1: Learn to setup Amazon EC2 Ubuntu machines. This includes how to download and use the tools needed such as PuTTY, PuTTYGen, WinSCP etc. Two major steps are:
	i) Setup the Security Group for the Hadoop clusters to work
	ii) Download the Key pair, which willl be used in Step 2.

Step 2: Setup keyless ssh from each machine to the other 2 machines.

Step 3. Download the Hadoop file, the java library and Prepare all the needed files for Hadoop cluster.

