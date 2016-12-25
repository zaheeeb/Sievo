# Sievo - Slack integration with errors log file

. This code is tracking logs file and notify to Slack channel once threshold is met.

### Installation

. Code is developed in C# console application and can be run through visual studio.
- slack webhhok key and user name are stored to system variables as 'webhook' and 'slack_user_name' respectively.

### Steps to executs program
 - Run code in visual studio. 
 - Console will ask for threshold which should be any number but for complete application working it can be 1.
 - Console will ask for logs file name which should be given as "logs.txt"
 - Console will ask for search server name which should be given as production_1.
 - Because in logs file errors are more than 1, so system will ask for Slack channel name to be notified.
 - By giving slack channel e.g. random following message is posted to slack channel. 
    "Error logged 3 times which is more than given threashold 1 of server production_1"

### Further Improvements
 - Input fields validation can be done. 
 - Dynamic path of logs file can be implemented.
 - Time/error specific search.
 - Sending notifications to server for scalability. 
