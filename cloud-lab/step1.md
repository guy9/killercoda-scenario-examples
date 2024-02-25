A [Cluster](https://university.scylladb.com/courses/scylla-essentials-overview/lessons/architecture/topic/cluster-node-ring/) is a collection of [Nodes](https://university.scylladb.com/topic/node/) that ScyllaDB uses to store the data. The nodes are logically distributed like a ring. A minimum cluster typically consists of at least three nodes. Data is automatically [replicated](https://university.scylladb.com/topic/data-replication/) across the cluster, depending on the Replication Factor. Learn more about ScyllaDB Architecture in [this lesson](https://university.scylladb.com/courses/scylla-essentials-overview/lessons/architecture/).


## Create a ScyllaDB Cluster

[Sign in](https://cloud.scylladb.com/user/signin) to ScyllaDB Cloud if you already have a user. Otherwise, [create](https://cloud.scylladb.com/user/signup) one. 

Once you’re in, navigate to My Clusters and add a new cluster. Notice that you can use the free trial if you’re a new user.

Leave the default options as they are. Enter “test-cluster” for the cluster name and click Launch Cluster. This will start a three-node cluster that you will use for this lab. 
Notice that you can use the free trial if you’re a new user. 

![](https://university.scylladb.com/wp-content/uploads/2021/06/scylladb_cloud_clusters.png)

Leave the default options as they are. Enter “test-cluster” for the cluster name.
Ensure your IP is added to the Allowed IPs list. This is to allow connections from the outside world to your new ScyllaDB Cloud cluster. 
Next, click Launch Cluster. This will start a three-node cluster that you will use for this lab. 
Wait until the cluster is ready. Next, you’ll connect to it. Click Connect.

Next, you’ll connect to it. Click on Connect.

![](https://university.scylladb.com/wp-content/uploads/2021/06/image3.png)

It’s also possible to use your own AWS account with ScyllaDB Cloud using the ScyllaDB Cloud Bring Your Own Account (BYOA) feature. Learn more about it [here]([url](https://docs.scylladb.com/scylla-cloud/cloud-setup/scylla-cloud-byoa/)https://docs.scylladb.com/scylla-cloud/cloud-setup/scylla-cloud-byoa/). 
