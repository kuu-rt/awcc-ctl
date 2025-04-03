# awcc-ctl

VERY minimalistic control script for the alienware-wmi driver.

```
Usage:
	awcc-ctl list-profiles
	awcc-ctl get-profile
	awcc-ctl set-profile <profile>
	awcc-ctl get-boost
	awcc-ctl set-boost <value>
	awcc-ctl [-h | --help]
```

## Requirements

* Kernel v6.15-rc1 or later (Latest commmit of [Linux](https://github.com/torvalds/linux))
* Patchset: [platform/x86: alienware-wmi-wmax: HWMON support + DebugFS + Improvements](https://patchwork.kernel.org/project/platform-driver-x86/patch/20250329-hwm-v7-0-a14ea39d8a94@gmail.com/)

## Instructions

To execute this script, do the following:

```
git clone https://github.com/kuu-rt/awcc-ctl
cd awcc-ctl
chmod +x awcc-ctl
./awcc-ctl
```

## Planned features (big maybe)

- Add a PKGBUILD for Arch users

## Contributions

If you'd like to make this script better, please make a PR :^)
