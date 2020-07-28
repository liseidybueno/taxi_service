# taxi_service
Mimics a taxi dispatcher 

This Java application was created for a Java Programming course and uses threading to mimic a dispatching taxi service. The program has five taxis that go on duty, and a text list of 20 customers with their name (cust #), drop off, and pick up locations. The customers are loaded up into a Linked Blocking Queue. Each driver object takes a customer from the queue and uses a thread to print out that customer has been picked up and dropped off. After drop off, the driver's customer count increases by one. Once each driver has had 4 customers, they are off duty.

