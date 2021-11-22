# UShallNotPassthrough

This is a 2-player co-op game.

The 1st player uses the Meta headset
  - Install .apk on Meta Quest 1 or 2 (from the latest release)
  - Run UShallNotPassthrough app on the headset

The 2nd player uses the instructions manual (from the latest release)

The players must read the instructions (player 1 reads the instructions in the game, player 2 reads the instructions manual) before starting.

DEVELOPER NOTE: We have Passthrough working but had to disable it due to a bug in the OpenXR SDK. As of this moment, OpenXR doesn't support Oculus Hand Tracking, but Passthrough requires OpenXR. Because of this we had to make a choice between using Passthrough or using Hand Tracking. Given that we can only have one or the other, we decided Hand Tracking was more important to the overall experience, so we opted to not use Passthrough. If this bug is fixed we're willing to update the game to use Passthrough instead of a VR environment.
