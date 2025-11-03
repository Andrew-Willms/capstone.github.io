# GOAL-E
#### MTE 481 — Mechatronics Engineering Design Project
_Andrew Willms, Christian Bergmann, Erik Smith, Jonathan Gervais, Josh Cooke_

&nbsp;
## The Needs We Have Observed
- Hockey goalies are often in very high demand for training.
- Many types of practice (such as shooting practice):
  - are very tiring for the goalie,
  - pose a substantial injury risk to the goalie, and
  - are not valuable training for the goalie.
- This leads to goalies not wanting to practice for long or deliberately missing practice.
- Current tools to substitute for goalies are simple static elements. These elements:
  - are a poor substitution, providing less valuable practice and
  - are less engaging, leading players not making a full effort.
- Baseball has created realistic pitching systems that enable hitters to practice without a pitcher. 
- Creating a similar tool for hockey would:
  - reduce goalie fatigue
  - reduce goalie injury risk
  - enable types of practice that pose a high risk of injury to goalies (such as slapshot practice)
  - increase player engagement during drills
  - greatly increase the amount of time players are able to practice

&nbsp;
## Problem Statement
Create a reactive hockey training device for players to practice against, removing the need for a human goalie.

## Functions and Goals
- Must be able to block, deflect, or capture pucks that are shot towards a hockey net.
- Must be able to operate autonomously.
- Must have an e-stop button accessible from behind the net and from a remote.
- Must sense the position of the puck before it is shot and move to minimize the open portion of the net.

## Constraints
- IP54 water and dust resistance.
- Must be able to operate in temperatures from -20°C to 40°C.
- Must be able to withstand repeated 80km/h slapshots.
- Must be electrical safety approved.
- Must be able to be powered off of a single 10A, 120V circuit.
- Must be able to complete the project before symposium.

## Objectives
- Complete the project using a total budget of $3000 or less.
- Be able to move across the crease in 2 seconds or less.
- Be able to identify unobstructed pucks within 20m with an accuracy of 95% or greater.
- Be able to identify pucks and estimate their postion in 50ms.
- Be able to identify the position of the puck within 5% of the distance to the puck.
- React correctly to 95% of unobstructed 50km/h shots taken from 3-20m away.
- Obstruct the same area of the net as an average junior or adult goalie.
- Be vulnerable to and effective against the same scoring strategies that human goalies are.
- The design should encourage players to play against it in the same way they would play against a human goalie.

## Criteria
- Cost (CAD)
- Effort to complete (/10)
- Cross-crease time (s)
- Puck identification accuracy (%)
- Puck position estimation time (s)
- Puck position estimation accuracy (%)
- Human-like feel and effectiveness (/10)

&nbsp;
## Design Log

| **Week** | All                                 | Andrew Willms                                                                                                                                                                                            | Christian Bergmann                                                                                                                                                        | Erik Smith                                                                                                                                     | Jonathan Gervais                                                                                                                  | Josh Cooke                                                                                                                                                                |
| -------- | ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 09/07    | Created the problem statement.      | Consulted professor [Russell Buchanan](https://uwaterloo.ca/mechanical-mechatronics-engineering/profile/r6buchan) about CV options.<br> Sourced IR lights and cameras for evaluating CV implementations. | Set up project management processes.                                                                                                                                      | Started compiling a list of solution agnostic materials (e.g. power supply, generic construction materials) to obtain a rough budget estimate. | Spoke with hockey players and coaches to asses community needs.                                                                   | CADed hockey net and crease to improve our understanding of the physical constraints of a hockey rink.                                                                    |
| 09/14    | Finalized constraints and criteria. | Began construction of a test rig for the vision system.                                                                                                                                                  | Constructed a small scale visual model of the net to aid in visualization of size and angles.                                                                             | Researched motor and motor control options.                                                                                                    | Created motor torque calculator to help evaluate the theoretical performance of different motors and gear reduction combinations. | Lead creating the constraints and criteria.                                                                                                                               |
| 09/21    | Brainstormed designs.               | Compared the amount of ambient light in 850 and 940nm wavelengths.                                                                                                                                       | Reached out to more hockey teams and players and collected quotes.                                                                                                        | Worked on sketches for the design proposal.                                                                                                    | Worked on sketches for the design proposal.                                                                                       | Worked on preliminary designs.                                                                                                                                            |
| 09/28    |                                     | Began creating CV application to gather and process test footage.                                                                                                                                        | Contacted the Motion Research Laboratory and [John McPhee](https://uwaterloo.ca/systems-design-engineering/profile/mcphee) regarding the possibility of borrowing motors. | Worked on sketches for the design proposal.                                                                                                    | Worked on sketches for the design proposal.                                                                                       | Contacted the Motion Research Laboratory and [John McPhee](https://uwaterloo.ca/systems-design-engineering/profile/mcphee) regarding the possibility of borrowing motors. |
| 10/05    | Preparation for preliminary design presentation | Developed slides for constraints, objectives and criteria. | Compiled gathered quotes for presentation. Updated gantt chart for presentation. Created slides for patent analysis. | Updated sketches for presentation and created related slides. | Updated sketches for presentation and created related slides. | Created slides for problem statement and opening of presentation. |
| 10/12    | Reading week. PDP preparation. | | | | | |
| 10/19    | Midterms | | | | | |
| 10/26    | Design analysis and calculations. | Researched control system options and derived formulas for system dynamics. Sourced motors and speed controllers for testing. Aided in torque and electrical power requirement calculations. | Aided in motor torque analysis. Developed CAD for the goalie and the arm mechanism. | Researched power supply options, calculated voltage and current requirements, and worked on electrical schematics. | Aided on more in depth conceptualization of goalie mechanism on end of arm, relating to motion of arms and lower body. | Finalized torque requirements and ideal gear ratios. Began designing a capstan speed reducer to meet the torque requirements. |
