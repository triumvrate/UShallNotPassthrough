# UShallNotPassthrough

This is a 2-player co-op game.

The 1st player uses the Oculus headset
  - Install .apk on Quest 1 or 2
  - Run UShallNotPassthrough app on the headset
  - 
The 2nd player uses an instructions manual: https://drive.google.com/file/d/1Tp2noMx9-9BxA_8s4lrPk0D4HxmpEyw0/view?usp=sharing

The players must read the instructions (player 1 reads the instructions in the game, player 2 reads the instructions manual) before starting.

DEVELOPER NOTE: We have Passthrough working but had to disable it due to a bug in the OpenXR SDK. As of this moment, OpenXR doesn't support Oculus Hand Tracking, but Passthrough requires OpenXR. Because of this we had to make a choice between using Passthrough or using Hand Tracking. Given that we can only have one or the other, we decided Hand Tracking was more important to the overall experience, so we opted to not use Passthrough. If this bug is fixed we're willing to update the game to use Passthrough instead of a VR environment.
