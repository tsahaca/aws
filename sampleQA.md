# aws

|#| Question | Choices | Ans | Why |
|----------|:----------:|:-------------:|:------:|------|
|1| Developers want your help in deploying a high transactional Cassandra NoSQL database on AWS. Due to the frequent writes, you want to maximize IOPS. Which EC2 instance type would you recommend? | Brustable (t2) | Storage Optimized | Maximum IOPS are achieved by using local SSD instance store. i3 instances provide up to 3.3M IOPS to the local ephemeral storage. Because Cassandra replicates data across multiple nodes, ephemeral storage is safe to use.|
                                                              
|2| What best describes how EBS snapshots work? |left-aligned |Only a volume's first snapshot will store the entire volume. Each subsequent snapshot will only store the changes from the last snapshot. | This |
