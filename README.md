# nfl_fastR

In a new cell, call the function plot_data(team_name, stat, side)

**args (all strings)

team_name --> abbreviated name of targeted team
stat --> targeted stat
side --> offense or defense

## Team Names:
Arizona:'ARI'<br/>
Atlanta: 'ATL'<br/>
Baltimore: 'BAL'<br/>
Buffalo: 'BUF'<br/>
Carolina: 'CAR'<br/>
Chicago:'CHI'<br/>
Cincinnati: 'CIN'<br/>
Cleveland: 'CLE'<br/>
Dallas:'DAL'<br/>
Denver: 'DEN'<br/>
Detroit:'DET'<br/>
Green Bay:'GB'<br/>
Houston: 'HOU'<br/>
Indianapolis: 'IND'<br/>
Jacksonville: 'JAX'<br/>
Kansas City: 'KC'<br/>
Los Angelas (Rams):'LA'<br/>
Los Angelas (Chargers): 'LAC'<br/>
Las Vegas: 'LV'<br/>
Miami: 'MIA'<br/>
Minnesota:'MIN'<br/>
New England:'NE'<br/>
New Orleans: 'NO'<br/>
New York (Giants):'NYG'<br/>
New York (Jets): 'NYJ'<br/>
Philedelphia: 'PHI'<br/>
Pittsburgh: 'PIT'<br/>
Seattle: 'SEA'<br/>
San Francisco: 'SF'<br/>
Tampa Bay:'TB'<br/>
Tennessee: 'TEN'<br/>
Washington: 'WAS'<br/>

## Stats:
epa: epa on both pass and rush plays
pass_epa: epa on passing plays
rush_epa: epa on rushing plays
success: success rate (%) on pass and rush plays 
pass_success: success rate (%) on pass plays
rush_success: success rate (%) on rush plays
      
## Example:

plot_data("GB" , "pass_success", "defense") --> this gets the pass success rate of the opponent when GB is on defense. 
       
       
       
       
       
