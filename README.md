
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
    1. The SPST switches have two terminals, with options to either connect the two terminals, or to not connect them. The SPDT switch has three terminals, with options to either connect the middle pole to the left throw or to connect the middle pole to the right throw. The pole is in the middle of the switch where the power is connected to.
    2. ![circuit](https://user-images.githubusercontent.com/89601540/154182960-c2e8580e-5413-4804-b0fa-d2d38fa6cfc5.PNG)
    3. Insert image of the double switch 
3. Experiment 7: Relay-Driven LED's
    2. When I'm not pressing the button, the first LED is lit up.
    3. Insert image of pressed button
    4. When I am pressing the button, the second LED is lit up. When I release it, the first LED is lit up and the second goes out.
    5. Insert image of no lights
    6. This is the circuit I built
4. Experiment 8: A Relay Oscillator
    1. Think of a resistor as a faucet and the capacitor as a balloon that is filling up with water. The balloon stops filling with water when the pressure inside the balloon is equal to the pressure in the pipe, regardless of how quickly the balloon fills up. The capacitor quits charging when it's voltage is the same as the supply's voltage. The resistance between the power supply and capacitor determines how quickly the capacitor charges.
    2. Capacitors that are large can hold a large voltage and can zap you if you touch it. 
    3. Capacitors can blow up if they are connected with the wrong current direction. 
    4. Insert image of the circuit with capacitor.
    5. When I press the button, the second LED switches on and the first LED slowly switches off. 
    6. When I was switching out capacitors, the time that the LED's took to dim changed. It changed quicker with smaller capacitors that hold a smaller voltage. It took longer to discharge on larger capacitors.
5. Experiment 9: Time and Capacitors
    1. Insert image of capacitor multimeter circuit
    2. As I pushed and held the button, the circuit connected, which charged the capacitor. I could see the voltage increasing the longer I held the button down. When I released the button, the voltage slowly started to drop, discharging the capacitor.
6. Experiment 10: Transistor Switching
    1. Insert image of transistor off
    2. This is the circuit containg a transistor LED and pushbutton. When I am not pressing on the button, the circuit is not complete and the LED is not on.
    3. Insert image of transistor on
    4. When I press on the button, the LED lights up. The transisor spits out a voltage but recieves voltage from two different spots.
    



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

In "Pay for the Printer" by Philip K Dick, the setting takes place in a post apocalyptic Earth where Hydrogen bombs were dropped during a war. An alien race came to Earth and began printing new items based off of original copies, but it was not a sustainable solution, because eventually everything that was printed turns to pudding. "The Preserving Machine" also by Philip K Dick is about a machine that turns music into animals, but the animals adapted to nature and turned foul, turning the music foul with it. "I listened to the music. It was hideous. I have never heard anything like it. It was distorted, diabolical, without sense or meaning, except, perhaps, an alien, disconcerting meaning that should never have been there." I thought the stories by Dick were really interesting and thought provoking, even though both of them were pretty unrealistic. Considering the printing done in the first story, how relevant will 3D printing be in the future regarding cheap housing or easily printed products that can help alot of people for cheap.

### Experiments

### Monk Chapter 3: Operating system

1. Introduction
2. Browsing Files Graphically
    1. Using the file manager, you can drag repositories from one repostiory to another.
    2. Operates similarly to a Windows File Manager.
3. Copying Files Onto a USB Flash Driver
    1. The drive is mounted in /media/pi
    2. If you want to copy a folder, you just drag the file onto the folder representing the flash drive.
4. Starting A Terminal Session
    1. Select the terminal icon in the RPI desktop.
5. Navigating the File System Using a Terminal
    1. Prompt: Gives a parameter
    2. Path: File path between different directories
    3. Root: The root directory
    4. Home: The terminal directory
    5. Tilde: Home directory
    6. cd: Changes directory
    7. ls: Lists all files in the directory
    8. pwd: Shows the path from the current directory to the home directory
6. Copying a File or Folder
    1. $ cp myfile.txt myfile2.txt 
    2. Creates a file named myfile and copies it into myfile2
7. Renaming a File or Folder
    1. $ mv myfile.txt myfile.rtf
    2. Renames a file from myfile.txt to myfile.rtf.
8. Editing a File
    1. $ nano myfile
    2. Allows you to edit myfile
    3. Ctrl X: Saves and exits
    4. Ctrl V: Next page, allows you to edit
    5. Ctrl Y: Previous page, allows you to edit
    6. Ctrl W: Searches for a page
    7. Ctrl O: Writes the file
9. Viewing the Contents of a File
    1. $ cat myfile.txt
    2. Displays the whole file
    3. $ more myfile.txt
    4. Displays one page of the file
10. Creating a File Without Using an Editor
    1. $ echo 'file contents here' > test.txt
    2. Creates a file and allows you to edit.
11. Creating a Directory
    1. $ mkdir mydirectory
    2. Creates a new directory called mydirectory
12. Deleting a File or Directory
    1. $ rm myfile.txt
    2. Deletes file myfile.txt
13. Performing Tasks with Superuser Privileges
    1. Prefix a command with sudo to complete a task you normally can't.
14. Understanding File Permissions
    1. $ ls -l
    2. Allows you to see the permissions which is the first block of code.
    3. First section is the type of file
    4. Second section is the owner who can either read or write the file.
    5. Third section is the group which is groups of people that can read or write the file.
    6. The final section specifies permissions for people who aren't the owner or in a specified group.
15. Changing File Permissions
    1. In case you want to allow someone to execute or edit a file they don't have permission for.
16. Making a Screen Capture
    1. $ scrot -s
    2. Allows you to screenshot specified parts of your screen.
17. Installing Software with apt-get
    1. $ sudo apt-get install abiword
    2. Installs the abiword software.
19. Removing Software Installed with apt-get
    1. $ sudo apt-get remove abiword
    2. Removes the abiword software.
20. Installing Python Packages with Pip
    1. $ sudo pip install svgwrite
    2. Installs the python package svgwrite.
    3. $ sudo pip remove svgwrite
    4. Removes the python package svgwrite.
21. Fetching Files with the Command Line
    1. $ wget "Internet Link"
    2. Fetches the files from the link
22. Fetching Source Code with Git
    1. $ git clone "Git Link"
    2. Copies git files.
    3. Python file.py
    4.  git remote "URL"
    5.  git add
    6.  git commit -m "your commit"
    7.  git push
23. Fetching this Book's Accompanying Code
    1. git clone "book"      

### Monk Chapter 5: Python Basics

1. Introduction
    1. To find your raspberry pi desktop
        - Open up your pi 
            - ssh pi@mitchpi
            - password = mitchpi
        - hostname -I 
            - gets your ip address.
        - Open up remote desktop
        - insert your raspberry pi ip address
        - username is pi and password is mitchpi
3. Deciding Between Python 2 and Python 3
4. Editing Python Programs with Mu
    1. Using Thonny instead of Mu.
    2. Made the count.py file which counts from 1 to 9.
5. Using the Python Console
    1. Thonny had no REPL button, you just type 2 + 2 in the console.
7. Running Python Programs from the Terminal
8. Assigning Names to Values (Variables)
    1. Assigned example variables
    2. Don't have a type
10. Displaying Output
    1. print()
12. Reading User Input
13. Arithmetic
14. Creating String
15. Concatenating (Joining) Strings
    1. S1 = 'abc'
    2. S2 = 'def'
    3. s = S1 + S2
    4. print(s)
17. Converting Numbers into Strings
    1. str(123)
19. Converting Strings into Numbers
    1. int('-123')
    2. int('1001',2) = 9
        - Binary number
    3. int('AFF0', 16) = 45040
        - Converts hexadecimal number into integer
21. Finding the Length of a String
    1. len('abcdef') = 6
23. Finding the Position of One String Within Another
    1. s = 'abcdefghi'
    2. s.find('def') = 3
25. Extracting Part of a String
    1. s = 'abcdefghi'
    2. s[1:5] = 'bcde'   
27. Replacing One String of Characters with Another Within a String
    1. s.replace('S1', 'S2')
        - Replaces the string S1 with the String S2 within the string s
29. Converting a String to Uppercase of Lowercase
    1. 'aBcDe'.upper() = 'ABCDE'
    2. 'aBcDe'.lower() = 'abcde'
31. Running Commands Conditionally
    1. if x > 100
    2. elif x < 10
    3. else
33. Comparing Values
    1. Less than <
    2. Greater than >
    3. Less than or equal to <=
    4. Greater than or equal to >=
    5. Exactly equal to ==
    6. Not equal to !=
    7. 1 != 2 prints True
35. Logical Operators
    1. if x > 10 and x < 20
        - print('x is in the middle')
37. Repeating Instructions an Exact Number of Times
    1. for i in range(1,11)
        - print(i)
        - prints numbers 1 through 10
39. Repeating Instructions Until Some Condition Changes
    1. while answer !='X'
41. Breaking Out of a Loop
    1. type break
43. Defining a Function in Python
    - def count_to_n(n):
        - for i in range(1, n+1):
            - print(i)
    - count_to_n(5)



## Week 5


### Context

- The article "Everying Thats Inside Your Iphone" by Brian Merchant describes the different elements that are used within an Iphone and how much is used. He breaks it down and comes up with the total raw cost of the materials to be a little over a dollar. He then describes where these materials come from which is from mines in poorer countries. A significant point is that these mines are also mined by children eventhough the conditions are awful and dangerous. The article "One Man's Nearly Impossible Task to Make a Toaster From Scratch" by Rachel Swaby is about a man that wanted to create a toaster from scratch using raw materials from the Earth. He broke down the cheapest toaster he could find and noticed there were hundreds of parts and materials within it. He ends up describing where he could find the materials he needed. The article "All Watched Over by Machines of Loving Grace" by Adam Curtis is about how altruism is defined by peoples genetics. He goes on to prove his theory using certain computer algorithms. 
- Brian Merchant mentions, "In 2008 alone, sixty children were killed in mining accidents at Cerro Rico."
- I thought it was crazy how complicated and dense Iphone components were.
- Considering many people will buy the new Iphone every year, do you think some people will wait a couple years for a new Iphone if they new how the Iphones were created?


## Week 1


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
