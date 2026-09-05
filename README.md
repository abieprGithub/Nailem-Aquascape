# Nailem: Smart Aquascape
<img width="239" height="65" alt="nailemlogolr" src="https://github.com/user-attachments/assets/eb9ea210-08bb-424a-a707-34730d97d1f6" />

As the name suggests, N**ai**lem is an AIoT-powered highly automated aquascape maintenance system, originally designed for Nilem fish (Osteochilus Vittatus):

<img width="150" height="87" alt="nilemlr" src="https://github.com/user-attachments/assets/0da04d37-755a-4ef0-b2fe-9e7c8d0b883f" />

<br>

🐟 Why Nilem in particular?

1. They're awesome
2. They're tuff (as in they can live in harsh conditions)
3. They're edible (yum)
4. They're common in my nation (Indonesia!)
5. They're reasonably sized (for food fish, at least)

### ❗ But more importantly,
This is **not** limited only to Nilem fish, and it will be designed to be scalable and flexible to meet the living conditions of most other fish, across a wide range of scale.
Of course, community contributions help in adapting this to a wider range of fish, though I haven't given myself time to learn how to manage contributions yet.

I've came up with this to solve a very real problem:
1) Raising food fish is a challenging and long process
2) I'm lazy as hell
3) Urban farming shouldn't be limited to crops, but livestock too

## Quick navigation

[🛠️ Technical Functions](detailed-functions) | [⚠️ Disclaimers](disclaimer) | [📜 Bulletin](bulletin)

(doesn't work yet, my bad)

<br>

## ⚙️ Functions

<img width="558" height="475" alt="diagramlr" src="https://github.com/user-attachments/assets/3cd6ae83-535b-4af1-ad20-fd058182d029" />

*Note: The following 3D model is old, and I will make a new one from the ground up soon.*

## 🛠️ Technical
It packs a whole load of functions. At its core, it's split between two subsystems: Real time control & AI compute.
At its core is an ESP32-S3 as a real time controller, which is kind of a perfect fit for this since I ended up utilizing almost its full potential.
To clarify a bit, what I mean by 'AI' before is actually just computer vision.
For that, this can be fitted with pretty much any low power computer that has USB or UART support, preferably SBCs designed for edge AI.
The NVIDIA Jetson Orin or the Rasperry Pi 5 + AI HAT should work well.
The thing is, the real time subsystem can exist as a standalone system, omitting the computer vision features entirely if the budget didn't allow.
However, it's 2026 and IoT alone is getting a little bit outdated.

<br>

<img width="1214" height="548" alt="wiringdiagram_newlr" src="https://github.com/user-attachments/assets/b341cdf9-afa8-4b71-8522-600d0a0ea45a" />

<br>

### Detailed functions

*Programming or build hasn't started yet, but this gives you an idea of what I wanted to create.* 

**Primary Automation Features:**
1) 💦 Surface cleaning
2) 🌡️ Temperature Regulation
3) 🥄 Feeding
4) 💡Lighting
5) 🔄 Water Change

**Monitored parameters:**
1) Water Temperature
2) Water pH
3) Water TDS
4) Water Turbidity
5) Ambient temperature
6) Ambient humidity
7) Ambient lighting
8) Power consumption

**IoT features:**
1) Web Dashboard
2) API
3) OTA Firmware Update
4) 

**AI Features:**
1) Fish behavior detection
2) Anomaly detection
3) Egg detection (hopefully 😭)

**Miscellaneous features for the sake of the developer and or the user**
1) Two status ARGB LEDs on the board
2) Header for an external ARGB
3) UART debug header
4) USB-C data-only receptacle
5) Highly modular design, both physically and electrically. 

## Disclaimer
This used to be my 8th grade engineering project. However, after the project officially closes, I was NOT satisfied with how this turned out (it was still under 50% done), so I took over this entire project after ensuring that my team is okay with it. 
With that, kudos to my goated team for their work, even though I was responsible for 80% of the technical work:

<br>

Abie (myself) - Programmer, leader; Akbar - Mechanic; Adzka - Mechanic; <br>
Nabil - Management; Shifa - Scientist; Kirana - Media;

<br>
This did technically start before the Hack Club Stardance YSWS, but the amount of revisions made AFTER it started make this practically a new project tbh.
However, I'm still going to state that this project started before the season anyways.

## Bulletin

*This section is intended to show the latest updates, devlogs, or things you should know, and is updated reguarly!*

I'm finally done creating the rough connection diagram of most of the project.
It's enough to tell you what goes where, but not as detailed as a wiring diagram
Making it at this stage is kinda pointless since the schematic is already done.
<br><br>
Next update should show a completed PCB !!!

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
