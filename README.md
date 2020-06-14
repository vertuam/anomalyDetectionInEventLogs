# anomalyDetectionInEventLogs
On the use of online clustering for anomaly detection in event logs

# anomalyDetectionInEventLogs
On the use of online clustering for anomaly detection in event logs

• Datasets:
    – 8 process models1 ranging different behaviors (note that we will have additional models representing the drifted      behavior from the refer- ence model)<br/>
    – 6 types of anomalies + 1 version with all anomalies concurrently<br/>
    – 4 types of concept drift: sudden, gradual, incremental, recurring<br/>
    – 3 log sizes (in number of cases): 1000, 5000, 10000<br/>
    – Anomaly percentage: 0%, 5%, 10%, 15%, 20%<br/>
    – Totalnumberofsyntheticlogs: 8*7*4*3*5=3360. Sincethis is a quite huge number of logs, we can chose to use only some part of it or to decrease the number of process models<br/>
    – For real event logs, I propose to use the BPIC logs without injecting anomalies as this was not well understood by BPM reviewers and the practice is indeed not the best because BPIC logs already have anomalies. We could run the anomaly detection here as a use case and discuss about the detected anomalies2<br/>
    <br/>
    1 https://github.com/tnolle/binet/tree/master/.res/process_models <br/>
    2 https://data.4tu.nl/repository/collection:event_logs_real<br/>
