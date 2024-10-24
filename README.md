The following requirements exists for this project:

Parking garage system
- R1: The system should be able to park units of type "car"
- R1.1: Each car has a unique ID of alphanumeric characters
- R1.1.1: The max length of the ID is 8.
- R1.2: Cars can have one of two types, "electric" or "gas"
- R2: Each parkinglot (spot) has one of two types, "electric" or "gas"
- R2.1: Cars of the type "electric" can park in any free spot.
- R2.2: Cars of type "gas", can only park in free spots of type "gas"
- R3: Cars entering and leaving have the timesstamp recorded
- R3.1 Timestamp is described in R7.1
- R4: Each type of car has a different price per hour of parking
- R4.1: When a car leaves, they pay a price based on how long they were parked
- R5: A singular controller should manage the system
- R5.1: Before a car can enter, the controller checks that space is available
- R5.2: Cars are registered by the controller, when they enter and leave the garage
- R5.3 A car cannot enter, if there are no free spots available
- R6: Cars parking position is determined by a coordinate (x, y, z)
- R7: A "day" is equal to 24 *stepLength* (int) from the **timer** class.
- R7.1: The *stepLength* value will be used to calculate timestamps of parking (entering) and leaving.
- R7.1: After each day, the correct total revenue should be calculated, according to the registered cars -- Maybe
kjiIiinsee