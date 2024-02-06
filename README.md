# 1122_5G-network
5G Network consists of **5G NR (new radio)** and **5G Core**. 
This course introduces the Matlab 5G Toolbox (for 5G NR) and GNS3 (for network) to students to become familiar with 5G technologies by using these tools, references, and examples in these references.
- **GNS3** - Graphical Network Simulator-3 is a network software emulator first released in 2008. It allows the combination of virtual and real devices to simulate complex networks.
- **Matlab 5G toolbox** - 5G Toolbox provides standard-compliant functions and reference examples for the modeling, simulating, and verifying 5G New Radio (NR) communications systems. 

## 🔰GNS3 Network simulator (To Know and To Do)
Graphical Network Simulator-3 is a network software emulator first released in 2008. It allows the combination of virtual and real devices used to simulate complex networks. It uses Dynamips emulation software to simulate Cisco IOS.
- refer to the instructions in the handout (/GNS3_instruct)
- the VM ova file will be provided in class. Please ask TA for installation support. (This is an optional. You can either use this .ova file or follow the instructions to install VM by yourself)    
### ▶️ GNS3 Installation (Week01)
- GNS3 official site - https://gns3.com/
- GNS3 installation video - David Bombal https://www.youtube.com/watch?v=Ibe3hgP8gCA 
- GNS3 links
  - GNS3 website: https://gns3.com/
  - GNS3 GitHub page: https://github.com/GNS3/gns3-gui/rele...
  - Free Solar-PuTTY: http://bit.ly/SolarPutty
  - Free Engineers Toolset: http://bit.ly/gns3toolset
- Free Software links: 
  - SolarWinds TFTP Server: https://www.solarwinds.com/free-tools...
  - Solar Putty: https://www.solarwinds.com/free-tools...
  - SolarWinds NPM: https://www.solarwinds.com/network-pe...
### ▶️ VirtualBox 
 - Virtualbox download: https://www.virtualbox.org/
### ▶️ Mininet installation
An Instant Virtual Network on your Laptop (or other PC)
- Mininet official site: https://mininet.org/
### ▶️ Architecture and Configuration  
- <img width="568" alt="image" src="https://github.com/iiotntust/1122_5G-network/assets/56021651/5ff05b63-4d8e-4f60-b502-a69cd2c95ca1">
- <img width="625" alt="image" src="https://github.com/iiotntust/1122_5G-network/assets/56021651/b0027a96-d083-4e39-a65d-519bc94d3a41">
## 🔰Matlab 5G Tool (To know)
In this exercise, we will generate a 5G NR test model (NR-TM) waveform using the 5G Waveform Generator app and download the generated waveform to a Keysight® E4438C vector signal generator for over-the-air transmission using Instrument Control Toolbox.(https://www.mathworks.com/campaigns/offers/next/5g-nr-waveform-generation-and-over-the-air-testing-with-matlab.html)
- Software: Matlab 5G Tool - https://www.mathworks.com/products/5g.html?s_tid=srchtitle_site_search_1_5G
- Do example **#1**and **#2**
### ▶️Exercises in class
- 1: Installation Matlab and 5G Toolbox;  
  - Download link (only available on NTUST campus): https://www.cc.ntust.edu.tw/p/412-1050-8352.php 
- 2: Waveform Generation, Generate standard-compliant 5G NR waveforms.
   - https://www.mathworks.com/videos/easy-wireless-waveform-generation-with-matlab-1682667504303.html
### ▶️Optional 
- 3 (Option): Link-Level Simulation, Simulate 5G NR end-to-end wireless communication links.
  - https://www.mathworks.com/help/5g/gs/model-5g-nr-communication-links.html
- 4 (Option): Test and Measurement, Evaluate the performance of 5G RF transmitters.
  - https://www.mathworks.com/campaigns/offers/next/5g-nr-waveform-generation-and-over-the-air-testing-with-matlab.html
- 5 (Option): MIMO and Beamforming, Use channel state information (CSI) feedback to adjust transmission parameters, including code rate, modulation, number of layers, and MIMO precoding matrix.
  - https://www.mathworks.com/videos/beamforming-for-mu-mimo-in-5g-new-radio-1677265377162.html
- 6 (Option): Propagation and Channel Models
  - https://www.mathworks.com/help/5g/ug/cdl-channel-model-customization-with-ray-tracing.html
- 7 (Option): Cell Search Procedures
  - https://www.mathworks.com/videos/5g-explained-synchronization-signal-blocks-in-5g-nr-1577445332091.html 
- 8 (Option): System-Level Simulation
  - https://www.mathworks.com/help/5g/system-level-simulation.html
- 9 (Option): AI for Wireless 
  - https://www.mathworks.com/videos/ai-for-wireless-communication-1663074769420.html
