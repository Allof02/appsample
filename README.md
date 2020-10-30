# OVERWATCH PROFILE

<p align=center><img src="Overwatch-Logo.png"></img></p>

* Profile Data*
* Competitive Rank*
* QuickPlay Data
  * Specific Tank Hero Data
  * Convert Data to Chart
  * Record every change on specific hero stats

## DEMO (Profile)
```csv
Username: ZEROTWO
Level: 57
Portrait: https://d15f34w2p8l1cc.cloudfront.net/overwatch/1d754ab4338bb097f0bb7d69fe4f14c41599bc5b3ea5fa21fef68a5a1b4f9796.png
---QuickPlay---
Playtime: 47:05:46
Won: 181
---Competitive---
Playedtime: 48:49
Won: 3
Lost: 2
Draw: 0
Played: 5
Win Rate:
---Ranking---
[Tank]
Rank: 2631
IMG: https://d1u1mce87gyfbn.cloudfront.net/game/rank-icons/rank-PlatinumTier.png
[Damage]
Rank: 
IMG: 
[Support]
Rank: 
IMG: 
CurrentTime: 13:04:33
```










## DEMO (Chart pics)
<p align=center><img src="dva demo plot.png"></img></p>





# Third Party Libraries Used

* pandas

* plotly.graph_objects

* plotly.subplots

 # What Happens Here
1. Run the api_to_csv.py
2. Data will be pulled from the api and then write into the herodata.csv
3. Everytime run the api_to_csv.py file, the data will be recorded without overwriting the previous data.
4. Run the plot_csv.py file
5. It will convert the data from herodata.csv into charts (DEMO Chart Pics)


