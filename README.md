# Welcome to the Pi-Fly Wiki

Welcome to the official Pi-Fly github page! 🚀

Pi-Fly is a next-generation automation platform designed to streamline and simplify the configuration of Raspberry Pi-based systems for Ardupilot, Pi Camera, and more. This platform takes advantage of modern Linux capabilities and offers an easy-to-use Python script to automatically configure your system for optimal performance.

Whether you're a developer, hobbyist, or a drone enthusiast, Pi-Fly is designed to help you easily set up and run your systems with minimal effort. Our goal is to provide you with the tools you need to succeed in your projects, whether it's automating flight controllers, working with IMUs, or streaming live video from your Pi Camera.

### Why Pi-Fly?  
- **64-bit Architecture** 🏎️ - Faster and more efficient than previous versions.  
- **Automated Setup** ⚙️ - No manual kernel tweaking; everything is configured via script.  
- **Multi-Sensor Support** 📡 - Works with multiple IMUs, GPS modules, and ADCs.  
- **AI & Computer Vision Ready** 🤖 - With the powerful Raspberry Pi 4, the **Pi Camera Module 3** can be leveraged for AI-based applications such as object detection, autonomous navigation, and real-time video analysis.  
- **Affordable & Open-Source** 💡 - A high-performance alternative to expensive, proprietary flight controllers.  


Feel free to explore the various setup guides, troubleshooting tips, and features that Pi-Fly offers. If you have any questions or suggestions, don't hesitate to reach out—we're here to help you make the most of your experience with Pi-Fly!

Check out the [Pi-Fly Wiki](https://github.com/akhodeir/Pi-Fly/wiki) for all the details.

**Note** : The board/project is not limited to Ardupilot. It can be used with any other flight controller such as PX4, INAV, Betaflight, your own flight controler,...etc
**Note**: : The initial name of the project was OBAL_V2, the name was changed to Pi-Fly due to some political issues with the owner of initial OBAL !!

Happy building! 🚁✨

![3D PCB](photo/3D.png)

![Drone](photo/IMG_9943.jpeg)

![Armed](photo/IMG_9940.jpeg)


# OBAL vs Pi-Fly vs Navio2 - Comparison

## 🚀 Overview
This table outlines the **significant improvements** made from the initial **OBAL** to **Pi-Fly** and compares it with the **Navio2** flight controller system.

---

## ⚙️ **Feature Comparison**

| Feature                | OBAL          | Pi-Fly        | Navio2             |
|------------------------|---------------|----------------|--------------------|
| **Linux Kernel**        | Bulleyes      | Bookworm       | Raspbian + ROS     |
| **Ardupilot**           | 32-bit        | 64-bit         | ?                  |
| **Linux Configuration** | Manual        | Automatic via script | Manual        |
| **Rx Protocol**         | PPM/PWM           | IBUS and SBUS  | PPM and SBUS       |
| **Flight Controller**   | Prototype     | Complete system| Complete system    |
| **IMU**                 | GY-91         | GY-91, GY-912, ... + more | MPU9250, LSM9DS1 |
| **Display**             | No            | Yes            | No                 |
| **Power Module**        | No            | Yes            | Yes                |
| **License**             | Open source   | Open source    | Proprietary        |
| **Price**               | < $60         | < $60          | $199               |
| **Link**                | [here](https://github.com/HefnySco/OBAL)     | [here](#)      | [here](https://navio2.hipi.io/)        |

---

## ⚠️ **Cons with Initial OBAL:**
- Uses **analog Rx protocol (PPM) or (PWM)**, limiting flexibility.
- Limited to **GY-91 IMU** (only possible IMU).
- **Safety switch** is not well designed.
- No proper **logic conversion** (mix of **5V and 3.3V** logical levels with Raspberry Pi).
- Uses an **old Linux version**, requiring recompilation to disable **`CONFIG_STRICT_DEVMEM`**.
- **32-bit Ardupilot** applications limit performance.

---
## [Donation] Your support is invaluable to this project!

Countless hours of hard work, prototyping, and investment in tools and materials have gone into making this project a reality. If you appreciate the effort and would like to contribute, your donation will help us continue developing and improving Pi-Fly.

Please consider donating for the project. There were tremendous effort added in this project. 
Many prototype boards were built and a lot of tools were purchased to make this project become true.

click image below to start donating :

[
![Donate with PayPal](photo/paypal-donate-button.png)
](https://www.paypal.com/donate/?hosted_button_id=LGAC3VKW2A8ZA)

**Important**

Use this project at your own risk. 
