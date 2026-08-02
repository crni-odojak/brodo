Regarding the 94P relays, the following applies:

Like the 86E and 86R relays, the 94P1 and 94P2 relays are electromechanical tripping devices whose activation depends on specific trigger signals. They also have particular sequences for the partial shutdown of the generating units, which are described below:

1. Partial shutdown relay 1 94P1: These relays operate by unloading the machine and then opening the unit's circuit breaker. The machine remains running with energization. This operation is primarily performed due to generator or transformer overload.

2. Partial shutdown relay 2 94P2: These relays trip the machine based on functions such as 32, 40, 81, 27, 24, 46, and 78, which require the immediate tripping of both the unit's circuit breaker and the excitation circuit breaker. This clears the fault, leaving the unit running without energization.

3. Sequence of Partial Shutdown 1: This program is executed by the unit controller as a backup protection measure when a condition requiring unit discharge is detected by relay 94P1.

The unit will be discharged and then disconnected from the system, remaining in a no-load, energized speed state, controlled by the speed and voltage regulators. When normal conditions are restored, relay 94P1 will automatically reset, and the appropriate commands can be issued to the equipment to reconnect the unit to the system and complete the synchronized start sequence.

This program is designed to discharge and disconnect the unit from the system in case of over-temperature in the generator or transformer.

4. Partial Shutdown Sequence 2: This program will trip the circuit breaker associated with the unit, as well as the circuit breaker at the substation connecting to the National Interconnected System (SIN), leaving the unit without power and running unloaded. Depending on the fault condition, the operator can choose to reconnect the unit or perform a normal shutdown. The program will be This function is executed as confirmation of the operation of the partial shutdown relay 2 of unit 94P2, which directly performs the protection function.

This function is intended for abnormal operations in the electrical system or generating unit, such as loss of excitation, high and low voltage, reverse power, and unbalanced load operation, in which a disconnection from the electrical grid and the excitation system is required without causing a complete shutdown of the unit.

The following is stated in IEEE Std C37.2 – “IEEE Standard for Electrical Power System Device Function Numbers, Acronyms, and Contact Designations”, section 3.1.94 “Device number 94—tripping or trip-free relay”:

“A self-resetting device that functions to trip a circuit breaker, contactor, or piece of equipment; to permit immediate tripping by other devices; or to prevent immediate reclosing of a circuit breaker if it should open automatically, even though its closing circuit is activated or energized.”

Translation:

“Automatic reset device whose function is to trip a circuit breaker, contactor, or other equipment; allow immediate tripping by other devices; or prevent the immediate reconnection of a circuit breaker if it automatically opens, even if its closing circuit is energized or powered.”

Similarly, the protection and tripping philosophies for generators are stipulated in IEEE Std C37.102, which is referenced in section 4.8.1 of the technical specifications.

It should be noted that the generator manufacturer may have a different name for the tripping function associated with relay 94. Therefore, the description of the sequence normally assigned to the device within the protection functions is included, in accordance with IEEE standards. Verification with the manufacturer is requested. Finally, the technical specifications, section 4.8.3.4 “Master Blocking and Tripping Relay,” stipulate that:

“The protection system shall include two master blocking and tripping relays (86E1 and 86E2) to manage emergency shutdowns associated with the protection functions implemented in the protection relays of the generators, the main step-up transformer, the outdoor substation, and signals from general and auxiliary equipment.” The distribution of functions in the master blocking and tripping relays will be determined by the corresponding design of the electrical protection system and associated systems.

The resetting of the blocking and tripping relays must be possible both automatically and manually. (Emphasis added).

In this regard, it is understood that the distribution of functionalities, sequences, interlocks, and triggers in the master block and trip relays is part of the detailed design that the Contractor must develop. Partial shutdowns of the generating units (94P), as well as the emergency shutdown (86E, electrical trip) and rapid shutdown (86R, mechanical trip), are functionalities attributable to the master relays.