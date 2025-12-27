<p align="center">
	<h1 align="center">Personal Linux Kernel</h1>
</p>

<p align="center">
This work is published under the terms of <a href="LICENSE"><b>MIT license</b></a>
</p>

## Description
This is my personal Linux kernel configuration based on [Linux Hardened](https://github.com/anthraxx/linux-hardened).

Linux Hardened is a modification of the Linux kernel with the aim of increasing kernel security and reducing the attack surface. This modification prioritizes security over performance.

The changes mainly consist of:
- Disabled support for INTEL PROCESSORS
- Enabled compilation specific to the processor architecture (--march=native)
- Removed functions and device support that are obsolete or would only be used in very specific cases

## Usage
This configuration is made for the Arch Linux compilation tool.

``` bash
makepkg -s
```

## Got any suggestions?
If you find any errors or have any new ideas for improving this repository, feel free to open an Issue or Pull Request, or contact me at my email address: nora@defitero.com
