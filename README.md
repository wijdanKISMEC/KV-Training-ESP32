# ESP32 TTGO GPIO Configuration

To configure the ESP32 TTGO GPIO, refer to the diagram below:

![ESP32 TTGO GPIO](https://github.com/user-attachments/assets/b54539fd-d14e-4b6a-b354-69bb6d22b656)

---

## TFT Display Configuration in the Library

### 1. Select the Correct TFT Display

Navigate to the `User_Setup_Select` file in your TFT library. This file is where you configure the type of TFT display you’re using. You can edit this file with any text editor.

![Library Directory](https://github.com/wijdanKISMEC/KV-Training-ESP32/blob/main/TFT%20Library%20Directory.png?raw=true)

### 2. Modify the Display Setup

In the `User_Setup_Select` file, you'll find several TFT display configurations. To use the TTGO Display, you need to comment out the default TFT display and uncomment the TTGO Display setup.

![Comment](https://github.com/wijdanKISMEC/KV-Training-ESP32/blob/main/TFT%20Edit.png?raw=true)

---

By following these steps, you can ensure that the correct TFT display is configured for your ESP32 TTGO project.
