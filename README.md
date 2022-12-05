## Requirements

Install [opcua-asyncio](https://github.com/FreeOpcUa/opcua-asyncio) with the following command:

```shell
pip install asyncua
```

## Starting the OPC UA Server

Run the server with:

```shell
$ python server.py
Server started: OPC UA Server(opc.tcp://localhost:4840)
```

## Running the OPC UA Client for Subscription

Run the client with:

```shell
$ python client.py
Data change notification was received and queued.
New value 4 of "['0:Root', '0:Objects', '2:MyObject', '2:MyVariable']" was processed.
Data change notification was received and queued.
New value 79 of "['0:Root', '0:Objects', '2:MyObject', '2:MyVariable']" was processed.
Data change notification was received and queued.
New value 75 of "['0:Root', '0:Objects', '2:MyObject', '2:MyVariable']" was processed.
...
```
