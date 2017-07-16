# StopLight
Child's stoplight with WS2812 LEDs and push on/off buttons
This program requires https://github.com/jgarff/rpi_ws281x

This is built to run on hardware that includes 3 logical lights, top, middle, and bottom
Each light is composed of 7 chained WS2812 LEDs on a round board, for a total of 21 LEDs
The default mode is stoplight mode, where it cycles between green, yellow, and red lights
There is an alarm mode that is designed to act as a night light and encourage a young child to stay in bed until it is time to wake up
There is a red light, green light game, with yellow and purple for walk and jump respectively
