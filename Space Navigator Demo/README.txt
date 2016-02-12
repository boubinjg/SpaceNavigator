This is a demo version of Space Navigator. This version is programmed specifically to study compliance with automation based on inherent reliability. This demo version has 3 levels. All levels last 5 minutes and have identical spawn rates.

Level 1: warmup
	The Warmup level incorporates no automation.

Level 2: 100% Reliability
	The second level includes automation which is 100% reliable. When a ship 	spawns, a route will be immediately drawn for it. This route will go to the 	correct planet 100% of the time. 
Level 3: 70% Reliability
	The third level includes automation which is 100% reliable for the first 		minute and 70% reliable for the rest of the game. 

When a level is completed, a file is created to save its information. The only way the game knows how to load a level is by analyzing the files which exist in the games working directory. To start the demo over from the beginning, delete all files of the form "level_x_data.txt" or similar. 
