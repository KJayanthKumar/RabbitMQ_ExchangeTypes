# RabbitMQ_ExchangeTypes
RabbitMQ Demo project for exchange types: Direct Exchange, Topic Exchange, Headers Exchange, Fanout Exchange.


Type of Exchanges
There are four main types of exchanges. 
1.	Direct, 
2.	Topic, 
3.	Header and 
4.	Fanout.

Direct exchange uses a routing key in the header to identify which queue the message should be sent to. The routing key is a header value set by the producer. And consumer uses the routing key to bind to the queue. The exchange does the exact match of routing key values.

The topic exchange also uses a routing key, but it does not do an exact match on the routing key, instead, it does a pattern match based on the pattern.

Header exchange routes messages based on header values and are very similar to Topic exchange.

As the name suggests, Fanout exchange routes messages to all the queues bound to it.
