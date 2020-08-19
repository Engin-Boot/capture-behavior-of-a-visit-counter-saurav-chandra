# Visit-counter technical needs

## Scenario: Recover across restarts of the server that runs the visit-counter

  Given: Server is restarting and sensor is counting visitors.

  When: I want to recover the no. of visitors during the server .restart

  Then: I get the count of the same.


## Scenario: Reconcile counts if the sensor is offline for a while

  Given: The sensor went offline for a while.

  When: I want to get the number of visits in that time.

  Then: I get an average number of visitors in one hour before and after the server failure. And generate the message that this is not the actual data.

