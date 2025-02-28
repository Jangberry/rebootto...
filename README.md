# Reboot to ...

> [!CAUTION]
> This fork is no longer maintained. It still works at the time of writing this warning, but be aware it could break anytime soon without fixes (I will, however, still look at PRs, but at this point you're probably better off forking this repo). If you're just choosing a bootloader, the extension [restart to](https://extensions.gnome.org/extension/7215/restart-to/) might be a great, still maintained, alternative.  
> Also take a look to [Reboot to UEFI](https://github.com/UbayGD/reboottouefi) as it might implement this someday.

This is a small Gnome extension that adds the ability to reboot directly to an entity of the boot-loader. This is a fork of the way better extentions [Reboot to UEFI](https://github.com/UbayGD/reboottouefi) by [UbayGD](https://github.com/UbayGD/). This will also add the UEFI entry to the menu, so you don't need both extensions.

This extension rely on the DBus interface `org.freedesktop.login1` to both discover entries and request the reboot.

![Screenshot of the extension options (Pop_OS, gnome 42.5)](images/Screenshot.png)

<br>

# Build the extension

To build the extension run the following command:

`$ sh build.sh`

If all goes well this will generate a zip file in the project folder.

# Install the extension

To install the extension just run the **install.sh** script with the following command:

`$ sh install.sh`

<hr>
<br>

# Notes

- This extension is available in [GNOME Extensions](https://extensions.gnome.org/extension/5913/rebootto/).
