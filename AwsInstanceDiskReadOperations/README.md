# AWS Instance Disk Read Operations
[![Run On Dcoder](https://static-content.dcoder.tech/dcoder-assets/run-on-dcoder.svg)](https://code.dcoder.tech/feed/block/60f007488ecf3a76ced6fae7)

## Description
This block will give you the disk read operations data for given instance id.

## Inputs
#### **instanceId**  *Text*
Id of AWS instance to be monitored.
#### **startTime**  *Text*
Specify the start time to fetch data.
#### **endTime**  *Text*
Specify end time to fetch the data.
#### **interval**  *Number*
Interval in seconds to fetch data. for eg- 60 for 1 min, 300 for 5 min
#### **region**  *Text*
Region in which instance is hosted on aws. for eg- ap-southeast-1
#### **awsAccessKeyId**  *Text*
Aws access key id to authenticate.
#### **awsSecretAccessKey**  *Text*
Aws secret access key to authenticate.

## Output
#### **diskReadData**  *JsonObject*
Disk read data of instance.

