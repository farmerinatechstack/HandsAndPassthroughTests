# HandsAndPassthroughTests

Goal: create a minimal project which works with AR Foundation, Meta Quest Support, XRI, and XR Hands via OpenXR.

General Notes
- Custom work is in Assets/MyAssets. There are two scenes which copy from Unity templates: HandsDemoScene and PassthroughDemoScene.

Status Updates
- 8/23/2023: HandsDemoScene works when tested in-editor (has not been tested with a build). However, basic passthrough does not even work in PassthroughDemoScene (tested on a build without hands). Some component of passthrough configuration is probably incorrect, but I have not figured out what the issue is yet.
