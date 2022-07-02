---
layout: post
title: Nvidia GSync windows quick fix tutorial
author: Álvaro
---

It seems that without a profile, Nvidia drivers don't play nice with some
apps, butchering their FPS in windows. Follow these steps to make sure a profile
with default settings is created, ensuring it plays nicely with GSYNC.

This is a simple tutorial to fix this:
<video width="640" height="360" muted autoplay loop>
<source src="/assets/videos/before-fix_mute.mp4" type="video/mp4">
</video>
to this:
<video width="640" height="360" muted autoplay loop>
<source src="/assets/videos/after-fix_mute.mp4" type="video/mp4">
</video>

# Steps

## 1. Open Nvidia Control Center

Open "Nvidia Control Center" (not GeForce Experience)

![](/assets/images/Screenshot 2022-06-11 210621.png)

## Add the faulty software

Go to Manage 3D Settings

![](/assets/images/Screenshot 2022-06-11 210643.png)

and then click on Add

![](/assets/images/Screenshot 2022-06-11 210756.png)

and select the software you want to fix

![](/assets/images/Screenshot 2022-06-11 210842.png)

## 3. Change the settings

Change the setting from the defaults by setting Monitor Technology to Fixed Refresh:

![](/assets/images/Screenshot 2022-06-11 210922.png)

This will change the settings for Preferred Refresh Rate and Vertical sync, too:

![](/assets/images/Screenshot 2022-06-11 211025.png)

and click on Apply

![](/assets/images/Screenshot 2022-06-11 211051.png)

## 4. Change the settings BACK

Now that the profile has been created, switch the settings BACK TO THEIR DEFAULTS!

Monitor Technology:

![](/assets/images/Screenshot 2022-06-11 211126.png)

Refresh Rate:

![](/assets/images/Screenshot 2022-06-11 211213.png)

Vertical Sync:

![](/assets/images/Screenshot 2022-06-11 211243.png)

Then click on Apply

![](/assets/images/Screenshot 2022-06-11 211312.png)