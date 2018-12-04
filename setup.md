---
title: Setup
---

Instructions for
[Windows](#windows),
[macOS](#macos)
and
[Linux](#linux)
are available below.
Please,
also download [Documents.zip]({{ page.root }}{% link files/Documents.zip %}).


# Windows
{:. #windows}

Download the [Cygwin installer](https://www.cygwin.com/)
and run the installer.
On the "Choosing Packages" step,
include

- sed
- gawk
- make

![Cygwin Installer during "Choosing Packages" step.](../fig/windows-cygwin-install-packages.png)

To select one package for installation,
click on the respective "Skip" in the "New" column.

# macOS
{:. #macos}

The default shell in all versions of macOS is Bash,
so no need to install it.
You access Bash from the Terminal (found in `/Applications/Utilities`).

To install sed, awk and make, you can use [Homebrew](https://brew.sh/).
From the terminal,
run

```
$ brew install gnu-sed gawk make
```

# Linux
{:. #linux}

The default shell is usually Bash,
so no need to install it.
If your machine is set up differently you can run it by opening a terminal and typing `bash`.

Install sed, awk and make using the package manager provided by your distribution.
Instructions for Debian and Red Hat/CentOS/Fedora are provided below.

## Debian-based Distributions

From the terminal,
run

```
$ sudo apt-get install sed gawk make
```

## Red Hat-based Distributions

From the terminal,
run

```
$ sudo dnf install sed gawk make
```

{% include links.md %}
