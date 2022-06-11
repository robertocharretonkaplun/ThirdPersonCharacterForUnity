# ThirdPersonCharacterForUnity
This is a Third Person Character Template to be used in Unity Engine and integrate it into the projects in a simple way.
![Third Person Character Demo](/ThirdPersonCharacter.png)
## How does this assets work?
This is as simple as adding the files into your project.

### Steps
1) Add the 'Third Person Character' prefab into your scene.
   ![Third Person Character Prefab](/ThirdPersonCharacterPrefab.png)
2) Check that the 'Third Person Player has the script 'ThirdPersonControllerV2' as a component of the object.
   ![Third Person Character Script](/ThirdPersonPlayerScript.png)
3) Add the references from the animator to the 'ThirdPersonControllerV2' script.
4) Verify that your animator has the correct references for the animations.
   ![Third Person Character Script](/ThirdPersonPlayerAnimator.png)
5) Add the 'ThirdPersonCameraRotator' script as a component into your main camera or desired camera.
6) Set the reference to follow the target (the player is the target normally).
   ![Third Person Character Script](/ThirdPersonCameraScript.png)
7) Adjust the camera position to follow the target in the correct way.
8) Adjust the script variables to your preference.

# Final Result
![Third Person Character Script](/ThirdPersonCharacterView.png)