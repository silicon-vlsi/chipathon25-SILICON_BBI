# Chipathon 2025, Silicon University, Odisha
 
Mentor Portal for all of the participants from Silicon University

- [Zoom Link for Chipathon Meeting every **Friday at 8:30PM IST**](https://us06web.zoom.us/j/83060635740?pwd=UbIWLnu8C7nyLTZE7JglzRgbwSa23r.1)
- [Zoom Link for SILICON_BBI team meeting every **Saturday at 3:30PM**](https://zoom.us/j/92589037939?pwd=bmQ0pNzFlGLlLLzM2sb3oM5rxdptgh.1)
  
# Resources

- [Main SSCS Chipathon 2025 GitHub Page](https://github.com/sscs-ose/sscs-chipathon-2025)
  - [schedule/](https://github.com/sscs-ose/sscs-chipathon-2025/blob/main/schedule): event schedule, important dates, **Report Submit links**, Meeting Videos
    - [Slide Deck with Proposals](https://docs.google.com/presentation/d/1PPs22g3QAaJXZ76OtD4wRJLnIo7fuem2/edit?slide=id.g36d74ebfab8_0_407&pli=1#slide=id.g36d74ebfab8_0_407)
  - **Links to Selected Weekly Meeting Slides**
    - [June 27 Meeting SLides](https://docs.google.com/presentation/d/e/2PACX-1vQwOCDO72NBn09BWiQVFil2mFRwZ__72UmFIUbe2BdGgr498ldONym0g9bURT5FMA/pub?slide=id.g36b4f57c94d_2_37): **StdCell Ideas** in Tim's Slides. Introduction to **CharLib** by James Stine.
    - [June 20 Meeting Slides](https://docs.google.com/presentation/d/e/2PACX-1vQdbPDtoySuBoXIKmtaYK0QQP0KcUmgab9Mp3-7UxugTcsv5Y2R-2Ct8uTjzvbFuw/pub?slide=id.g36a22847a52_3_0): **Slide 53** has project goals.
  - [resources/Digital_Building_Blocks](https://github.com/sscs-ose/sscs-chipathon-2025/blob/main/resources/Digital_Building_Blocks)
    - [Standard Cell Overview](https://github.com/sscs-ose/sscs-chipathon-2025/blob/main/resources/Digital_Building_Blocks/files/Chipathon_digital_track_overview.pdf): Tim Edward, et.al.
    - [GF180 Analog Design Workflow GitHub Repo Template](https://github.com/Jianxun/iic-osic-tools-project-template): Use this template to create your _project repository_ in your GitHub account. Follow the the naming convention: **_chipathon25-SILICON_BBI[1/2]-<username>_** [1/2] -> depending on your group, use 1 or 2. **NOTE** This template can be used to create the whole docker image as well.

- **STANDARD CELL LINKS**
  - [Global Foundry 5V 7-track Standard Cells](https://github.com/fossi-foundation//globalfoundries-pdk-libs-gf180mcu_fd_sc_mcu7t5v0)
  - [OSU 3.3V GF Standard Cell Lib](https://github.com/stineje/globalfoundries-pdk-libs-gf180mcu_osu_sc): This is the library we are going to augment.
  - [PDF Slides: Introduction Standard Cells](/docs/Standard%20Cell%20Design.pdf)
- **TUTORIALS/EXAMPLES/ETC**
  -  Tutorial using **Xschem** and **ngspice** with gf180mcu ([part-1](https://youtu.be/MdywD87-DVg) | [part-2](https://youtu.be/DLvZSsLAbho) | [part-3](https://youtu.be/nBnR8Nm_B_I) )
  -  [End-to-End tutorial using Sky130](docs/Open-Source%20Analog%20Design%20Flow%20Using%20Efabless%20and%20the%20SkyWater%20130nm%20PDK.pdf)
  - **Magic** Resources
    - [Magic](http://www.opencircuitdesign.com/magic/): The official site of Magic maintained by Tim Edwards. COntains a bunch of tutorials.
    - [Drawing an inverter](https://docs.google.com/document/d/1hSLKsz9xcEJgAMmYYer5cDwvPqas9_JGRUAgEORx1Yw/edit#heading=h.j6gtadx04fb6): A google doc by Ryan Ridley, Teo Ene, and James E. Stine. Very step-by-step guide for SKY-130nm process.
    - [Magic Video Tutorial](https://youtu.be/XvBpqKwzrFY?si=AyL0Wr3V4gb954yx) by Tim Edwards. (~1hr 30min) 
    - [Magic cheaetsheet](https://github.com/iic-jku/osic-multitool/blob/main/magic-cheatsheet/magic_cheatsheet.pdf) by Harald Pretl.
      
- **VIDEOS**
  - July 12 ([Video (1 hr)](https://zoom.us/rec/share/dV2a7f0OiC-pDPC1i0mP9-_u6QtGHIcBtFH_UYWn8SxJCGKBjiNZdG2z_ecZMhBd.ovn2cfo-f_DAk2kr)) Weekly Meeting
    - Review of the project proposal with assigned standard cells for each members.
    - 0:40 hr : **Assignment** Copy the 2-input NAND gate with 1X drive strength from the OSU 9-Track library and increase drive strength to 2X.
  - July 1 ([Video (30-min)](https://zoom.us/rec/share/gD_Pr28JdMq8DdJxe6bWLcMAMnFSaTuuNu0P7W9OATsU_7tqP0cgvbKwSJzCncpf.2hM4n4cL8CEQeh9i?startTime=1751357089000)) : This video demonstrates on how to access the **OSU standard cell library** and simulate it.
    - 0:00 hr : Reviewing the **GF180 Process**
    - 0:06 hr : Cloning the **OSU Standard Cell Library**
    - 0:10 hr : **Reading** the standard cells in Xschem
    - 0:14 hr : **Netlist and Simulate** the standard cell
  - June 28 ([Video (1:20 hrs)](https://zoom.us/rec/share/xjX9IamReQsPZ1U40AkjokxDDd7zHhl_LZWi4nH8png014gCtHxPwRhp4EJAwLoS.CjTjLz1BgSH1s8gk)) Weekly Meeting
    - 0:00 hr : Introduction to VLSI Design flow.
    - 0:25 hr : Introduction Standard Cells [[PDF of Slides](/docs/Standard%20Cell%20Design.pdf)]
    - 0:50 hr : Questions/Answers and Docker installation.
    - 1:00 hr : Connecting through **Tiger VNC** viewer and checking the **EDA tools (xschem, ngspice)**
    - 1:08 hr : Cloning the **GitHub template**
  - June 26 ([Video (9-min)](https://zoom.us/rec/share/DI3iGQpEiO0sQCuq--XjCDxQMElF9J_zpmhLO5JPsenvdU8ih3zvHZqblLavywYi.eWBLfY78VkDgHfb8)): This is a quick video demonstrating the **docker download of the IIC OSIC tools** and shows how to invoke the 3 EDA tools, **xschem, ngspice** and **Magic**
    
- **TOOL INSTALLATION**
  - **QUICK-START GUIDE for INSTALLING IIC OSIC Tools in Windows** 
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
