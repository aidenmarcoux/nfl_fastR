# nfl_fastR

In a new cell, call the function plot_data(team_name, stat, side)

**args (all strings)

team_name --> abbreviated name of targeted team
stat --> targeted stat
side --> offense or defense

## Team Names:
Arizona:'ARI'
Atlanta: 'ATL'
Baltimore: 'BAL'
Buffalo: 'BUF'
Carolina: 'CAR'
Chicago:'CHI'
Cincinnati: 'CIN'
Cleveland: 'CLE'
Dallas:'DAL'
Denver: 'DEN'
Detroit:'DET'
Green Bay:'GB'
Houston: 'HOU'
Indianapolis: 'IND'
Jacksonville: 'JAX'
Kansas City: 'KC'
Los Angelas (Rams):'LA'
Los Angelas (Chargers): 'LAC'
Las Vegas: 'LV'
Miami: 'MIA'
Minnesota:'MIN'
New England:'NE'
New Orleans: 'NO'
New York (Giants):'NYG',
New York (Jets): 'NYJ'
Philedelphia: 'PHI'
Pittsburgh: 'PIT'
Seattle: 'SEA'
San Francisco: 'SF'
Tampa Bay:'TB'
Tennessee: 'TEN'
Washington: 'WAS'

## Stats:
epa: epa on both pass and rush plays
pass_epa: epa on passing plays
rush_epa: epa on rushing plays
success: success rate (%) on pass and rush plays 
pass_success: success rate (%) on pass plays
rush_success: success rate (%) on rush plays
      
## Example:

plot_data("GB" , "pass_success", "defense") --> this gets the pass success rate of the opponent when GB is on defense. 
       
       
       
       
       
