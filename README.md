# Chipathon 2025, Silicon University, Odisha
 
Mentor Portal for all of the participants from Silicon University

# Resources

- [Main SSCS Chipathon 2025 GitHub Page](https://github.com/sscs-ose/sscs-chipathon-2025)
  - [schedule/](https://github.com/sscs-ose/sscs-chipathon-2025/blob/main/schedule): event schedule, important dates, **Report Submit links**, Meeting Videos
  - [resources/Digital_Building_Blocks](https://github.com/sscs-ose/sscs-chipathon-2025/blob/main/resources/Digital_Building_Blocks)
    - [Standard Cell Overview](https://github.com/sscs-ose/sscs-chipathon-2025/blob/main/resources/Digital_Building_Blocks/files/Chipathon_digital_track_overview.pdf)
    - [GF180 Analog Design Workflow GitHub Repo Template](https://github.com/Jianxun/iic-osic-tools-project-template): Use this template to create your _project repository_ in your GitHub account. Follow the the naming convention: **_chipathon25-SILICON_BBI[1/2]-<username>_** [1/2] -> depending on your group, use 1 or 2. **NOTE** This template can be used to create the whole docker image as well.

- **STANDARD CELL LINKS**
  - [Global Foundry 7-track Standard Cells](https://github.com/fossi-foundation//globalfoundries-pdk-libs-gf180mcu_fd_sc_mcu7t5v0)
  - [OSU 3.3V GF Standard Cell Lib](https://github.com/stineje/globalfoundries-pdk-libs-gf180mcu_osu_sc): This is the library we are going to augment.
- **TUTORIALS/EXAMPLES/ETC**
  -  Tutorial using **Xschem** and **ngspice** with gf180mcu ([part-1](https://youtu.be/MdywD87-DVg) | [part-2](https://youtu.be/DLvZSsLAbho) | [part-3](https://youtu.be/nBnR8Nm_B_I) )
  -  [End-to-End tutorial using Sky130](docs/Open-Source%20Analog%20Design%20Flow%20Using%20Efabless%20and%20the%20SkyWater%20130nm%20PDK.pdf)
  - **Magic** Resources
    - [Magic](http://www.opencircuitdesign.com/magic/): The official site of Magic maintained by Tim Edwards. COntains a bunch of tutorials.
    - [Drawing an inverter](https://docs.google.com/document/d/1hSLKsz9xcEJgAMmYYer5cDwvPqas9_JGRUAgEORx1Yw/edit#heading=h.j6gtadx04fb6): A google doc by Ryan Ridley, Teo Ene, and James E. Stine. Very step-by-step guide for SKY-130nm process.
    - [Magic Video Tutorial](https://youtu.be/XvBpqKwzrFY?si=AyL0Wr3V4gb954yx) by Tim Edwards. (~1hr 30min) 
    - [Magic cheaetsheet](https://github.com/iic-jku/osic-multitool/blob/main/magic-cheatsheet/magic_cheatsheet.pdf) by Harald Pretl.

- **TOOL INSTALLATION**
  - **Quick-Start Guide for Windows** ([Video](https://zoom.us/rec/share/ahAF2sZ06EhY9c5Euyu2XA0EWwzEurNndqUKoftl7LWP5kEYUlztXJquwv_rsXs5.ZmtQttKvS1RvCqQ5?startTime=1750921181000))
    - Assuming **WSL is installed**.
    - Download and install **Docker Desktop**. Create a free user and login to the _Dashboard_
      - During install the select: ✅ Use WSL 2 instead of Hyper-V (recommneded)
    - Copy the `start_chipathon_vnc.bat` from the [Chipathon /resource](https://github.com/sscs-ose/sscs-chipathon-2025/blob/main/resources/IIC-OSIC-TOOLS/start_chipathon_vnc.bat) page to a accessible location eg. `C:\Users\<username>\Downloads`
    - Start the a Powershell in admin mode: `Windows-> Right-Click -> Windows Powershell (admin)`
    - Change directory to the _Downloads_ folder and execute the _batch file_ `.\start_chipathon_vnc.bat`
      - **IMPORTANT NOTE**: This downloads a >2GB docker image so make sure you have a good internet connection and you are plugged in.
    - After installation you can start the docker container from the _Dashboard_ or from the _Powershell_
    - This will start a VNC Server and you can login using a VNC client like Tiger VNC (If you haven't download and install from the Web)
      - In the connect window enter `localhost:5901`
      - When asked for passwprd enter `abc123`
    - Now you can access the Linux desktop with all the EDA tools available. 
