# Goal-E
### MTE 481 - Mechatronics Engineering Design Project
_Andrew Willms, Christian Bergmann, Erik Smith, Jonathan Gervais, Josh Cooke_

&nbsp;
## The Needs We Have Observed
- Hockey Goalies are often in very high demand for training
- Shooting practice with a live Goalie is very tiring for the Goalie involved
- This leads to Goalies not wanting to practice for too long
- Current Substitution tools for Goalies are very basic and often do not mirror reality
- Baseball has created a pitching system able to replicate the exact pitches of players
- Creating a similar tool for hockey would reduce goalie wearout and increase player practice time

&nbsp;
## Problem Statement
Create a reactive hockey training device for players to practice against, removing the need for a human goalie.

## Functions and Goals
- Must have an e-stop button accessible from behind the net.
- Must have remote e-stop capabilities.
- Block, deflect, or capture pucks that are shot towards a hockey net.

## Constraints
- IP54 water and dust resistance.
- Must be able to operate in temperatures from -20 °C to 40 °C.
- Must CSA electrical safety approved.
- Must CSA hockey safety rated (must be able to withstand the impact of a high velocity puck).
- Must be able to be powered of a single 10 A, 120 V circuit.

## Objectives
- Complete the project using a total budget of $3000 or less.
- Be able to move across the crease in less than 2 seconds.
- Be able to react to an incoming puck in less than 20 ms.
- Successfully identify the puck in 98% of frames caputered by the vision system when in view and within 6 meters.
- Obstruct the same portion of the surface area of the net as an average \[insert league here eg. Junior B] goalie.

## Criteria

&nbsp;
## Design Log

|                     | All                                             | Andrew Willms                                                                                                                 | Christian Bergmann | Erik Smith | Jonathan Gervais | Josh Cooke |
| ------------------- | ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------ | ---------- | ---------------- | ---------- |
| **Week 0**<br>09/03 | Finalized team.                                |                                                                                                                               |                    |            |                  |            |
| **Week 1**<br>09/08 | Created the problem statement. | Consulted professor [Russell Buchanan](https://uwaterloo.ca/mechanical-mechatronics-engineering/profile/r6buchan) about CV options.<br> Sourced IR lights and cameras for evaluating CV implementations. | Set up project management processes. | Started compiling a list of solution agnostic materials (e.g. power supply, generic construction materials) to obtain a rough budget estimate. | Spoke with hockey players and coaches to asses community needs. | CADed hockey net and crease to improve our understanding of the physical constraints of a hockey rink. |
| **Week 2**<br>09/15 | Finalized constarints and criteria. | Began construction of a test rig for the vision systen. | Constructed a small scale visual model of the net to aid in visualization of size and angles. | Researched motor and motor control options. | Created motor torque calculator to help evaluate the theoretical performance of different motors and gear reduction combinations. | Lead creating the constraints and criteria. |
