#### Notes from the course

  - Quetions
  - FIFO/guarantee
  - PubSub
  - How can I set the priority 
  - Alarms

#### Event Forwarding pattern

	From Service A -> to pipe -> Service B -> Database.

	For treat lost messages. Use synchronus send and peristed messages.
	
	Client acknowledge mode, deque, but marked with id.

	Last participant support for message acknoweledgement.

	No lost messages,but perfomance, throughput and duplicates.

#### Thread,Delegate pattern

	Not every message must be in order,but rather message withtin context must be ordered.

	maintain processing order
	increase throughput
	increase perfomance
	increase scalability
	
