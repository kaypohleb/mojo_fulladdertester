# Full Adder Testing using Mojo V3
Are you too lazy to test whether your full adder works? Are your fingers too fat to shift the DIP switches? Don't worry! We have created this Mojo tester just for you! 

## Set-up of Mojo
### Outputs of Mojo:
- P51: For input A of full adder
- P41: For input B of full adder
- P35: For input C of full adder

### Inputs of Mojo:
- P120: For output Carry of full adder
- P118: For output Sum of full adder

### IO_DIP Switch Allocations:
- DIP 23: Control input A of full adder (when in Manual Mode)
- DIP 22: Control input B of full adder (when in Manual Mode)
- DIP 21: Control input C of full adder (when in Manual Mode)
- DIP 16: Switches between Modes: 1 represents Automated Mode; 0 represents Manual Mode

### IO_LED Allocations: 
- LED 23: Represents input A of full adder
- LED 22: Represents input B of full adder
- LED 21: Represents input C of full adder
- LED 16: Represents current Mode: lit represents Automated Mode; unlit represents Manual Mode

- LED 7: Represents output Sum of full adder
- LED 6: Represents output Carry of full adder
- LED 0: Represents if the full adder is functioning correctly according to the output and input
