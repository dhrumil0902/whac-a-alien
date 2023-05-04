# whac-a-alien
This game was inspired by the classic Whac-A-Mole game. It involves moving a hammer with keyboard keys and pressing the spacebar to attack aliens. Your score is based on the number of aliens you hit before time runs out. The game was built from scratch and applies concepts such as keyboard interrupts, timer interrupts, graphics animation, and double buffering. All the pixels you see in the game were either drawn manually or converted from images to pixels.

## How To Play without a DE1-SOC Board?
1. Download the whac.c file
2. Visit: [https://cpulator.01xz.net/?sys=nios-de1soc&d_audio=48000](https://cpulator.01xz.net/?sys=arm-de1soc&maxmem=2147483632)
3. Go to Settings (bottom left) and set "Memory usage warning" to 2048 MB. Then, click "Apply and Reload" (at the bottom of the settings panel).
4. Return to the Settings panel and uncheck all the values in the "Debugging Checks" section.
5. Upload the whac.c file and set "Language" to C.
6. Click "Compile and Load."
7. Click "Continue" at the top.
8. Under Devices, you should see a VGA pixel buffer screen that is green, displaying the start screen of the game. You can enlarge the screen using the dropdown menu.
9. Locate the "PS/2 keyboard or mouse" under Devices and start typing where it says "Type here." You can drag this panel closer to the VGA pixel buffer screen to make it easier to play the game.
10. Follow the on-screen instructions, using w, a, s, d to move and space to hit.
    
NOTE: THE CPULATOR IS A VIRTUALIZATION TOOL FOR THE ACTUAL DE1-SOC BOARD, AND IT MAY BE LAGGY OR NOT WORK SMOOTHLY.

## Gif Demonstration
![hammer](https://user-images.githubusercontent.com/64914881/200074664-58dacdae-eb80-4228-9569-86e3d0279ac6.gif)
