+++
title = 'Test'
date = 2024-07-14T10:56:41-07:00
draft = false
+++

### Introduction.

In the rapidly evolving world of robotics and embedded systems, microROS is a game-changer. It brings the capabilities of ROS (Robot Operating System) 2 to microcontrollers, facilitating the development of robust and interactive systems. The Raspberry Pi Pico, with its powerful RP2040 chip, provides an excellent platform for such applications.

This tutorial will guide you through setting up and running microROS on the Raspberry Pi Pico. The ability to publish and subscribe to topics directly from the microcontroller, a standout feature of microROS, allows for real-time communication and data exchange, fostering complex, coordinated behaviors.

Additionally, microROS's reduced memory footprint makes it ideal for devices with limited resources. Whether you're a hobbyist or an experienced engineer, by the end of this tutorial, you'll be equipped to leverage the power of microROS on your Raspberry Pi Pico. Let's get started!

In this tutorial I'm assumming you're working with the regular Pico without Wi-Fi support and you have ROS2 installed on your computer.

Also, this tutorial is based on the following articles: 

### Setting up the Environment

Let's isntall the dependencies
<script src="https://gist.github.com/ThisUserTaken/7d69eb264f5b1d2eaecf9a4686706bf3.js"></script>