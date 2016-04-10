# What?

Simple Python script to backup Riak clusters running on EC2.

# Why?

If you don't have enterprise edition and can't do a cross datacenter nightly sync - you need a backup plan. This script helps scheduling EBS snapshots, while making sure that the services are down during the snapshot for a consistent backup and also waits for hinted handoffs to complete once nodes are back online. 

# How?

Just download the script, make changes to email settings, nodes etc and run. 
