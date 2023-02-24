---
title: A Real Time Electronic Football Analyst
category: ReadRPO
order: 1
---

<div align="center">
  Aarav Batra
  <br>
  <a href="aaravbatra@duck.com">aaravbatra@duck.com</a>
  <br>
  <a href="https://readrpo.github.io">readrpo.github.io</a>
  <br>
  
  <br>
</div>
  <div style="text-align: center; text-align: justify;">
  **Abstract.** The use of artificial intelligence in football player detection has the potential to revolutionize the way coaches and teams analyze the game. The proposed system will utilize object detection and relative points to determine the location of players on the field. The player's location will be represented by XYZ coordinates in yards, with the exception of ball travel, which will be measured in a different manner. A 360° vision system will be employed to provide comprehensive coverage of the field and accurately assign unique coordinates to each object class. The main advantage of using an XYZ plane for detection is the ability to accurately track player movement, including jumping or hurdling for the ball, as well as the trajectory of the ball itself. In order to effectively determine the outcome of a play, it is important to have a clear understanding of the formation of the players and the play being run. The system will use both historical data and real-time data from current games to calculate the probability of a given play being run by the opponent. This information can be used to gain a strategic advantage by allowing coaches to make informed decisions in real-time. By utilizing advanced machine learning algorithms and a large data set of both training and testing data, the proposed system will be able to quickly process vast amounts of information to determine the most likely outcome of a play. This will be a significant improvement over traditional methods, as it will allow coaches to make split-second decisions based on real-time data, rather than relying on intuition or prior experience.
</div>

## 1. Introduction
<p style="text-align: justify;">

  High schools typically run the same base playbook every season, and different plays are added on or changed. While the other team runs fundamentally the same plays, it’s impossible to pre-determine the play being run despite a strategic similarity. Film sessions are valuable to players and coaches to break down strategy, but the data is scattered and too difficult to manually organize. Systems like this already exist however they fail in real time and only manage to scarcely piece basic data together. Data could be manually inputted to make predictions, but would take too long to make a call. Existing systems would be rendered useless as major league teams change their playbooks annually. The only advantage such a system would provide is statistics, such as completion rates and patterns. Making calls on the field would be completely impossible for an artificial intelligence system with brand new data every play. 
<br>
  What is needed is a 360° view of the field with a system to process the data quickly enough with surplus data to make a call on the field. This complicates the issue because high-speeds would be required, and any IP calls for predicting would simply take too long. The solution could come from syncing all 4 streams and converting them to frames at the same timestamp, detecting yard lines and yard numbers to use focal length to calculate the relative distance to the player, and analyzing the data. However, OCR would be extremely unreliable and time consuming on the system for detecting yard numbers and jersey numbers to assign unique IDs to each player. Instead, we propose classing each player by their position on the field to assign a unique number to each player by a system such as the one proposed by the NCAA [3]. Another issue presented is the automatic systems of sports cameras which may zoom, pan, or stitch video from multiple cameras on the same unit. This would need precise calculations from when the camera will zoom, and what its focal length is. Unless the algorithm accounts for quantifying the spatial solving, then any motion by the camera would render it useless. 
<br>
  The solution would either need to find the spatial solving on the fly, such as using points on the field as reference points which would complicate the tracking but provide more data.
</p>

## 2. Objects

## 3. Detection

## 4. Spatial Solving

## 5. Analysis

## 6. Hardware

## 7. Speed

## 8. Incentive

## 9. Conclusion

## References
[1] Copyright 2023 ReadRPO by Aarav Batra
[2] Batra, A., Pike, D., Steinfeld, A., et al. (2023). Roboflow (Version 1.0) ReadRPO. Available from https://roboflow.com. computer vision.
[3] NCAA Football Rulebook. (2023). NCAA Football  Rule 1, Section 4, Article 1. Available from https://www.ncaapublications.com. 
