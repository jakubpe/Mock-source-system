# Mock-source-system
Mock source system, generating random data - sending it to pulsar queue - receiving the data - uploading the data to MinIO server

Read in this order:
-Data creation = generating data and saving it to csv. file
-Producer = reading saved file from file system and sending it to pulsar queue
-consumer = receiving data from pulsar queue and saving it as csv. file
-MinIO upload  = uploading received data to MinIO server
