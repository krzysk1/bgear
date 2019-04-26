# bgear
The Extra 330 SC is a Lycoming AEIO-580-powered single-seat aircraft with improved roll rate and easier roll stops, designed specifically for Unlimited category competition. It is actually the only single-seater aerobatic aircraft built by Extra.

Made by Krzysztof Kaniewski. 
3D model created by Martins Upitis; http://devlog-martinsh.blogspot.com/


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