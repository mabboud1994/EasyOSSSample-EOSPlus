# EasyOSS Project sample for UE 5.4.4, EOS Plus OSS

## Requirements

1. **You must run the project with Unreal engine version 5.4.4** 
2. **You must have a product configured in epic game dev portal**
3. **You must have a steam app id**
4. **Your EOS Product must have a steam identity provider configured**

## How to run the sample

1. Go to `config/DefaultEngine.ini`, then configure EOS Voice Chat according to your EOS Product configuration, then put your steam app id in the steam plugin section.
2. In the project root directory, create a folder named `Plugins` then copy the Easy OSS plugin into it.
3. Open the .uproject file with UE Editor Version 5.4.4
4. Go to `Edit->Plugins`, then make sure that Easy OSS Plugin is activated. You must have the plugin installed for this engine first.
5. Go to `Edit->Project Settings`, search for epic online services plugin then configure it according to you EOS Product configuration.
6. Go the `Main menu->Game Instance` then open the game instance blueprint.
7. Go the function `Get EOS Trusted Server Artifact`, then modify its output to fit your EOS trusted server artifact.
8. Modify the client bat script by providing your you pathes.
9. Modify the dedicated server bat script by providing you pathes and your epicapp.
10. Open the steam client application and make sure that your are authenticated.
10. Run the client bat script to test the game.
