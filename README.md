# printi mini help page
![two dogs](img/doggoSmall.jpg)

don't panic!

## FAQ:

### Setup

I plugged in my brand new printi mini but nothing is happening!

> It will take up to **5 minutes** for the printi mini to start. When it does, it will print the printi logo and instructions for setting up Wi-Fi. Hold tight!

How do I **connect my printi to a Wi-Fi network**?

> [Open the settings page of your printi mini](/settings).

Can I **update** the firmware of my printi mini?

> Yes! The firmware will be updated automatically when the printi _boots_, so restart (switch off/on) your printi every now and then to get the latest features!

How do I **change the printi name**?

> [Open the settings page of your printi mini](/settings).

------

### Trouble

> In case of trouble, **try turning your printi off and on**.

🚨 What does a **flashing red LED** mean?

> You ran out of paper! Switch off your printi, lift the lid, and put in a new thermal paper roll: **width: 57mm, diameter: ≤60mm**. (They are sold at office supply stores.) Voilà!

My printi only prints blank paper!

> Make sure that you are using 58mm *thermal* receipt paper (does one side turn black quickly when you heat it?), and that the paper is not loaded in reverse.

My printi is **not receiving pictures**!

> Check that you are sending your pictures to the right address. For example, if your printer name is `apples`, you should go to `printi.me/apples` to send pictures. You can view or change your printer name using the [settings page](/settings). You could also try using a different printer name.

My printi doesn't do anything 😢

> Oh no! Remember that it might take up to five minutes for printi to boot and update. Is the [settings page](/settings) working? Feel free to [contact me](https://github.com/fonsp)!

------

### Misc

Can I protect my printi mini with a **password**?

> No, but you can make your printi nearly impossible to find by choosing a complex name. Every `printi.me/subdomain` page looks exactly the same, and uploads are handled identically, regardless of whether it connects to a printi or not. 

Are images sent to a printi mini **stored on a server**?

> Never on a hard drive; (processed) photos are only stored in memory, and will be deleted when printed, or after 7 days, whichever comes first. 

What happens to images sent to `printi.me`?

> That's secret!

Where can I buy more **printi minis**?!

> [Contact me](https://github.com/fonsp)!

Can I use the **USB port** and **ethernet port** at the back of my printi mini?

> The USB port should _not_ be used: the printer already has an internal USB connection. I am not yet sure about the ethernet port, but do send me an email when you figure it out!

How do I hack my printi mini?

> The SSH server of the embedded Onion Omega 2+ is likely disabled, but you can still change your software by opening your printi mini and taking out the Omega. You can access the terminal over the serial pins (or using the Onion Omega Dock). Please refer to the [client setup instructions](https://github.com/fonsp/printi/wiki/Installing-the-client) to see what commands are run at boot. For example, you could clear the /root/printi directory, and replace it with a clone of _your own fork_ of [the GitHub repository](https://github.com/fonsp/printi). It will then pull the latest version of your fork at boot, instead of the official client.

I don't want a printi mini anymore!

> Oh no! Bring your printi mini to any electronics store to **dispose of it properly**. If you want, you can open the printi mini (there are four screws, two of which are hidden beneath the rubber pads) and take out the Onion Omega 2+ (and leave the wires). After reassembly, you now have a regular receipt printer and a super cool computer.

_- [fons](https://github.com/fonsp)_

