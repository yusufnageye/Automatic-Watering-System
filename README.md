The project I undertook involved the development of a moisture level monitoring and watering system using the Arduino Grove board beginner kit, with programming implemented in Java. The system was designed to periodically check the moisture level of the soil and administer water to the plant when necessary. It utilized a moisture sensor connected to the Arduino to gauge soil moisture, displaying the moisture level, status, and time on the OLED display of the Arduino board and the console.

The project was inspired by an automatic watering system observed in a garden, which included a moisture level monitoring feature. The system's technical requirements included checking the soil moisture level every hour and watering the plant if it detected dry soil. The moisture threshold for soil dryness was determined through experimentation, with a range of 500 to 600 indicating dryness.

To implement the hourly moisture level check, a time-tracking mechanism was employed, similar to an alarm system. If an hour had passed since the last check, the system would evaluate the moisture level, displaying the appropriate status (PW - plant watering or NPW - not watering plant) and updating the time. If the soil was dry, it would activate the water pump until the moisture level fell below the threshold.

During the watering process, continuous moisture level checks ensured that the pump stopped when the soil reached an acceptable moisture level. The OLED display presented the moisture level, status, and time before and after watering, but only if the soil was dry. The console continuously logged all activities, including moisture level checks and pumping times, providing a comprehensive record.

Components used in the project included the Arduino Grove board, moisture sensor, MOSFET, pump, and the plant itself. Java was the programming language of choice, and the Firmata application served as the API for communication between the Arduino Grove board and its internal and external components. This comprehensive system effectively monitored and maintained the moisture level in the soil, ensuring optimal plant health.





