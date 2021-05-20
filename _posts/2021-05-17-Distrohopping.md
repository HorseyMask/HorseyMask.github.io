--- 
layout: post
title:  "Distrohopping"
date:   2021-5-20 21:33:00 +0900
categories: [tech]
---

![Completed Build](/assets/images/2021-05-20distro/2021-05-20_21-29.png){:class="img-responsive"}

I got a bit bored. So I decided to do some distrohopping. Well, to be more exact, I moved away from Windows 10 on my main system to Linux, then I went on a bit of distrohopping adventure, meaning that I tried out a bunch of different Linux distributions, or distros. On the way, I've learned a lot, and that with my current habits and usecases for a computer, Linux fits it very well. With this post, I'm looking to go through my process of throwing myself through countless installs (and maybe a few more) to where I finally landed.

## The rationale to pack up my bags and move
As for *why* I made the move away from Windows in the first place, it was mostly due to three factors:
- Lack of control
- Privacy concerns
- Boredom

Privacy concerns has been a great issue from the start of Windows 10, though it's probably been going on before then. With all sorts of telemetry being collected, it's been an obvious issue. It can be disabled with some registry changes, or ripped out entiretly from the ISO with unofficial tools, but it's just not an ideal experience. Lack of control is also a lesser issue, as you could technically wrangle Windows around to do some things that you want it to do. For example, you could technically control Windows Update to make sure you aren't getting any major updates immediatly as history shows that there are issues with new Windows updates. However, sometimes Windows works again your decisions and installs the updates anyways. Finally, I just got bored of Windows, after using it for so long, and wanted to jump over to try something new.

## The move to the first distro - Pop!_OS
Looking around doing my research at the offered distros, I decided to head with Pop!_OS, as it seemed to be a great and easy to use distro with some added features.
Pop!_OS is a Ubuntu based distro developed by the folks at System76, a computer hardware company most well known for their laptops. I hold them to a pretty high regard, and I thought that thier take on Linux would be a great experience. And I was right in that thinking. The little features they added into the Pop!_OS ecosystem were very good, such as the window management system included right in the box. It was a great introduction to an new way of using my desktop space that will soon follow me to the other distros that I tried.

The ease of use and compatibility was a welcoming suprise for myself. Previously, due to a bug with my graphics card with the Linux kernel, I was simply unable to use any graphical application at all, which was a huge issue. But after doing some research, I was able to finally fix the issue for myself, and use a Linux setup with a proper desktop. I was also able to run all the apps that I really needed for myself, and everything really did seem to come together quite well. Even the few games that I still play ran very well, native or with Steam's Proton compatibility layer.

There were still a major issue that I had with this distro: Boredom. While Pop!_OS is a great distro with all the customizations that System76 brought to it, it was still Ubuntu under all the customization. Having used Ubuntu for a short bit before, I still wanted something different. Also, I didn't really fancy the GNOME desktop environment that it shipped with. I wanted something a bit more simple.

This is in no way me trying to disparage Pop!_OS or System76. In fact, I think System76 has a goldmine of a distro on their hands. An easy to use Linux distro with enhancements that enthusiasts would enjoy? Priceless for many. I would recommend it to many as a starting begineer Linux experience, but I was looking for something else. So I started packing up my bags and prepared to move out again to where many move on next: the Arch family.

## btw i use ~~arch~~ manjaro
The next stop for my distrohopping ways was Manjaro Linux. I always did want to try out the Arch based distros, but I was always intimidated by the fabled difficulity of installing said distro to a computer that I would use daily. So, as a compromise, I just decided to try out Manjaro first. Along with this, influenced by the window manager features that Pop!_OS spoiled me with, I also decided to try out a full fledged window manager. I decided to use Awesome, as it seemed like an easier window manager to use for a beginner. The Awesomewm Manjaro edition had a customized version of Awesome with a lot of graphical features that I thought catered more towards a beginner. And by trying it out, I was right. I found myself adjusting quite well with Awesome, and while I don't think I took advantage of all the available features, it was a great first time experience with a window manager.

Back to Manjaro as a distro though. Overall, I did enjoy my experience here, but I think that I could have had a better experience had I been better informed. While I was changing distros from Pop!_OS to Manjaro, I was also looking for a less bloated distro, one with only the programs that I needed. Well, the full-fledged Manjaro wasn't really that. I felt that there was a lot of included software that I did not need, and I didn't want to start stripping it down to break something else. Meanwhile, the minimal verion of Manjaro was a lot more... well, minimal, but felt like it was missing some important things that I did need. It felt like a messy situation where I needed a bit more control than I had.

Also, there were a lot of other technical issues, espically with automounting drives and setting up services. While I was able to get my NTFS drives from my Windows installation working, I could not get a Windows dynamic drive set up properly to be automounted. This came down to me not being able to set up the services correctly for the dynamic drive to be automounted, and I could not figure it out.

Manjaro did teach me some valuable lessons, such as that I wanted to use a window manager, and not rely on a desktop environment. However, with the issues that compounded throughout my experience, it was time to move again. This time though, I thought, 'What if I go even more simplier, to a barebone installation of Linux so I can install just the stuff I need?'. So instead of going back to a more "done-for-you" distro, I decided to dig myself deeper, and take the jump to proper Arch Linux.

## btw i use arch
A lot of people who fall in the rabbit hole of Linux eventually find their way to Arch, one way or the other. I was finally able to take the chance here. Installing Arch went a lot more smoother than I initally expected. While everything was done in the command line, from partition and preparing a drive to the actual installation process, it wasn't as bad as some people make it out to be. By roughly following online guides, I was able to finish up the base installation, albeit with some minor hitches here and there. 

After finishing up the installation and booting into the system for the first time, the first real advantage of Arch came out to me instantly: the freedom and control. In all my previous distros, every installation pre-installs some sort of application, and does a lot of default setup for the hardware. Arch completly threw this out and left me with a blank terminal screen. The bare essential software installed, with the bare minimum hardware configurations to get the computer booted. While this can be daunting and require a lot of work for some, this situation was actually quite refreshing. The fact that from here, I can set up my system, install only the software that I need (and want) was a novel concept.

With the freedoms that Arch Linux gave me, it was actually easier to set up my new system than my previous two distros that I tried, believe it or not. With the proper software and right configurations, all my NTFS hard drives were automounting with no issues, unlike Manjaro. With reading the documentation and following the instructions, I had mostly a very smooth experience with everything that mattered. All my programs were more or less working, and I was even able to do things such as set up a parametric equalizer properly with Arch that was a lot harder with other distros. It was truly surprising how everything did work out easily enough, and in the way I wanted.

On the way, I also changed my tiling windows manager away from Awesome. I found that the added features on Awesome in the Manjaro edition to be harder to add by my own, so I decided to just branch off and find other options. I tried two, spectrwm and qtile, and I ended up settling on qtile, due to the usage of a familar language in Python for configuration and the great documentation provided. I do want to go back and give spectrwm another try though, as it does seem like an even more lightweight window manager than qtile. But for now, I am happy with the configuration of qtile that I came up with.

With all of this work done, I think I've found my place to stay for now. Arch has given me a lot more control over how my operating system works, and I really do like using the system that I configured for myself. I think that I can finally settle down with my OS choice and setup and stop moving around for now, and I'll put my distrohopping adventures to a pause for now.

## The future with distrohopping
While I said that I found a good stable place to stop exploring new distros, I do have a few more in mind. One that I really do want to try, but not know if I want to go through the trouble again is Artix Linux. Artix is just the Arch Linux distro, but with the systemd init system ripped out and replaced with alternative systems, such as OpenRC, runit, and s6. The reason that Artix was created was due to a group of Arch users disliking the idea of using systemd for reasons that are beyond the scope of this blogpost. As I have only used distros that have used systemd, I am somewhat curious as to how Artix does things differently, and how different the setup process is with these alternative init systems. 

But until I do get bored of Arch, which I don't think I will for a while, or unles I sense that my OS is getting bloated, I think I'm sticking with my current setup. Maybe a bit of configuration changes, or a exploration of window managers, but I'm happy for now. For the first time in a while in the Linux world that is.

I am planning to put my dotfiles and configs on a GitHub repository for myself and others (idk who would want to use it but), so look out for that.
