# Pedalboard Playground
* *Authors* *: [Anya Molodtsova](https://github.com/molodtsovvva), [Ben Rappoport](https://github.com/benthebenno), [Alec Sabol-Pulling](https://github.com/Sergey-ASP).

**Pedalboard Playground** is an application for music learners and enthusiasts. It applies digital audio effects to uploaded sounds, simulating the usage of effects pedals. The program facilitates a learning environment, allowing users to gain proficiency in digital pedal usage, laying the groundwork for understanding analog audio effects and getting familiar with the signal processing foundations. It provides a cost-effective sound-editing solution by offering **10 distinct digital audio effects**, eliminating the need to purchase expensive analog effect pedals.

## Installation Instructions 

To install the program, clone the repository to your local machine or download it as an archive. Inside the repository folder, run the **PedalboardPlayground.exe** file, which will run the application. You're all set!

![image](https://github.com/user-attachments/assets/d5f359ff-698d-480d-b302-11359883bde0)

## Usage Instructions

You can find a video tutorial following [this link](https://molodtsovvva.github.io/pedals.html).
Once you run the program,  you will see a field with 6 slots for effects pedals, 10 pedals themselves, an info box, a * *"Run"* *, and a * *"Clear"* * button. 

To upload a sound to the program, drop it anywhere on the application window, and it will be uploaded automatically. To change a sound, drop another file in. Some sample sounds you can use are located in `../sounds`.
The program is aimed at processing relatively short sound files. It accepts both stereo and mono sound files of all the standard audio formats. Notice that if a mono sound is fed in, it is converted into a stereo file by duplicating the single channel. Thus, the output file will be stereo in all cases.

To apply a pedal, select it by clicking on it and then click on one of the spots in the chain. The pedals can go in arbitrary order, allowing free spots, and can be replaced by just putting another pedal over. To clear the chain, click a "Clear" button on the bottom of the screen. 

After you're happy with your effects selection, click the run button, and the processed sound will be played back to you. If you want to access the resulting sound file, go to `../result/final.wav`, as the returned sound file is always saved as final.wav.

If you have any questions, feel free to reach out to us. * *Happy pedaling!* *
