# cx-api-xdr-ingestion

This is a public repository that contains the Protobuf message and service definitions for the Coralogix XDR Ingestion APIs.

To generate data locally: ```protoc -I . --python_betterproto_out=python_out com/coralogix/xdr/ingestion/v1/*```