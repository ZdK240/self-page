# Siril
<img width="375" height="177" alt="Screenshot 2026-07-28 133403" src="https://github.com/user-attachments/assets/c4b8074b-7cca-4bd0-9eca-d0443c6df1b7" />

-> Siril is an image tool which can stack images, analyze images, and do much more ([more details on their website](https://siril.org/)).

It can take multiple modules to do many kinds of tasks, with the most important in our application being Starnet, 
which allows us to stack images automatically using a Python script

This documentation is meant to help set up Siril, to show the installation of Starnet, and how the images must be set up in order to 
stack them.

## Installation
First of all, we go to the [website](https://siril.org/), where we are greeted by the following screen:
<img width="1366" height="766" alt="Siril - Downloads - Google Chrome 7_28_2026 1_29_34 PM" src="https://github.com/user-attachments/assets/ca5016df-7b83-4feb-a61f-80f394dcb616" />

Here, we can select the OS we are running and select the installer depending on OS and the chip (in case of Mac). However, since I am using a Windows,
I will be selecting the Windows option. To make installation and running easier for Windows users, I recommend using the Portable installer, which installs a zip file
with an .exe file in the bin folder.
<img width="870" height="496" alt="bin - File Explorer 7_28_2026 1_59_05 PM" src="https://github.com/user-attachments/assets/e3b6d268-e8fe-44b1-b7cf-3e6319c129cd" />

Run the siril.exe file, let the Windows CMD do some background processes, and you will see this screen.
<img width="1150" height="749" alt="Siril-1 4 4 7_28_2026 2_02_44 PM" src="https://github.com/user-attachments/assets/c1466846-5cb6-41b5-b888-e40762b3ad1a" />

## The Setup
-> Now you must press the blue button for a drop-down menu like this, and press 'Get Scripts' to get a menu as shown below:
<img width="800" height="703" alt="Siril-1 4 4 7_28_2026 2_20_19 PM" src="https://github.com/user-attachments/assets/87895ff1-6dfb-47cf-8c8b-84853ced61ad" />

Now search up mono_preprocessing_withoutDBF and enable it since this is the main script that stacks our images.
