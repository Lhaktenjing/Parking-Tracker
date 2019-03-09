# Parking-Tracker
A smarter solution to the Parking and traffic problem using NbIot
# Inspiration: 
Traffic Congestion has been one of the major challenges of big cities in the World including Seattle. From a service provider/government's point of view, it is an issue of concern because of the challenge in managing the huge flow of traffic resulting in inefficient service distribution. A study shows that almost up to 30% of the traffic in a city at a given time are drivers looking for parking spaces. And from a consumer's perspective, it will be a lifesaver as they will be able to access the availability of parking spaces hugely reducing the time and the stress they have to deal with. In addition, the ability to manipulate your payment and time duration benefits users from paying extra money or fines that might show up. And most importantly, it'll be a huge aid for the parking enforcement department as it reduces unnecessary patrolling saving a huge amount of budget is saved. Which can be invested in other sectors.

## What it does: 
For consumers: It sends users detailed information of location and available parking spaces near him/her. Help keep track of the his/her parked car. Manage payments and parking duration.

For Government/Service Provider: Keep track of parking space use up. See unauthorized parking or violation of law. Bill customers  


## How we built it:
Used ultrasonic sensor to detect the presence of a car in the space.
NbIot technology to send and receive data over SMS and cloud
Arduino 

## Challenges we ran into
NB-IoT is highly new modern technology so we had difficulties to get deeper information when we tried to do hardware programming and connect all hardware components together. Moreover, it is our first time interacting with Twilio Development Kit included the SIM card and new Arduino interface. Due to the limited resources, we did not have chance to try new features for the system such as card installation and LED Display.

## Accomplishments that we're proud of
We connected Ultra-Sonic sensor to the main board successfully as it can detect the objects nearby. For example, if a car park in a street car lot, here is the process of how Parking Tracker app:

the time meter started as the Ultra-Sonic sensor detected the car.
The LED light sends signals to users as it starts to calculate the amount of time the car is going to park.
The system records the time and notifies users through an application (IOS/Android/SMS) before the meter runs out.
It possibly notifies other departments such as Parking Enforcement, Towing Service, or Police Office if the car is violated regulations
It is the first NB-IoT smart parking tracker in WA, or in the US possibly so we feel proud that the possibility of this product can be accomplished in the most efficient way (low battery consumption, less data usage, inexpensive components)

## What we learned
The advantages of NBIot technology
Design Process of an integrated Arduino system
Twilio technology for information exchange

## What's next for Parking Tracker
- Android/Ios Application for User Interface
- A well set up payment system 
- Led Displays for information exchange
- Back End Cloud setup


