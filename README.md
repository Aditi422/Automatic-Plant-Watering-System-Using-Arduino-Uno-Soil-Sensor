# Automatic-Plant-Watering-System-Using-Arduino-Uno-Soil-Sensor

### Smart Garden Irrigation System

Welcome to the Smart Garden Irrigation System repository! This project aims to provide an automated solution for watering your garden based on soil moisture levels and sunlight intensity. Below, you'll find details on the major components used in the build.

#### Components Used:
- **Arduino Uno:** The brain of the system, responsible for controlling various sensors and actuators.
- **4 channel relay board:** Used for controlling water flow to different sections of the garden.
- **Soil sensor:** Measures soil moisture to determine watering needs.
- **Jumper wires:** Connect various components together.
- **9V Power Supply:** Provides power to the Arduino and other components.

#### General Circuit Information:
- **Soil Moisture Sensors:** Moisture sensors that measure the resistance or conductivity across the soil matrix between two contacts are essentially junk.
- First of all, resistance is not a very good indicator of moisture content, because it is highly dependent on a number of factors which might vary from garden to garden including soil ph, dissolved solids
in the water, and temperature. Second, most of them are of poor quality with contacts that easily corrode. For the most part you'd be lucky to get one to last through an entire season. Capacitive sensors
are generally more accurate because they are just measuring the change in dialetric properties of the soil which is less sensitive to other environmental factors. They also don't require any exposed
conductive surfaces which means they can last a bit longer in the harsh environment of backyard.

#### Final Thoughts:
After sharing this project with the community, I received valuable suggestions and had some insights of my own. Here are a few considerations:
- Learning Opportunity: This project served as a valuable learning experience.
- Wireless Monitoring: While feasible, wireless monitoring wasn't implemented due to complexity.
- Solenoid Placement: Consider mounting the solenoid directly on the hose bib to reduce water hammer.
- Garden Tips: Addressing concerns such as soil against house siding and choice of mulch.
- Combining Technology and Gardening: Leveraging technology to simplify and enhance gardening practices.

Feel free to explore the code and documentation in this repository. Your feedback and contributions are highly appreciated!

Happy Gardening,
ADITI GHOSH.
