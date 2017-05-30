# Monitoring Plugin: Mongo-Connector

### Description

Monitor the offset of your mongo-connector (https://github.com/mongodb-labs/mongo-connector).

### Usage
Usage: check_mongo_connector [options]

Options:
  -h, --help         show this help message and exit
  -H MONGODB_SERVER  [Default: mongodb://localhost:27017] MongoDB host URI
  -f OPLOG_FILE      [Default: /var/lib/mongo-connector/oplog.log] Path to
                     mongo-connector oplog file (oplogFile)
  -w WARNING         [Default: 30] Warning offset in seconds
  -c CRITICAL        [Default: 60] Critical offset in seconds

### Install 

Copy check_mongo_connector to your plugin folder and create a service/exec in your monitoring engine. 
