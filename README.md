# Realtime Color Sensor using Particle Photon

The realtime color sensor using photn senses the color of the object that you want the RGB value of and displays it on an OLED display connected to the photon.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Things you will need to get this to work:

1. Particle Photon
2. OLED Display
3. Flora Color Sensor
4. saishColorSensor.ino file
5. saishColorSensorInputVisualization.html file for displaying the input visualization.

### Circuit Diagram



### Installing

1. Connect the OLED Display and the flora color sensor as shown in the circuit diagram.
2. Flash the code from the saishColorSensor.ino to the photon either using the particle cloud IDE or locally.
3. Power up the photon and wait for it to connect to the internet.
4. Once it is connected to the internet, the rgb values will be displayed on the oled display.
5. For the input visualization open the saishColorSensorInputVisualization.html file on your web browser and notice the change in color of the bouncing ball.
6. That's all!


## Running the tests

Once the photon is powered up, open the terminal and type in "particle serial monitor" without the quotes.
 - If you are getting the values in the form (eg: 77, 79, 90), your input is working fine.
 - If you are getting "data: 77, 79, 90", your subscription to the cloud is working fine.
 - If you are getting the output on the OLED display in the form - "rgb(77, 79, 9)", then everything is working fine.

### Break down into end to end tests

The above tests are used to make sure that the input and output are working fine in collaboration.

## Deployment

No additional requirements are necessary except that you should flash the code to the photon and then open the "saishColorSensorInputVisualization.html" file to view the visualization - the color of the bouncing ball changes.

## Built With

* Particle Photon Maker Kit - [https://store.particle.io/]
* Visualization is done using d3.js - [https://d3js.org/]
* Bouncing beach ball visualization got from "datavizclub.tumble.com" = [http://datavizclub.tumblr.com/post/119132679558/make-a-bouncing-beach-ball-with-d3]


## Authors

* **datavizclub.tumble.com** - *Initial visualization work* - datavizclub.tumble.com
* Saish Menon - RIT


## License

Open Licence

## Acknowledgments

* Thanks to datavizclub.tumble.com - beach ball visualization
