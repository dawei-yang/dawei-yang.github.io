---
layout: project
type: project
image: images/arduino.png
title: Arduino Pill Dispenser
permalink: projects/pill_dispenser
# All dates must be YYYY-MM-DD format!
date: 2016-11-30
labels:
  - Pill dispenser
  - Arduino
  - C
summary: Developed a pill dispenser by using Arudino Uno.
---

<div class=" rounded images">
  <img class="rounded image" src="../images/arduino.jpg">

</div>
<div style="text-indent:2em">
The reason we decided to make this pill dispenser is that some people always forget to take medication on time, and they really need a device to help them. User can set the time he or she needs to take medication and how many pills he or she should have by using Android phone through Bluetooth. Once the real time is exact the time was set, the pill dispenser will start working. After it load the exact number of pills, it will stop and alarm. Meanwhile the app also notices the user to take the pills.
</div>
<div style="text-indent:2em">
This device has two parts: Arduino and App, and I contributed to the Arduino part. I used cardboard to make the device. Arduino connects to a DC stepper motor, a pair of IR break sensor, a real-time clock, a bluetooth module, and a piezoelectric. With the real-time clock, this device has the real time signal even lose power. The stepper rotates with a wheel, and a hole on the wheel takes one pill from the container when it perpendicular upward. Then, the pill drops when the hole is downward. The IR break sensor is right under the hole, so the sensor will receive a signal whenever a pill drops. Arduino counts how many pills drops by this signal. 
</div>
<div style="text-indent:2em">
  
  I learned how to connect sensors and motors with Arduino Uno. One of the advantage of this device is that we used the signal of the IR break sensor as a hardware interrupt. Therefore, although sometimes the hole cannot carry one pill from the container. Since Arduino doesn’t receive any signal, the stepper will keeping running until the expected number of pills are detected.
</div>
