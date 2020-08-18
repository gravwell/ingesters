# ARCHIVED

This repo has been archived, see the [mono repo](https://github.com/gravwell/gravwell) for current code

### Sample ingesters for Gravwell.

fileFollow: Watches for & ingests updates to specific files/directories, e.g. /var/log/auth.log
networkLog: Captures & ingests network traffic from interfaces.
SimpleRelay: Listens on TCP/UDP for log events. Can ingest either newline-delimited events or syslog's RFC 5424 format.
massFile:  Bulk file optimization and ingest
session:   Ingest large entries using tcp session transfers
GooglePubSubIngester: Ingest from the Google Cloud Platform Pub Sub system
KinesisIngester:  Ingest from AWS Kinesis

go install github.com/gravwell/ingesters/fileFollow
go install github.com/gravwell/ingesters/networkLog
go install github.com/gravwell/ingesters/SimpleRelay
go install github.com/gravwell/ingesters/massFile
go install github.com/gravwell/ingesters/session
go install github.com/gravwell/ingesters/GooglePubSubIngester
go install github.com/gravwell/ingesters/KinesisIngester

