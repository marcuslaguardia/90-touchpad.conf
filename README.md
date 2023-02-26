# My touchpad

This is an X11 .conf file designed to better serve touchpad users.

## What does it do?

- Enables tap-to-click functionality;
- Allows you to use the middle mouse button when touching it with three fingers.

## Usage

Place the 90-touchpad.conf under the /etc/X11/xorg.conf.d/ directory (super user privileges are required)

```sh
sudo cp -r 90-touchpad.conf /etc/X11/xorg.conf.d/
```

Either reboot or log out to apply the changes.
