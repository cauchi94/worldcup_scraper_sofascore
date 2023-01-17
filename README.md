# worldcup_scraper_sofascore
The Python script returns two dataframes corresponding to the rankings of the Group Stages and the results and outcomes of the Knockout Phase of the World Cup based on the edition that is selected.

## How to Use  
Use www.sofascore.com to find the url that corresponds to the World Cup Edition you're looking for. The best way to do this is to go directly to the link and click on:  
- Football  
- World Championship  
- Select the World Cup Edition for which you want to scrape results  
- The edition's ID is the last integer after the # (hashtag) (e.g. 41087)  

Run the script, and when prompted for the ID, enter the above integer.  
  
The Python script must save two data frames:  
- Group Stage Standings  
- Knockout Phase Results (after 90 mins, after extra time, after penalties)  
