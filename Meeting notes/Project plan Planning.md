# Milestones & Task decomposition


## Move along aisle

Stability

Recognize obstacles (end of carriages) using Lidar

Move in straight line

(IR sensors)


## Cleaning tables
1. Assume table is free of rubbish >> sanitize

Recognize edge of table (color & shape)

Moving arm

Spray disinfectant

Determine pressure to apply to swipe the table


2. Clean tables of rubbish

Detects rubbish

Arm moves to sweep rubbish into bag

Arm swipes

End of warm with mop cleans


## Identifying unoccupied tables

Camera or IR sensor to check the entire length of the chair to determine distance to nearest object (compare against length to wall)



## Detect people moving down aisle & move out of the way

Detect any object if still not end of carriage as obstacle needed to avoid

Or use sticker on walls to check end of carriage

Save current position -> Move back to docking station -> Wait 40s -> Move back to position


## Clean door buttons & open buttons

Check for types of buttons & check respective heights to detect circles

For exit buttons that light up: Use camera to **detect** circle shape

Rotate to clean circle

Have 2 functions corresponding to 2 IF statements (detect button/table?)

Exert little more pressure to open buttons (if necessary)


## Cross carriages

Depends on train (research)

Option so far: large & flexible wheels


## Webots presentation

Simulate train environment using Webots to test robot
