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

#### Ambulance Pattern

	Carpool thread 1 is dedicated to priority message only and remains idle if no priority message exist.

	You can think in an ambulance, an ambulance can reorder de priority of any threads, no meaning 
	a exclusive lane for ambulance.

#### Watch Notifications

	A broker will be converted in one point of failure.
	Connection saturation.
	no request mechanism(notify only)
	bandwidth utilization

	Brokerless architecure.

	Toggle-features.[]we don't need persistent connection

#### Supervisor consumer pattern.	

	Continually monitor queue.
	50 and 500 items the same time.

#### Contexual Queue pattern
	
	book orders, music orders, and movie orders are processed by different services

#### Workflow event pattern

	Ideal for error-processing flow
