
An attempt to use an embedded jms broker as a remote jms broker.

* http-connector: The broker is a pure embedded jms broker based on Galleon layer embedded-activemq, no customization, no queue nor topics created.
The client makes use of external jms queues and topics. and accesses the broker thanks to an http-connector.

* remote-connector: The broker is extended with a remote acceptor. It also defines a queue and a topic. The client relies on cloud CLI script to configure 
the jms and naming subsystems thanks to env variables.


