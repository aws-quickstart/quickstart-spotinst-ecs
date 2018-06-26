# quickstart-spotinst-elastigroup-ecs

This Quick Start creates a Spotinst Elastigroup and configures it as the underlying infrastructure for an Amazon ECS cluster. Spotinst Elastigroup is an intelligent cluster management platform that lets you save up to 80% on your compute costs while maintaining 100% availability. Spotinst Elastigroup maintains spot instances as the underlying infrastructure for your ECS cluster, while making sure that your ECS cluster is always available by leveraging predictive algorithms and smart resource allocation. 

Spotinst Elastigroup’s ECS autoscaler strips away any need to provision, manage, or scale your infrastructure. Moreover, the Elastigroup ECS autoscaler constantly monitors CPU, Memory and port availability, scaling your cluster up to accommodate for incoming tasks, and scaling it down when instances are underutilized. Finally, the ECS autoscaler lets you define and customize the desired “headroom” for your ECS cluster, making sure that your application always has enough capacity provisioned to handle spikes in traffic.



![Quick Start Linux Bastion Design Architecture](https://github.com/spotinst/quickstart-spotinst-elastigroup-ecs/blob/master/architecture.png)