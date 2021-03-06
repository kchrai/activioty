# Checkpoints

*Checkpoints* are those components of Activ-IoTy that performs timekeeping activities. They are 'virtual gates' where competitors check-in to complete the full itinerary of the race.

The objective of a *checkpoint* is to register what competitor is at that location and the time when they checked in.

Checkpoints are fully configurable and can be made of different IoT components to satisfy the requirements of the race.

For this pilot, I developed several *checkpoints* with different devices and platforms to simulate a wide range of racing scenarios.

* [Checkpoint 1: RFID Reader + Raspberry Pi + Python](./rfid-reader-python/)
* [Checkpoint 2: Bluetooth Keypad + Raspberry Pi + Python](./bluetooth-keypad-python)
* [Checkpoint 3: IR Remote + Arduino Uno](./ir-arduino/)
* [Pseudo-checkpoint (on the move): Fona 3G + Arduino Lilypad](../tracking)
