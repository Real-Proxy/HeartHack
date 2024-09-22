# HeartHack: DIY ECG Machine

The **HeartHack DIY ECG Machine** is a simple and affordable solution for monitoring ECG signals. It utilizes an AD8232 ECG module connected to a sound card to visualize real-time electrical activity of the heart.

## Features

- View ECG signals through a sound card (line-in or microphone jack).
- Real-time heart monitoring
- Use the AD8232 ECG module and a single operational amplifier (Op-Amp) for accurate heart signal readings.
  
![Screenshot](HeartHack/src/images/screenshot.png)

*Figure 1: ECG Machine interface displaying heart rate.*

## Understanding ECG
In general terms, lets look at what an ECG is representing and how we're able to sense it. The ECG is separated into two basic Intervals, the PR Interval and the QT Interval, described below.

![Waves and Internals](HeartHack/src/images/EKG_Complex_en.svg.png)

*Figure 2: Waves and Internals of a heart beat.*


![Heart Diagram](HeartHack/src/images/Heart_diagram-en.svg.png)

*Figure 3: Heart diagram.*

### PR Interval
The PR interval represents the time for an electrical impulse to travel from the right atrium to the left. It corresponds to the initial depolarization and contraction of the atria.

### QT Interval
The QT interval covers the contraction of the ventricles, the hallmark of which is the "beep" in cardiac monitors. It includes the QRS complex, ST segment, and T wave, representing both ventricular contraction and relaxation.

## Hardware Requirements

### AD8232 ECG Module
- Preferred ECG device for this project is the AD8232 breakout board.
  
![AD8232 Module](HeartHack/src/images/AD-8232-Heart-Monitor.jpg)

*Figure 4: AD8232 Module .*

### Battery Managment System
- Preferred BMS device for this project.

![BMS Module](HeartHack/src/images/BMS.jpg)

*Figure 5: BMS Module .*

### Disposable Electrodes
- Preferred Electordes device for this project.

![electrodes](HeartHack/src/images/ecg-electrode.png)

*Figure 6: Electrodes .*

### Disposable Electrodes Leads
- Preferred leads device for this project.

![electrodes lead](HeartHack/src/images/wires.jpg)

*Figure 7: Electrodes Leads .*

## Connecting the Hardware

### Circuit Diagram


![Circuit Diagram](HeartHack/src/images/CIrcuit.jpg)

*Figure 8: Final Circuit .*

### Sensor Pad Placement
Place the sensor pads as close to the heart as possible for optimal measurements. Two common configurations are:

- Forearms and legs
- Chest, arms, and lower abdomen

| Cable Color | Signal      |
|-------------|-------------|
| Black       | RA (Right Arm) |
| Blue        | LA (Left Arm)  |
| Red         | RL (Right Leg) |

![Sensor Placement](HeartHack/src/images/body.png)

*Figure 9: Sensor Placement.*
