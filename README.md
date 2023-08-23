# HandsAndPassthroughTests

Goal: create a minimal project which works with AR Foundation, Meta Quest Support, XRI, and XR Hands via OpenXR.

General Notes
- I don't plan to maintain this repo, but feel free to use as you wish. I  wanted to get a basic sample working and I saw others post the same, so I created a quick repo with my configurations.
  - Don't count this as "development ready" or "productionized." I just merged packages and settings together into a testable starting point.
- Custom work is in Assets/MyAssets. There are three scenes which copy from Unity templates, but HandsAndPassthroughDemoScene is the most important. That scene shows controllers or hands with passthrough.
  - HandsDemoScene was a scene I used to test XR Hands.
  - PassthroughDemoScene was a scene I used for testing passthrough (and also technically does support some hand tracking).
- If you're curious about exploring these packages or prototyping XR experiences together too, you can message me on Discord at farmerinatechstack or on LinkedIn (Hassan Karaouni).

Status Updates
- 8/23/2023 #3: HandsAndPassthroughDemoScene has a rough sample of hands working with passthrough.
- 8/23/2023 #2: updated URP settings so that PassthroughDemoScene now works when built to headset. Note: there are errors on displaying hands, interacting with objects, etc but I'm disregarding that for now. The goal is just to get Passthrough and Hands working.
- 8/23/2023 #1
  - HandsDemoScene works when tested in-editor (has not been tested with a build).
  - Basic passthrough (no hands added yet) does not even work in PassthroughDemoScene. I tested on a build (passthrough in editor is not supported yet).
  - Some component of passthrough configuration is probably incorrect, but I have not figured out what the issue is yet.
  - The next step is to try and get PassthroughDemoScene to display passthrough in a build, then create another scene that shows passthrough with hands.
