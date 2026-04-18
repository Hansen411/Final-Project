# Final-Project
The purpose of the project is to visualize and analyze the overal career results of Formula One Drivers. This is primarily done through a network graph, along with some deeper analysis of career lengths and their success.
## Project Introduction
Formula One is considered the highest class of international open-wheel single-seat racing. Having just celebrated the 75th anniversary of the sport, the sport has had consistent formatting of 20 drivers and 10 teams (2 drivers per team) with a varying number of races per season. However, the 2026 season introduced an 11th team, making it a total of 22 drivers per season. Race results are based on finishing position in the final lap of a race, which can vary depending on the circuit, as circuit laps vary in distance; the total lap count is adjusted to maintain a consistent distance of ~305 km per race. Based on the finishing position of each race, drivers are awarded points, which also contribute to the Team points. At the end of the racing season (usually early December), two championships are decided, the Drivers' Championship and the Constructors Championship. The Drivers' Championship determines which individual driver scored the most points throughout the racing season, while the Constructors Championship determines which Team scored the most points. 
<img width="442" height="362" alt="image" src="https://github.com/user-attachments/assets/cd0bc1f0-b40a-40d9-a001-246562bd38ad" />

## Dataset
The Formula One Race Data[1] used for this project was sourced through Kaggle. The dataset contains 14 different tables with data ranging from seasons beginning in 1950 to 2025. This data does not contain the current (2026) season and therefore does not reflect the addition of an 11th team or the additional 2 drivers. With the use of Microsoft Access, I combined 5 of the available tables (Results, Drivers, Race Status, Races, Lap Times) to create a consolidated table of 27,304 records [2]. Instances of a race status outside of “Finished” were not removed, as the main observation of this project is the overall race career results, and a race status of “retired” or “DNF (Did Not Finish)” still contributes to a driver’s overall career performance.

## Conclusion

## Resources
<ul>
  <li>
    [1] https://www.kaggle.com/datasets/jtrotman/formula-1-race-data?select=circuits.csv
  </li>
  <li>
    [2] Can be found in "Results_4.xlxs"
  </li>
</ul>



## Acknowledgements
