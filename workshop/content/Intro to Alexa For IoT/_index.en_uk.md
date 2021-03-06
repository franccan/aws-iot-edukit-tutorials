+++
title = "Intro to Alexa for IoT"
chapter = true
weight = 50
pre = "<b>5. </b>"
+++

In this tutorial, you will implement Alexa Voice Service Integration for AWS IoT (AFI) on the M5Stack Core2 for AWS IoT EduKit reference hardware kit. You will learn how to use the Espressif Voice Assistant SDK (VA-SDK) and Alexa to control the onboard LED using Alexa Smart Home commands. This tutorial currently uses an AWS account provided by Espressif. This is a *beta* port of the Espressif VA-SDK for the M5Stack Core2 for AWS IoT EduKit reference hardware.

Assumptions. Before starting this tutorial, verify the following prerequisites:

1. You have an [M5Stack Core2 ESP32 IoT Development Kit for AWS IoT EduKit](https://www.amazon.com/dp/B08NP5LVFH).
2. You have the necessary toolchain and dependent software installed to build and flash firmware to your M5Stack Core2 for AWS IoT EduKit reference hardware and know which serial port your Core2 for AWS IoT EduKit device is connected to. It is highly recommended you complete the full [**Blinky Hello World**](/en_uk/blinky-hello-world.html) tutorial first.
3. You have at least a basic technical understanding of AWS IoT messaging concepts such as topics, publishing, and subscribing.
4. You have an IDE installed like Visual Studio Code, as covered in the [**Getting Started**](/en_uk/getting-started.html) tutorial.

---
{{% button href="https://github.com/m5stack/Core2-for-AWS-IoT-EduKit/issues" icon="fas fa-bug" %}}Report bugs{{% /button %}} {{% button href="https://community.m5stack.com/category/41/core2-for-aws" icon="far fa-question-circle" %}}Community support{{% /button %}}