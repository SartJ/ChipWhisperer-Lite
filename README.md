# Set Up

Guide: https://chipwhisperer.readthedocs.io/en/latest/windows-install.html
https://theses.liacs.nl/pdf/2020-2021-BurghoornG.pdf

1. Open a command prompt or powershell windows and `run wsl --install -d ubuntu`
2. Restart your computer

## Installing the Compilers

1. Run WSL
2. Run `sudo apt update`.
3. Run `sudo apt install -y build-essential gcc-arm-none-eabi gcc-avr avr-libc`

## Running the Installer

1. Link to the Installer: https://github.com/newaetech/chipwhisperer/releases
2. Download and install the latest release in the home page. It usually has read/write permission.
3. After installation run the ChipWhisperer application from the Desktop shortcut or your Start menu.

After a terminal pop-up the following Jupyter Lab will open on the browser:
![image](https://github.com/user-attachments/assets/be2b01cd-8102-4341-98b3-140dac427984)

Go to the Jupyter folder.

![image](https://github.com/user-attachments/assets/93416378-99cb-42bc-b3d8-5bb4d394d5c3)

Run through the "0 - Introduction to Jypyter Notebooks" to verify that everything is running smooth.



