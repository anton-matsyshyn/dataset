### This repository contains a dataset of a server machines features.
All measures were performed consecutively, with an interval of 5 minutes.

Timeframe: 15 Mar 2023 - 14 Apr 2023. <br />
Number of instances: 8615. <br />
Number of features: 22 + timestamp <br />
Mesaure interval: 5 min. <br />

Table contains a list of characteristics with measure units.

| Feature       | Unit          |
| ------------- |:-------------:|
| Apdex         | percent       |
| Latency       | ms            |
| ConsumerLag   | integer       |
| TotalReceivedBytesMessaging   | byte       |
| ThreadsInUse   | integer       |
| CpuPercentageUsed   | percent       |
| DistanceMatrixRequestOk   | integer       |
| DistanceMatrixRequestFailed   | integer       |
| DistanceRowRequestOk   | integer       |
| DistanceRowRequestFailed   | integer       |
| ErrorLogsCount   | integer       |
| Gen0Collections   | byte       |
| Gen1Collections   | byte       |
| Gen2Collections   | byte       |
| Percentile75   | ms       |
| Percentile95   | ms       |
| Percentile99   | ms       |
| ActiveGrains   | integer       |
| KafkaProducedMessages   | integer       |
| KafkaReceivedMessages   | integer       |
| Throughput   | byte       |
