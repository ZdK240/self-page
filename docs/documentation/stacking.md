# Siril
<img width="375" height="177" alt="Screenshot 2026-07-28 133403" src="https://github.com/user-attachments/assets/c4b8074b-7cca-4bd0-9eca-d0443c6df1b7" />

-> Siril is an image tool which can stack images, analyze images, and do much more ([more details on their website](https://siril.org/)).

It can take multiple modules to do many kinds of tasks, with the most important in our application being Starnet, 
which allows us to stack images automatically using a Python script

This documentation is meant to help set up Siril, to show the installation of Starnet, and how the images must be set up in order to 
stack them.

## Installation of Siril
First of all, we go to the [website](https://siril.org/), where we are greeted by the following screen:
<img width="1366" height="766" alt="Siril - Downloads - Google Chrome 7_28_2026 1_29_34 PM" src="https://github.com/user-attachments/assets/ca5016df-7b83-4feb-a61f-80f394dcb616" />

Here, we can select the OS we are running and select the installer depending on OS and the chip (in case of Mac). However, since I am using a Windows,
I will be selecting the Windows option. To make installation and running easier for Windows users, I recommend using the Portable installer, which installs a zip file
with an .exe file in the bin folder.
<img width="870" height="496" alt="bin - File Explorer 7_28_2026 1_59_05 PM" src="https://github.com/user-attachments/assets/e3b6d268-e8fe-44b1-b7cf-3e6319c129cd" />

Run the siril.exe file, let the Windows CMD do some background processes, and you will see this screen.
<img width="1150" height="749" alt="Siril-1 4 4 7_28_2026 2_02_44 PM" src="https://github.com/user-attachments/assets/c1466846-5cb6-41b5-b888-e40762b3ad1a" />

## The Setup & Process
-> Now you must press the blue button for a drop-down menu like this, and press 'Get Scripts' to get a menu as shown below:
<img width="800" height="703" alt="Siril-1 4 4 7_28_2026 2_20_19 PM" src="https://github.com/user-attachments/assets/87895ff1-6dfb-47cf-8c8b-84853ced61ad" />

Now search up mono_preprocessing_withoutDBF and enable it since this is the main script that stacks our images.

Nest, press the home button (coloured blue) and set up a directory with a folder named 'lights', where you will be keeping the images that you want to stack (images are in .fits).
<img width="990" height="737" alt="Siril-1 4 4 7_29_2026 11_43_25 AM" src="https://github.com/user-attachments/assets/abdc788d-8d60-4a17-974d-d9d507f0c961" />

Then you set the working directory as the parent folder for the images folder, which in my case here would be 'Pictures'. Go to that folder and press 'Open' (located at bottom-right of the window).

Then you can go back to the drop-down menu, script list, and click on the script that we installed (mono_preprocessing_withoutDBF).

Let the script run its course, and it will finish stacking it for you, with the time taken depending on the number of images to stack.

When done, there should be a new file called 'result.fits' in the parent folder for the images, which you can open to see the result of the script.
<img width="990" height="737" alt="Siril-1 4 4 7_29_2026 11_51_26 AM" src="https://github.com/user-attachments/assets/f07c3920-12d2-43f1-a995-75b68cf6d138" />
<img width="1343" height="749" alt="Siril-1 4 4 7_29_2026 11_52_01 AM" src="https://github.com/user-attachments/assets/6f6da722-405a-4a02-80b5-5c281275f8d6" />

(Do remember to set this particular setting from 'Linear' to 'Autostretch'):
<img width="1288" height="254" alt="Screenshot 2026-07-29 130144" src="https://github.com/user-attachments/assets/1a5615b5-25a2-44a4-9d7b-ab4d12753e8e" />

Now we shall take a detour to install Starnet, which is a script or software that helps in removing stars from the image, as far as my own knowledge goes for this app. In this case, it will help us to see only the galaxy in the image shown, so as to observe it better.

Firstly, we go to the Starnet [download page](https://starnetastro.com/cli-tools/starnet/) where we will install a .exe file or zip file according to preference and OS.<img width="1365" height="766" alt="Screenshot 2026-07-29 103047" src="https://github.com/user-attachments/assets/5f6cd391-9a5e-409a-a310-4e429a6f31c9" />

I have not used the installer, but instead used the zip file. so this documentation is mainly for the installation of the zip file.

After installing the zip file, we extract it and leave it anywhere, as long as you do not forget where it is.

Then, go press the three bars near the minimize button at the top-right, press preferences and see this screen:
<img width="800" height="703" alt="Siril-1 4 4 7_29_2026 12_40_23 PM" src="https://github.com/user-attachments/assets/7930234c-fc8d-42c5-ab9b-c6843d1ef6e2" />

Go to 'Miscellaneous' and after pressing the first option to select a file from the 'Software Location' menu, select the starnet2.exe file in your unzipped folder.

After this, there should be the 'Image Processing' menu above in the options.
<img width="1343" height="749" alt="Siril-1 4 4 7_29_2026 12_39_07 PM" src="https://github.com/user-attachments/assets/480bfc46-3bee-4545-b28a-6123bdb5a79b" />

Press on that for a drop-down menu, select 'Star Processing', then 'Starnet Star Removal'. You will see a menu with options for star removal, where you can tweak it if you must and press 'Execute'. In our case, we can leave it as default.
<img width="1365" height="766" alt="Screenshot 2026-07-29 124512" src="https://github.com/user-attachments/assets/c54ca5b8-9e2d-4905-a5ee-a2e2b460830a" />

Then we will get an image without stars as seen below:
<img width="522" height="354" alt="Screenshot 2026-07-29 130338" src="https://github.com/user-attachments/assets/4ce1844e-e5e8-4bbe-9a44-bbb486d6873c" />

With this result (possibly) being on your screen, you can rest assured that you know how to do this now.
