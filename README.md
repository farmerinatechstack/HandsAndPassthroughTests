# HandsAndPassthroughTests

Goal: create a minimal project which works with AR Foundation, Meta Quest Support, XRI, and XR Hands via OpenXR.

General Notes
- Custom work is in Assets/MyAssets. There are two scenes which copy from Unity templates: HandsDemoScene and PassthroughDemoScene.

Status Updates
- 8/23/2023 #2: updated URP settings so that PassthroughDemoScene now works when built to headset. Note: there are errors on displaying hands, interacting with objects, etc but I'm disregarding that for now. The goal is just to get Passthrough and Hands working.
- 8/23/2023 #1
  - HandsDemoScene works when tested in-editor (has not been tested with a build).
  - Basic passthrough (no hands added yet) does not even work in PassthroughDemoScene. I tested on a build (passthrough in editor is not supported at the time of this commit).
  - Some component of passthrough configuration is probably incorrect, but I have not figured out what the issue is yet.
  - The next step is to try and get PassthroughDemoScene to display passthrough in a build, then create another scene that shows passthrough with hands.
