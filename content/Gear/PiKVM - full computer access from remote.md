If you have a PC somewhere remotely connected to the internet you can easily control via tools like RDP, Anydesk, Chrome Desktop etc. But that only works if the PC runs properly. If it doesn't boot for some reason, you need a KVM (Keyboard, Video, Mouse). A [KVM](https://en.wikipedia.org/wiki/KVM_switch) works like you had a display and a keyboard connected to it, so you can even install a new OS from remote.

The PiKVm makes use of a Raspberry PI, in this case a PI 4 B. I had two PIs laying around so I only had top order this [PiKVM-Kit](https://www.amazon.de/dp/B0B5QVFYMB) to get going. You connect the target via HDMI (for video) and USB (for keyboard, mouse and audio) and there is even a connector to an ATX PSU in case the target is a desktop PC.
The kit is a clone that works with the [original software](https://pikvm.org/) which is simply amazing. Next time I will order with PiKVM to support the project.

I got it for my [[Remote Telescope Hosting in Spain]] to be able to control my astrophotography PC in case of problems.  Really great is the option to install [Tailscale-VPN](https://tailscale.com/) on it, so you can control it even if it's in a NAT.

This thing works like a charm!

## BIOS-Setup remotely controlled
![[Screenshot 2025-05-21 202954.png]]

## The kit
![[6-IMG_3006.jpg]]
![[5-IMG_3007.jpg]]
![[1-IMG_3015.jpg]]