Nick Bearup
Project 2 Submission:

1) When I ran the exact_F2 function locally on my computer, I got the following output:

21/04/04 20:35:14 INFO DAGScheduler: Job 1 finished: reduce at main.scala:131, took 114.330169 s
==================================
Exact F2. Time elapsed:114s. Estimate: 21968462
==================================

When I ran the program in the GCP, this is the error message that I kept getting:

21/04/05 21:28:07 INFO org.sparkproject.jetty.util.log: Logging initialized @3631ms to org.sparkproject.jetty.util.log.Slf4jLog
21/04/05 21:28:07 INFO org.sparkproject.jetty.server.Server: jetty-9.4.36.v20210114; built: 2021-01-14T16:44:28.689Z; git: 238ec6997c7806b055319a6d11f8ae7564adc0de; jvm 1.8.0_282-b08
21/04/05 21:28:07 INFO org.sparkproject.jetty.server.Server: Started @3809ms
21/04/05 21:28:07 INFO org.sparkproject.jetty.server.AbstractConnector: Started ServerConnector@1d207fad{HTTP/1.1, (http/1.1)}{0.0.0.0:39743}
21/04/05 21:28:08 INFO org.apache.hadoop.yarn.client.RMProxy: Connecting to ResourceManager at bearupn-csci3390-cluster-m/10.128.0.12:8032
21/04/05 21:28:08 INFO org.apache.hadoop.yarn.client.AHSProxy: Connecting to Application History server at bearupn-csci3390-cluster-m/10.128.0.12:10200
21/04/05 21:28:09 INFO org.apache.hadoop.conf.Configuration: resource-types.xml not found
21/04/05 21:28:09 INFO org.apache.hadoop.yarn.util.resource.ResourceUtils: Unable to find 'resource-types.xml'.
21/04/05 21:28:11 INFO org.apache.hadoop.yarn.client.api.impl.YarnClientImpl: Submitted application application_1617657916224_0001
21/04/05 21:28:12 INFO org.apache.hadoop.yarn.client.RMProxy: Connecting to ResourceManager at bearupn-csci3390-cluster-m/10.128.0.12:8030
Usage: project_2 input_path option = {BJKST, tidemark, ToW, exactF2, exactF0} 
21/04/05 21:28:14 INFO org.sparkproject.jetty.server.AbstractConnector: Stopped Spark@1d207fad{HTTP/1.1, (http/1.1)}{0.0.0.0:0}

I was in contact with Professor Su extensively, and couldn't seem to figure out what the issue was.

I clearly had some trouble with this project.
