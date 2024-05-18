# awscloudwatch
Consultas de logs

###
fields @timestamp, @message 
| filter @message like /(?i)ERROR/

