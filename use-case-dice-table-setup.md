Use Case: Dice Table Setup
=================================
**Actors**: Dealer

**Scope**: Dice crypto condition

**Purpose**: Setup a table for blockchain dice game

**Type**: Primary 

**Overview**: A Dealer creates a plan (fund) representing a table for people to place bets at.  In order for people to bet, it needs funds added to it.

Typical course of events:
----------------------

| Actor Action | System Response |
|:--------------|:----------------|
| 1. Dealer creates a table | 2. The system determines that the inputs satisfy the requirements and responds with a rawtransaction |
| 3. Dealer broadcasts the rawtransaction | 4. The system responds with a transaction id |
| 5. Dealer waits until the transaction has been confirmed |  |
| 6. Dealer queries the system for list of tables | 7. System responds with list of tables |
| 8. Dealer chooses the table from the list to fund and adds funds to the table | 9.  System responds with a transaction id |



Alternative Courses:
-----------
1a. Dealer submits wrong data inputs and no rawtransaction is returned and the use case ends here or can be started again.

