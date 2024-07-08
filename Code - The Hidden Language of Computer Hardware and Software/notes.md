### Chapter 1: Best Friends
- Introduces the founding of Morse Code.
> The key word here is two. Two types of blinks, two vowel sounds, two different anything, really, can with suitable combinations convey all types of information.

### Chapter 2: Codes and Combinations
- Walks over the morse code language.
> Combinations of binary objects (such as coins) and binary codes (such as Morse code) are always described by powers of two. Two is a very important number in this book.

### Chapter 3: Braille and Binary Codes
- Braille used a binary system which multipurposed the letters 'a' through 'j' to prevent adding more than 6 dots/cells, which i found very similar to language, as many things are repurposed in different situations to prevent redundancy in a sense.

Thoughts: The key here for the first three chapters were obviously emphasising the importance of binary code, which will later likely relate to the binary system used in computer architecture of gates and such, which i am looking forward to. 

### Chapter 4: Anatomy of a Flashlight
- Introduces the concept of electricity through the analysis of how a flashlight works.
- Electricity flow is the passage of electrons, precipitated by an initial movement, usually the battery.
- Although a bad analogy, the water and pipe analogy helps explain elementary electricity:
> Current is similar to the amount of water flowing through a pipe. Voltage is similar to the water pressure. Resistance is similar to the width of a pipe—the smaller the pipe, the greater the resistance. So the more water pressure you have, the more water that flows through the pipe. The smaller the pipe, the less water that flows through it. The amount of water flowing through a pipe (the current) is directly proportional to the water pressure (the voltage) and inversely proportional to the skinniness of the pipe (the resistance).

- E = I/R 
Where I represents current in amperes, E represents voltage, and R represents resistance.

> Either the switch is closed or it’s open. Either current flows or it doesn’t.Either the lightbulb lights up or it doesn’t.Like the binary codes invented by Morse and Braille, this simpleflashlight is either on or off. There’s no in-between. This similarity betweenbinary codes and simple electrical circuits is going to prove very useful inthe chapters ahead.

### Chapter 5: Communicating Around Corners
- Introduces basic electrical circuit terminology, and the evolution of communication across long distances. 

### Chapter 6: Logic with Switches
- Explaining logic with boolean algebra
- Boolean operations union and intersection can be represented in electrical circuitry from switches in parallel or series.

### Chapter 7: Telegraphs and Relays
- To create a telegraph to facilitate long distance communication, and to mitigate the limitation of long distance-wiring, relays were invented. 
- Relays use the input signal to power a coil of wire that causes the iron bar to beocme an electromagnet, pulling down a metal plate, which resends the signal in real-time ti the output wire. 
- They essentially re-send weak signals as strong signals, resetting its voltage to mititgate long-distance issues with wiring.

### Chapter 8: Relays and Gates
- Two relays can form an AND and OR logic gates.
- A single relay is called a buffer, strengthening signals that have branched off, while an inverter outputs the opposite of the input
- A combination of the AND, OR, and inverter (NOT), creates the NAND and NOR gates.
- Boolean expressions can always be expressed using logic gates, whether simplified or not.

### Chapter 9: Our Ten Digits
- Dives into the history of number systems.
- Our base 10 number system supposedly originating from the number of fingers we have.
- This arbitrary allocation may not fit the use for other beings where they dont have 10 fingers or different needs.

### Chapter 10: Alternative 10's
- Worked the way down to the simple binary system, looked at how batches of three bits could be used to convert the decimal number into octal
- AND gates can be used to create a device that encodes the decimal based on input switches simulating binary positioning
- OR gates can be used to create its decoder counterpart

### Chapter 11: Bit by Bit by Bit
- Looks at real world uses of binary representation, such as the perseverence Mars rover's parachute, barcodes, and QR codes.
- Barcodes and QR codes have their multiple of their own agreed upon standards, as well as many aspects that enforce error checking and prevents tampering.

### Chapter 12: Bytes and Hexadecimal
- Bytes are 8 bits, and is always the multiple for computer word sizes, but reading the binary of multiple bytes is difficult and long, thus introducing the hexademical number system, which each bit can represent 4 bits in binary, this each byte being represented by two hexadecimal symbols. The octal number system does not work as not all bytes and combinations of bytes are divisibale by 3. 
- Hexadecimal is commonly used to represent RGB colour prefixed by a # symbol.

### Chapter 13: From ASCII to Unicode
- 