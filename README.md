# bgear
Extra 300S (BGE Air Race) for Aerofly FS4

**THE MODEL HAS NO DETAILED COCKPIT AND NO DEVELOPMENT IS PLANNED NOW**

The Extra Flugzeugbau EA300 is a two-seat aerobatic monoplane capable of Unlimited category competition.

This is free add-on for Aerofly FS4 created by Krzysztof Kaniewski with the Aerofly FS4 SDK. 
Original 3D model created by Martins Upitis; http://devlog-martinsh.blogspot.com/]>. Thanks to him. 
Flight dynamic model based on default Aerofly FS 330LX.
 
Martins Upitis write: The BGE Air Race project is dead, but from the positive side I have some nice stuff to share with you. So I give you this nice low-poly aerobatics aircraft to play with. The model is based on Extra 300L  and I used Zivko Edge 540 cockpit as the reference for the interior.

Creative Commons License
This work is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.
so basically you can do anything with it.

 Some features may not work as intended and this aircraft could crash your Aerofly FS4. 
 Use it at your own risk!
 
# Installation & Sound

1. Unzip file and move the folder "bgear" into the C:\Users\~\Documents\Aerofly FS 4\aircraft folder.

2. Copy all *.tsb files from "extra300" folder from your Aerofly FS4 installation path into "bgear\sounds" folder.

# Uninstall

1. Delete the folder "bgear".

# Resources

Aircraft Technical Data & Specifications https://www.manualslib.com/products/Extra-300s-4117778.html

There are other liveries in folders:

- blender
- bw
- red
- star
- white

# Tips

How to change to expert mode:

        <[servoclassic][ServoLeftAileron]>
            <[float64][P1][0.4]>				=>	            <[float64][P1][0.78]>
            <[float64][P3][0.1]>				=>	            <[float64][P3][0.18]>
        <[servoclassic][ServoRightAileron]>
            <[float64][P1][-0.4]>				=>	            <[float64][P1][-0.78]>
            <[float64][P3][-0.1]>				=>	            <[float64][P3][-0.18]>
        <[servoclassic][ServoElevator]>
            <[float64][P1][0.3]>				=>	            <[float64][P1][0.5]>
        <[airfoil][AirfoilRoot]> and <[airfoil][AirfoilTip]>			
            <[float64][StallRange][0.2]>		=>	            <[float64][StallRange][0.1]>
        <[aerowing][StabilizerAero]>
            <[float64][PropwashRotation][0.0]>	=>	            <[float64][PropwashRotation][0.01]>
=======
>>>>>>> parent of 0dfe043... Update README.md
