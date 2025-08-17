# Background Music for ES-DE on Android Using Tasker

Instructions for setting up background music to play in ES-DE frontend using [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en) (paid app)

- [Background Music base functionality setup](https://github.com/RobZombie9043/bgmusic-android-es-de/edit/main/README.md#background-music-base-functionality-setup)
- [Optional Screensaver Controls](https://github.com/RobZombie9043/bgmusic-android-es-de/edit/main/README.md#optional-screensaver-controls)

<hr/>

## Background Music base functionality setup
<details>
<summary>Step-by-step instructions for setting up a background music profile in Tasker</summary>

<hr/>

A premade project file that can be imported in Tasker is available [here](https://github.com/RobZombie9043/bgmusic-android-es-de/blob/main/Resources/Background_Music.prj.xml). 

Below instructions detail how to create this profile from scratch.

> 💡 If it is the first time you are using Tasker it will likely prompt a number of times through the setup for permissions to complete the functionality required to do this. Follow the prompts when this happens to grant the appropriate permissions. 

<hr/>

### 1) Tap `+` to create new profile 
<img width="1920" height="1080" alt="Screenshot_20250817-074500" src="https://github.com/user-attachments/assets/dda1fef0-2fe0-4e6c-bbf3-26cd24fb79f5" />

<hr/>

### 2) Choose `Application`
<img width="1920" height="1080" alt="Screenshot_20250817-074504" src="https://github.com/user-attachments/assets/555de198-5748-40eb-89f0-a9414137c439" />

<hr/>

### 3) Choose `ES-DE`
<img width="1920" height="1080" alt="Screenshot_20250817-074510" src="https://github.com/user-attachments/assets/8bf417f5-476a-483b-8651-1293a91c2382" />

<hr/>

### 4) Tap `New Task +`
<img width="1920" height="1080" alt="Screenshot_20250817-074526" src="https://github.com/user-attachments/assets/d14d9daf-5e83-48ce-a55d-0a877493ca92" />

<hr/>

### 5) Type in name for new task - `Start Music`
<img width="1920" height="1080" alt="Screenshot_20250817-074555" src="https://github.com/user-attachments/assets/adc8ca29-2b36-4dec-8430-9f5c92be7caa" />

<hr/>

### 6) Tap `+` to add task and choose `Media`
<img width="1920" height="1080" alt="Screenshot_20250817-074608" src="https://github.com/user-attachments/assets/cb8382b9-8a20-4dec-b187-0951d18740ac" />

<hr/>

### 7) Choose `Music Play Dir`
<img width="1920" height="1080" alt="Screenshot_20250817-074618" src="https://github.com/user-attachments/assets/2491d657-5154-4f52-9d9a-d73ef8f58362" />

<hr/>

### 8) Tap `🔍` for adding directory
<img width="1920" height="1080" alt="Screenshot_20250817-074635" src="https://github.com/user-attachments/assets/341dc5ef-8a9e-4191-be47-45e492b92fcf" />

<hr/>

### 9) Choose the folder to use for storing Music
<img width="1920" height="1080" alt="Screenshot_20250817-074717" src="https://github.com/user-attachments/assets/f51f0f40-4f78-4a57-b645-8603971fc608" />
<img width="1920" height="1080" alt="Screenshot_20250817-074720" src="https://github.com/user-attachments/assets/76e18116-83cb-4f21-a3ad-88ed8a19962e" />

<hr/>

### 10) Tick `Audio Only` (only look for known audio file types), `Random` (randomise playlist each time), and `Flash` (flash message with song title)
<img width="1920" height="1080" alt="Screenshot_20250817-074751" src="https://github.com/user-attachments/assets/12e69e5a-16df-43f4-b3da-1aafdc80534f" />

<hr/>

### 11) Go back and then back again to get back to the Profile screen
<img width="1920" height="1080" alt="Screenshot_20250817-074757" src="https://github.com/user-attachments/assets/3cf4d27d-0b71-4db8-afc8-797e5933ec6c" />
<img width="1920" height="1080" alt="Screenshot_20250817-074804" src="https://github.com/user-attachments/assets/15cc6d88-8706-47dc-adff-6fc388a1860d" />

<hr/>

### 12) Long press on the `Start Music` task to bring up sub menu and choose `Add Exit Task <-`
<img width="1920" height="1080" alt="Screenshot_20250817-074808" src="https://github.com/user-attachments/assets/03456497-5503-4394-8fb8-24e416bd9ee6" />

<hr/>

### 13) Choose `New Task +`
<img width="1920" height="1080" alt="Screenshot_20250817-074812" src="https://github.com/user-attachments/assets/5f83c2c3-5b10-46b3-adf6-f0ae5681b56a" />

<hr/>

### 14) Type in name for new task - `Stop Music`
<img width="1920" height="1080" alt="Screenshot_20250817-074836" src="https://github.com/user-attachments/assets/fad732c8-4ee9-4370-bfe0-41d120fa8e8b" />

<hr/>

### 15) Tap `+` to add task
<img width="1920" height="1080" alt="Screenshot_20250817-074840" src="https://github.com/user-attachments/assets/63c62728-509a-4bee-ab10-a25bc0ade59c" />

<hr/>

### 16) Choose `Media`
<img width="1920" height="1080" alt="Screenshot_20250817-074848" src="https://github.com/user-attachments/assets/91277f54-c725-49b0-8258-546e09866455" />

<hr/>

### 17) Choose `Music Stop`
<img width="1920" height="1080" alt="Screenshot_20250817-074856" src="https://github.com/user-attachments/assets/1e43443f-6dee-46ff-bfb4-b0f508a21787" />

<hr/>

### 18) No further changes needed in this menu, go back and then back again to get back to the Profile screen
<img width="1920" height="1080" alt="Screenshot_20250817-074900" src="https://github.com/user-attachments/assets/f83fe9cc-5bbe-4dd9-8edd-2166d9370c5f" />
<img width="1920" height="1080" alt="Screenshot_20250817-074906" src="https://github.com/user-attachments/assets/956c40bf-6f9b-4925-bcc1-ae03f82e99bb" />

<hr/>

### 19) Long press on the `ES-DE` profile to bring up sub menu and choose `Add +`
<img width="1920" height="1080" alt="Screenshot_20250817-082508" src="https://github.com/user-attachments/assets/884c4d51-a717-40ff-b8ca-b46bb3de04b0" />

<hr/>

### 20) Choose `State`
<img width="1920" height="1080" alt="Screenshot_20250817-082516" src="https://github.com/user-attachments/assets/234883f6-ccc0-441d-92aa-41494fe91b4c" />

<hr/>

### 21) Choose `Display`
<img width="1920" height="1080" alt="Screenshot_20250817-082525" src="https://github.com/user-attachments/assets/78f65da1-3df8-4ed0-ac41-7838120a1df3" />

<hr/>

### 22) Choose `Display State`
<img width="1920" height="1080" alt="Screenshot_20250817-082529" src="https://github.com/user-attachments/assets/eaf4e56a-f8ef-485e-b863-a03b6ef06188" />

<hr/>

### 23) Change `Is` dropdown box from `Off` to `On` (this stops bg music from playing when device is put to sleep)
<img width="1920" height="1080" alt="Screenshot_20250817-082536" src="https://github.com/user-attachments/assets/bd61d740-a5a2-420d-873e-9500c5ba5b4e" />
<img width="1920" height="1080" alt="Screenshot_20250817-082540" src="https://github.com/user-attachments/assets/31a868ae-bf26-442c-a903-4d195f2f3582" />

<hr/>

### 24) Go back to the main profile screen and tap `✓` in top right of screen to confirm new tasks
<img width="1920" height="1080" alt="Screenshot_20250817-082544" src="https://github.com/user-attachments/assets/1ef90cf1-2e11-4908-b407-e262e0ac64e9" />

<hr/>

</details>

<hr/>

## [Optional] Screensaver Controls
<details>
<summary>Optional instructions for setting up controls for background music playback during the ES-DE screensaver</summary>

<hr/>

This is an optional set up to enable some more advanced control over the background music playing during the screensaver playing in ES-DE.

> 💡 This example will work through hooking in to the screensaver-start and screensaver-end events using ES-DE's custom event scripting functionality and pausing the playback of bg music during the screensaver and then playing music again when exiting the screensaver. Similar logic could be followed to alter the volume of music playback during the screensaver event etc.

### 1) Go in to ES-DE `Main Menu` -> `Other Settings` > `Enable Cutom Event Scripts` and toggle this on
<img width="1920" height="1080" alt="Screenshot_20250817-131527" src="https://github.com/user-attachments/assets/420b33f6-5b01-499a-af5c-2399b6f91544" />

<hr/>

### 2) Copy the script files from [here](https://github.com/RobZombie9043/bgmusic-android-es-de/tree/main/Resources/scripts) to the ~ES-DE\scripts folder
The resultant file structure should look like:
```
~ES-DE\
~ES-DE\scripts\
~ES-DE\scripts\screensaver-end\
~ES-DE\scripts\screensaver-end\screensaver-end.sh
~ES-DE\scripts\screensaver-start\
~ES-DE\scripts\screensaver-start\screensaver-start.sh
```

<hr/>

### 3) Steps to be detailed (WIP)

<img width="1920" height="1080" alt="Screenshot_20250817-125857" src="https://github.com/user-attachments/assets/14fac6b0-46e7-4770-888f-b050050af8a4" />
<img width="1920" height="1080" alt="Screenshot_20250817-125906" src="https://github.com/user-attachments/assets/9e884fba-7015-4342-bb32-58ec8b5127ce" />
<img width="1920" height="1080" alt="Screenshot_20250817-125910" src="https://github.com/user-attachments/assets/b7e723f4-f4e5-46e5-93d1-71c769393f44" />
<img width="1920" height="1080" alt="Screenshot_20250817-125916" src="https://github.com/user-attachments/assets/21b06d72-4d17-43f9-b0d0-a892ab09a806" />
<img width="1920" height="1080" alt="Screenshot_20250817-130003" src="https://github.com/user-attachments/assets/42d95615-da60-461e-b917-b7a893a1945f" />
<img width="1920" height="1080" alt="Screenshot_20250817-130011" src="https://github.com/user-attachments/assets/6c4fd7f5-29b0-4751-a085-4a83cdd734bf" />
<img width="1920" height="1080" alt="Screenshot_20250817-130120" src="https://github.com/user-attachments/assets/279d8d45-88d7-497c-a5e3-e51779d582f1" />
<img width="1920" height="1080" alt="Screenshot_20250817-130136" src="https://github.com/user-attachments/assets/f664f562-495d-4d51-aef8-090488c4dfff" />
<img width="1920" height="1080" alt="Screenshot_20250817-130154" src="https://github.com/user-attachments/assets/0948cd67-10ac-4161-8052-d42783b1019e" />
<img width="1920" height="1080" alt="Screenshot_20250817-130234" src="https://github.com/user-attachments/assets/6bc524ec-d26c-496e-9887-946318977fa8" />
<img width="1920" height="1080" alt="Screenshot_20250817-130241" src="https://github.com/user-attachments/assets/554c5585-bb2f-4c1b-954b-b1cfd12c5590" />
<img width="1920" height="1080" alt="Screenshot_20250817-130354" src="https://github.com/user-attachments/assets/4a54dba8-60fc-4eed-a1b1-18d586b8d11e" />
<img width="1920" height="1080" alt="Screenshot_20250817-130401" src="https://github.com/user-attachments/assets/8de99458-d766-40a9-85ba-30804e9e9b38" />
<img width="1920" height="1080" alt="Screenshot_20250817-130425" src="https://github.com/user-attachments/assets/52dd8a5b-0abc-4a34-a7d5-0a080a25c508" />
<img width="1920" height="1080" alt="Screenshot_20250817-130448" src="https://github.com/user-attachments/assets/27c08afa-3306-4d8d-aabf-d96fd5339a49" />
<img width="1920" height="1080" alt="Screenshot_20250817-130518" src="https://github.com/user-attachments/assets/7282e2fa-7bff-4520-867d-ed1dfb407cd2" />
<img width="1920" height="1080" alt="Screenshot_20250817-130528" src="https://github.com/user-attachments/assets/85e93d3c-8ab4-4ec6-acda-fe2386891601" />
<img width="1920" height="1080" alt="Screenshot_20250817-130534" src="https://github.com/user-attachments/assets/36e060e8-1518-44c7-8652-54c24c5cec1f" />
<img width="1920" height="1080" alt="Screenshot_20250817-130541" src="https://github.com/user-attachments/assets/e858222f-575e-4e41-bbe0-9f2cf7bc456f" />
<img width="1920" height="1080" alt="Screenshot_20250817-130555" src="https://github.com/user-attachments/assets/435ea00f-b6da-4b1e-a370-881cc5ee5cd4" />
<img width="1920" height="1080" alt="Screenshot_20250817-130600" src="https://github.com/user-attachments/assets/6541955f-506f-4a89-825f-03ef5873f995" />
<img width="1920" height="1080" alt="Screenshot_20250817-130604" src="https://github.com/user-attachments/assets/debb257b-7f08-441d-867d-7f6b426203d2" />
<img width="1920" height="1080" alt="Screenshot_20250817-130632" src="https://github.com/user-attachments/assets/6a968c1e-535b-472a-8edd-e557987241e2" />
<img width="1920" height="1080" alt="Screenshot_20250817-130644" src="https://github.com/user-attachments/assets/1b957d92-31a1-45cc-bbe9-85cf5ebed063" />
<img width="1920" height="1080" alt="Screenshot_20250817-130657" src="https://github.com/user-attachments/assets/f0fe2367-a6b1-4bbf-8fcc-a4fcfdb521c8" />
<img width="1920" height="1080" alt="Screenshot_20250817-130702" src="https://github.com/user-attachments/assets/d905e6bd-4eb2-47bf-82f3-c7c8fae9e68c" />
<img width="1920" height="1080" alt="Screenshot_20250817-130709" src="https://github.com/user-attachments/assets/15117d10-7159-4209-9223-31b7709ef907" />
<img width="1920" height="1080" alt="Screenshot_20250817-130722" src="https://github.com/user-attachments/assets/1c11eedb-d4e6-4f24-b60b-97f40c8187b4" />


</details>

<hr/>

## Updates to come
- [ ] Add hook into screensaver event to allow control of music playback during screensaver (i.e. lower volume or stop music playback during screensaver)
- [ ] Add customisations to music title flash message displaying song title
- [ ] Investigate possibilty of music control shortcuts (next track, pause, play?)


