# Assignment 3B

All the python files for the assignment can be found in the "Scripts" folder of the electronics package uploaded to classroom

The "msg" contains the .msg file for the custom message

## Q1
Q1 has two python codes. **Q1_publisher.py** is the publisher that publishes to the topic /new, whereas **Q1_subscriber.py** is the subscriber that subscribes to the topic /new and prints to the terminal.

## Q2
Q2 has two python codes. **Q2_s1.py** publishes its color status to topic /s1. **Q2_s2.py** subscribes to this topic and publishes its color status to the topic /s2 based on the data on /s1.

## Q3
Q3 has one python code, **Q3_custom_msg.py**. This code was written just to check if my custom message was actually working.

## Q4
Q4 has four python codes. **seconds.py** counts from 0 to 60 and publishes this count to the topic /seconds. **minutes.py** subscribes to that topic, increments whenever seconds cross 60, and publishes this value to /minutes. **hours.py** does the same thing, except it subscribes to both /seconds and /minutes. **clock.py** subscribes to all three of the above topics and publishes the "clock" to /clock.