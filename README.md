# PreprocessingT20MaleDataset
Preprocessing and adding new features in the dataset.
The dataset of Men's T20 International match data is taken from the website https://cricsheet.org/downloads/#experimental. 

Each file has various starting lines such as version, info lines, etc. The irrevalent lines are discared. The dataset contains information about 2nd innings. 

For the purpose of score prediction, only the data about the first innings is kept. The dataset contains ball by ball info. The given features are:
  * The word 'ball' to identify it as such
  * Innings number, starting from 1
  * Over and ball
  * Batting team name
  * Batsman
  * Non-striker
  * Bowler
  * Runs-off-bat
  * Extras
  * Kind of wicket, if any
  * Dismissed played, if there was a wicket
Some new features are added, and some features are discarded. Final features are:
  * id // unique id of the match
  * overs
  * teamBat
  * striker	
  * non-striker	
  * baller	
  * wickets	
  * teamBowl	
  * venue	
  * city	
  * runs	// run made on the current ball
  * cruns	// current total runs
  * run-rate
  * total	// total runs
  * last_runs5	// runs in the last 5 overs
  * last_wicket5 // wickets in the last 5 overs

 
  
  
  

