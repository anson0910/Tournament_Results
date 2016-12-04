# Tournament_Results
Database schema to store the game matches between players, and code to query this data and determine the winners of various games.

## Testing the database setup:
1. In directory, type `psql`
2. Build the database **tournament**, and create tables **players** and **matches** through sourcing the file by <br>
  `\i tournament.sql`
3. Run <br>
  `python tournament_test.py`
  to execute the test file. 
