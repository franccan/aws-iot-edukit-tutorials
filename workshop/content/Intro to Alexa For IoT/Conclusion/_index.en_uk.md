
+++
title = "Conclusion"
weight = 50
pre = "<b>e. </b>"
+++

## Conclusion
You have completed the AWS IoT EduKit hands-on tutorial for running Alexa for AWS IoT (AFI) using the custom ported Espressif Voice Assistant SDK and Alexa to control on-board peripherals using Alexa Smart Home commands. For additional information about Smart Home for AVS, see the [documentation](https://developer.amazon.com/en-US/docs/alexa/alexa-voice-service/smart-home-for-avs.html) or the following [blog post](https://developer.amazon.com/en-US/blogs/alexa/device-makers/2020/04/create-a-sample-alexa-built-in-disco-ball-with-smart-home-for-av).

If you would like to learn more about other interfaces available or to come up with your own implementations of using other features of the M5Stack Core2 for AWS IoT EduKit reference hardware, take a look at [ModeController](https://developer.amazon.com/en-US/docs/alexa/alexa-voice-service/alexa-modecontroller.html) and [ToggleController](https://developer.amazon.com/en-US/docs/alexa/alexa-voice-service/alexa-togglecontroller.html). Use your creativity and what you've learned in the other chapters of this tutorial to explore new capabilities for voice! 

This is the last tutorial currently available. We will be publishing more.

## Clean up
In this solution you did not use any of your own resources in AWS. However, you can wipe your device software (and remove the certificates from flash) by entering the command (replace **<<DEVICE_PORT>>** with the serial port your device is connected to):
```bash
idf.py erase_flash -p <<DEVICE_PORT>>
```

---
{{% button href="https://github.com/m5stack/Core2-for-AWS-IoT-EduKit/issues" icon="fas fa-bug" %}}Report bugs{{% /button %}} {{% button href="https://community.m5stack.com/category/41/core2-for-aws" icon="far fa-question-circle" %}}Community support{{% /button %}}