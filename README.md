# theElectronicDiceGame


The Dice Game is used to demonstrate Eli Goldratt's 'Theory of Constraints'. The game is a powerful learning exercise that demonstrates the impact of variability and dependency on throughput and work-in-process inventory. The insights obtained by playig this game cn also be extended to a service or supply chain context.

The setup models a simple factory having 8 machines, each with a capacity to produce between 1 and 6 units per day.
For each workstation, a single electronic die is rolled. The workstation can process that many pieces (if they are available in queue).The station will ship the lesser of the die roll and the number of pieces that are waiting to be processed. For example, if 6 pieces are waiting and the die roll is 2, the station will ship 2 pieces. If only 3 pieces are waiting and the die roll is 5, then 3 pieces will be shipped.

Each workstation starts with 4 pieces in stock. Therefore, in theory, the manufacturing line "should" be able to ship an average of 3.5 pieces per turn. The game supports realtime visualisation of the parts moving through the system in each round, the parts currently in system and other statistics like total throughput, average throughput etc. in the form of a bar graph.
