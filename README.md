
# dig333-devlog

#### Weeks: [1](#week-1) [2](#week-2) [3](#week-3) [4](#week-4) [5](#week-5) [6](#week-6) [7](#week-7) [8](#week-8) [9](#week-9) [10](#week-10) [11](#week-11) [12](#week-12) [13](#week-13) [14](#week-14) [15](#week-15)










<!--
BELOW IS A WEEKLY TEMPLATE. COPY/PASTE IT TO ADD A WEEK. SEE ASSIGNMENTS FOR DETAILS 
https://docs.google.com/document/d/1PAoPz-3vDPFWS5q9RHRb-dC7T4earpFXJW8w6v9wfZ0/edit
-->

## Week 1

### Context

- The TedX video by Tom Igoe mentions alot of objects that have been created with his Arduino project. There have been many open sourced machines that have been created that are similar to the Arduino. There are also many bad things that have come out of this tech revolution like credit card skimmers.
- "The devices that we make and the devices that we use, what they do matters less than the relationships that we make through them and how they change our relationships."
- There are so many positive uses that came out of physical computing.
- Do the bad computers ever outweigh the good computers?






## Week 2

### Context

- The article "The Internet of Things: Roadmap to a Connected World" describes how the connectivity of our devices has grown and is projected to continue to grow in the oncoming years. The article mentions how there are problems associated with the privacy and security of people as the network continues to grow, as well as advancements in society like self-driving cars. The article "The Internet of Things has a Dirty Little Secret it's not really ours" describes how there are so many new and innovative products that serve little to no purpose and need an internet connection to complete basic tasks. This becomes a problem when the internet or electricity goes out though. 
- “Companies should step up and guarantee the longevity of their products, no matter the cost or bind it might put them in."
- I agreed with the author of,"The Internet of Things has a Dirty Little Secret it's not really ours" about how there are so many simple products that have been unnecessarily complicated. 
- I would like to know why people continue to buy these products even though they become more of a headache than their old fashioned versions.

### Experiments

### Platt Chapter 1: Experiencing Electricity

1. Experiment 1: Taste the Power!
    1. ![image](https://user-images.githubusercontent.com/89601540/153111022-e5c88fc5-ed34-4256-9568-f4d352618187.png)

    2. If the voltage is constant, and the resistance is increased, the current is decreased.
    3. What happens to the voltage if the current of a circuit is increased, but the resistance remains the same.
2. Experiment 2: Let's Abuse A Battery!
    1. Describing Ohm's Law using the water analogy.
        a. Voltage can be thought of as the height of the water level above the whole where water flows out. The volume of the water is irrelevant though.
        b. The resistance can be thought of as the area of the hole that water is spewing out of.
        c. The current can be thought of as the amount of water exiting the hole.
    2. Matching the units for voltage, current, and resistance
        a. Voltage is measured in volts.
        b. Current is measured in Amps.
        c. Resistance is measured in Ohms.
    3. Understanding three differences between AC and DC.
        a. AC current oscillates sinusoidally, sometimes going negative or zero.
        b. AC current is better for transmitting electrons long distances, because they don't really "travel", they more or less just oscillate within a conductor.
        c. Most simple electronic circuits use DC.
    4. An important concept is the difference between AC and DC.
    5. In the water analogy, why is the current of the water flowing out not dependent on the volume of water above the hole?
3. Experiment 3:Your First Circuit
    1. ![image](https://user-images.githubusercontent.com/89601540/153105195-df75d89e-a502-450f-96fe-deb03c950de4.png) 
    2. The resistor I used was brown, black, orange, gold.
    3. brown = 1, black = 0, orange = x1000, and gold = +- 5%.
    4. The resistor is 10,000 ohms.
    5. ![image](https://user-images.githubusercontent.com/89601540/153111080-2d1a753f-668e-4347-922a-4bf2743fd889.png)
    6. The resistor can be place before or after the LED.
    7. An important concept was understanding how to create circuits, and how electrons flow through the circuits.
    8. What could you do to increase the luminosity of the LED?
4. Experiment 4: Varying the Voltage
    1. ![image](https://user-images.githubusercontent.com/89601540/153111129-8763e2b0-b2c8-4bcf-ae14-28065e2e1cca.png)
    2. Polarity is essentially the voltage or potential difference between two points of a circuit.
    3. You can check the voltage across parts of a circuit by connecting the multimeter in parallel with components of a circuit.
    4. You can measure the current at a point in your circuit by hooking up the multimeter in series in your circuit.
    5. There was about 1V of potential through the resistor and .0001A of current before the resistor.
    6. V= I x R. R = V/I. R = 1V/.0001A. R = 10k ohms.
5. Experiment 5: Let's Make a Battery
    1. Power(watts) = I x V.
    2. Batteries in series.
        a. Voltage increases as well as power.
    3. Batteries in parallel.
        a. Current increases as well as power.
        
    
### Monk Chapter 1: Setup and Management

1. Selecting a Model of Raspberry Pi
    1. Different uses for Raspberry Pi
        a. Raspberry Pi 3 B+ is a good general purpose pi.
        b. Raspberry Pi Zero W is good for single projects.
2. Enclosing a Raspberry Pi
    1. Connections on the underside of the circuit board could easily become shorted.
3. Selecting a Power Supply
    1. The standard operating voltage is 5V.
    2. You would like at least 1A of current, if you have more. The raspberry pi will only use as much as it needs so it won't be wasted.
    3. The raspberry pis can become hot and might be damaged, or just simply fail.
4. Selecting an Operating System
    1. Raspbian is the standard distributor of the raspberry pis.
5. Installing an Operating System Without NOOBS
    1. Don't use the preinstalled images or your raspberry pi won't work well.
6. Using a Composite Video Monitor/TV
    1. There is HDMI and composite outputs. HDMI is a much higher quality of output than the composite.
7. Maximizing Performance
    1. Pro - Makes your raspberry pi faster.
    2. Con - It consumes more power and risks overheating
8. Changing Your Password
    1. Default password is raspberry and you can change it using the configuration utility.
9. Shutting Down Your Raspberry Pi
    1. Sudo is a raspberry pi command used to give instructions to your raspberry pi.
    2. Type the command $ sudo reboot
    3. Pulling the plug can corrupt some files that were writing to the sd card.

## Week 3

### Context

- The "Critical Engineering Manifesto" is a bunch of rules that engineers are supposed to follow that also describe the job they do. The "Artistic Profile: Julian Oliver" is an interview of Julian Oliver where he comments on open source programs. "All Watched Over by Machines of Loving Grace" tells us about how Rand affected the economy.
- "The Critical Engineer considers any technology depended upon to be both a challenge and a threat. The greater the dependence on a technology the greater the need to study and expose its inner workings, regardless of ownership or legal provision."
- I thought this quote was interesting because of the development of AI and how there are alot of situations where computers can complete tasks better than humans.
- What are some of the downfalls of an overreliance on AI.



### Experiments

<!-- List each Platt experiment / Monk recipe outcome, adding notes, photos, schematics, captions to show your work. -->

1. Name of the experiment
    1. Text, photos, etc.
    1. Describe the most important thing you learned (to share in class)
    1. Write a quiz question (which we will discuss in class)

### Platt Chapter 2: Switching Basics and More

1. Necessary Items For Chapter 2
    1. ![IMG_8176](https://user-images.githubusercontent.com/89601540/155003566-ee53f7d6-b80e-4889-ac82-86c6cc79dc79.jpg)

    2. Above from left to right the tool names are, pliers, wire stripper, and wire cutter.
    3. I couln't find any wire, but you just run it through the whole with the correct gauge and pull it hard with a pliers.
    4. I couln't find the capacitor, transistor, switch nor the relays, but there were trimpots. I do know what the other four look like though.
    5. Are you able to cut a wire with the wire stripper?
2. Experiment 6: Very Simple Switching
    1. The SPST switches have two terminals, with options to either connect the two terminals, or to not connect them. The SPDT switch has three terminals, with options to either connect the middle pole to the left throw or to connect the middle pole to the right throw.
    2. ![circuit](https://user-images.githubusercontent.com/89601540/154182960-c2e8580e-5413-4804-b0fa-d2d38fa6cfc5.PNG)

3. Experiment 7: Relay-Driven LED's
    1. 



### Monk Chapter 2: Networking
1. Introduction
2. Connecting to a Wired Network
    1. ssh pi@mitchpi
3. Finding your IP Address
    1. $ hostname -I
    2. $ ifconfig
4. Setting a Static IP Address
5. Setting the Network Name of a Raspberry Pi
    1. You can use the Raspberry Pi configuration tool by going to menu -> Preferences -> Raspberry Pi Configuration -> System.
6. Setting Up a Wireless Connection
    1. Network Icon -> Select the Wifi connection you want -> type in your password
7. Connection with a Console Lead
    1. Go to Menu -> Preferences -> Raspberry Pi Configuration -> Interface
8. Controlling the Pi Remotely with SSH
    1. Connecting - $ ssh pi@mitchpi
    2. Disconnect - $ shutdown
    3. $ sudo raspi-config configures your raspberry pi.
    4. ls - lists all directories.
    5. cd - traverses directories



## Week 4


### Context

- Summarize the article(s) in 3-4 sentences. Also include...
- 1 quote from the reading(s)
- 1 related comment on the reading(s)
- 1 related follow-up question (what question does it bring up for you?)


### Experiments

<!-- List each Platt experiment / Monk recipe outcome, adding notes, photos, schematics, captions to show your work. -->

1. Name of the experiment
    1. Text, photos, etc.
    1. Describe the most important thing you learned (to share in class)
    1. Write a quiz question (which we will discuss in class)
