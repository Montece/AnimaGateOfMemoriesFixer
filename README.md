# AnimaGateOfMemoriesFixer

How to fix a pseudo-death bug

Operating system: Windows

This guide will help you solve a bug that may occur unexpectedly.
The essence of the bug is that your character has 0 health points, but does not die. The game considers him dead, but the character can still walk. Reboot doesn't help. The character cannot speak to NPCs or interact with the world.

Solution:
1) Download and unzip the archive from the link: https://drive.google.com/file/d/1LbOaX08b6NbmSkxSxJis3WwmFOCFoQji/view?usp=sharing
2) Start the game "Anima Gate Of Memories" and move the character who has a bug in any safe place
3) Run "SharpMonoInjector.exe"
4) Click "Refresh" button
5) Select "[***] AnimaGateOfMemories" in the "Process" list
6) Press the button with three dots under "Assembly to inject"
7) Select the file "AnimaGateOfMemoriesFixer.dll"
8) In the "Class name" field, enter "Main"
9) In the "Method name" field, enter "Entry"
10) Click the "Inject" button
11) Check in the game that the bug has been fixed (in the program at the bottom it should say "Injection successful")
12) Select "[***] AnimaGateOfMemoriesFixer.dll" in the "Injected assemblies" list
13) On the right, in the "Method name" field, enter "Entry"
14) Click the "Eject" button
15) Enjoy the game!