# CPPUE5MultiplayerShooter



Working through Unreal Engine 5 C++ Multiplayer Shooter Course on udemy. In Progress!

https://www.udemy.com/course/unreal-engine-5-cpp-multiplayer-shooter/

![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/UnrealEngine5C%2B%2BMultiplayerShooterUdemy.png)


# Finished Sections of course

## Section 1: Introduction

## Section 2: Creating A Multiplayer Plugin

## Section 3: Project Creation

Had to go through this youtube video to do retargeting for UE5.2
https://www.youtube.com/watch?v=_sLnCqBaElI

Also had to add Enhanced Input, using code/setup from previous project here
https://github.com/jacobmott/CPPUE5UltGameDevCrs/blob/main/Source/CPPUE5UltGameDevCrs/Public/Characters/SlashCharacter.h

![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_1.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_2.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_3.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_4.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_5.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_6.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_7.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3_8.png)


![](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/CPPUE5MultiplayerShooter-Section1-3.gif)


### Youtube vid

https://youtu.be/46iaDDNVhOo

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/46iaDDNVhOo/0.jpg)](https://youtu.be/46iaDDNVhOo)


## Section 4: The Weapon

![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon1.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon2.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon3.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon4.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon5.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon6.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon7.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon8.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon9.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon10.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon11.png)
![image](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon12.png)


![](https://media.githubusercontent.com/media/jacobmott/CPPUE5MultiplayerShooter/main/Screenshots/Sec4TheWeapon.gif)


### Youtube vid

https://youtu.be/GSGzTB4VxPA

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/GSGzTB4VxPA/0.jpg)](https://youtu.be/GSGzTB4VxPA)


# Started Section

## Section 5: Firing Weapons

# Project Setup/Install instructions
The Content folder is not included as part of this project, if you want a copy of it, contact me @ vortexgamesemail@gmail.com


## For me
The content folder is stored in s3 bucket
Pull down from bucket
```
  aws s3 cp --recursive s3://<bucket>/CPPUE5MultiplayerShooter/Blaster/Content Blaster/Content
  aws s3 cp --recursive s3://<bucket>/CPPUE5MultiplayerShooter/MPTesting/Content MPTesting/Content
  aws s3 cp --recursive s3://<bucket>/CPPUE5MultiplayerShooter/MenuSystem/Content MenuSystem/Content
```

Push to bucket
```
  aws s3 cp --recursive Blaster/Content s3://<bucket>/CPPUE5MultiplayerShooter/Blaster/Content
  aws s3 cp --recursive MPTesting/Content s3://<bucket>/CPPUE5MultiplayerShooter/MPTesting/Content
  aws s3 cp --recursive MenuSystem/Content s3://<bucket>/CPPUE5MultiplayerShooter/MenuSystem/Content
```


