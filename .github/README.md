# OSBES Preset Template

This document will walk you through the usage of this template step-by-step to create your own custom OSBES presets.

### Step 1: Template Download

First of all, download this template by clicking [here](https://github.com/osbesdl/PresetTemplate/releases), and select the OSBES version you want to make your preset for (if you're not sure, just use the most recent one)

Next, click "Source Code (zip)", and save the file to your computer.

You'll then want to unzip this folder onto anywhere on your computer, rename it to whatever you want to name your pack, and open the folder.

### Step 2: Manifest Setup

After you have entered the pack folder, open the file `manifest.json` with a text editor of your choice; Then follow these steps:

- Replace both instances of `DESCRIPTION` with a short description of what your pack changes. This will be displayed below your pack name in-game

- Replace `PACK NAME` with the name of your pack

- Replace `UUIDv4` and `UUIDv4 2`  with two UUIDs generated from [www.uuidgenerator.net](www.uuidgenerator.net)
  
  - These two UUIDs must, and I repeat, **MUST** be different from one-another

- Replace `YOUR NAME` with your username, or whatever you want to be credited as

### Step 2.5: PBR definition

If you have PBR textures included within your pack, download [this zip](https://drive.google.com/file/d/1fq0sw9H99-9MKoUr2wokpT3RKXHck-CM/view?usp=sharing) and extract the contents into the root of your pack (the part with `manifest.json` in it)

If you are unsure of what any of this means or if you are not using PBR, just ignore this step and move on to step 3

### Step 3: Icon

You *can* skip this step, although I would advise that you still create your own icon to differentiate your preset from others.

    0. Make sure that you already have a pack icon ready (This icon must be 500x500 resolution)

1. Delete the default pack icon named `pack_icon.png`

2. Open your custom pack icon in an image editor of your choice

3. Layer the included image labelled `icon-template.png` on-top of your custom icon

4. Save this edited image in the pack folder as `pack_icon.png`

### Step 4: Make your changes!

At this point you have set up the preset pack to the point where you can start making your own changes!

All of the files that you are recommended to change are in `shaders/glsl/includes/options`, however if you need to change any other file in the shader, you can download that file/files from the shader itself and put them in the template under the same file structure.
