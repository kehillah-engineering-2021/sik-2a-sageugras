# Circuit 2a
## By sageugras

### Introduction
In this circuit, you'll use the RedBoard and a small buzzer to make music, and you'll learn how to program your own songs using arrays.
### How to Run Code
#### Parts needed:
![2Aparts](https://user-images.githubusercontent.com/54454824/95892791-e4ee8300-0d3b-11eb-9a1f-159dadec2515.png)

#### New Component:
##### Buzzer
![Buzzer1](https://user-images.githubusercontent.com/54454824/95892797-e61fb000-0d3b-11eb-8f24-9496669d046c.jpg)

The buzzer uses a small magnetic coil to vibrate a metal disc inside a plastic housing. By pulsing electricity through the coil at different rates, different frequencies (pitches) of sound can be produced. Attaching a potentiometer to the output allows you to limit the amount of current moving through the buzzer and lower its volume.

#### New Concepts:
##### Reset Button
![reset2](https://user-images.githubusercontent.com/54454824/95893091-4f9fbe80-0d3c-11eb-8096-ef90d6333b8a.jpg)

The RedBoard has a built-in reset button. This button will reset the board and start the code over from the beginning, running what is in setup() and then loop().
##### Tone Function
To control the buzzer, you will use the tone function. This function is similar to PWM in that it generates a wave that is of a certain frequency on the specified pin. The frequency and duration can both be passed to the tone() function when calling it. To turn the tone off, you need to call noTone() or pass a duration of time for it to play and then stop. Unlike PWM, tone() can be used on any digital pin.
##### Arrays
Arrays are used like variables, but they can store multiple values. The simplest array is just a list. Imagine that you want to store the frequency for each note of the C major scale. We could make seven variables and assign a frequency to each one, or we could use an array and store all seven in the same array, as shown below. To refer to a specific value in the array, an index number is used. Arrays are indexed from 0. For example, to call the first element in the array, use array_name[0];; to call the second element, use array_name[1]; and so on.

#### Hardware Hookup
##### Buzzer
![buzzer_polarity](https://user-images.githubusercontent.com/54454824/95893397-c046db00-0d3c-11eb-948d-8d9eb00ff5b2.jpg)

The buzzer is polarized. To see which leg is positive and which is negative, flip the buzzer over and look at the markings underneath. Keep track of which pin is where, as they will be hard to see once inserted into the breadboard. There is also text on the positive side of the buzzer, along with a tiny (+) symbol.

##### Volume Knob
All of the circuits in Project 2 make use of a potentiometer as a rudimentary volume knob. Notice that only two of the potentiometer's legs are used in these circuits. In these instances, the potentiometer is acting as a variable resistor, limiting the amount of current flowing to the speaker and thus affecting the volume as you turn the knob. This is similar to the current-limiting resistor used to limit current to the LED in circuit 1A --- only this time the resistance is variable.

Ready to start hooking everything up? Check out the circuit diagram and hookup table below to see how everything is connected.

##### Circuit Diagram
![SIK_Circuit_2A_buzzer](https://user-images.githubusercontent.com/54454824/95893401-c1780800-0d3c-11eb-900d-6749dd322b14.jpg)

### Code Explanation


### Code in Action


