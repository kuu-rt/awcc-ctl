# awcc-ctl

VERY minimalistic control script for the alienware-wmi driver.

```
Usage:
	awcc-ctl list-profiles
	awcc-ctl manual-fan-control
	awcc-ctl get-profile
	awcc-ctl set-profile <profile>
	awcc-ctl get-boost
	awcc-ctl set-boost <value>
	awcc-ctl [-h | --help]
```

## Requirements

* Kernel: *for-next* branch of the [platform-drivers-x86](https://git.kernel.org/pub/scm/linux/kernel/git/pdx86/platform-drivers-x86.git) tree
* Patchset: [platform/x86: alienware-wmi-wmax: HWMON support + DebugFS + Improvements](https://patchwork.kernel.org/project/platform-driver-x86/cover/20250305-hwm-v3-0-395e7a1407e2@gmail.com/)

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
