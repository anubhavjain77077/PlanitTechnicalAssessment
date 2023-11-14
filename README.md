Planit Technical Assessment

"The system should scale to 2000 users".
What other questions would you need to ask in order to get enough information to create a workload model.

Is 2000 concurrent users to be achieved during steady state ? What is the total transactions to be achieved for total duration and for steady state ? What are the performance critical scenarios and its actions - Total transactions to be acheived per scenario What is scenario distribution percentage ?

The system should be able to scale to 2000 users for a steady state for 1 hour, achieveing 200000 transactions in that 1 hour duration. The system should be able to handle around 300000 transactions in the load test run. The load distribution should be Homepage for duckduckgo 30% Suggested search - 40% Search - 30%

Following factors to be considered:

• The protocol(s) the application is using • How to manage cookies, cache, which calls are served by cloud cdn etc • The performance testing scenarios are working manually (functionally) • Which load testing tool to be used, licenced or open-source ?, whether or not it will support the protocol • Performance metrics, accepted levels, or SLAs and goals, objectives of the test • Which kind of performance tests applications needs, load, stress, failover, endurance etc • performance tesing env equivalent to prod or not • Performance testing data required during the load test and how to poppulate that. • Which monitoring tool(s) being used.
