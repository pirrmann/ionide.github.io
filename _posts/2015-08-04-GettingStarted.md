---
title: "Getting Started"
bg: purple
color: white
style: left
fa-icon: plug
---

# Getting Started

F# 4.0 needs to be installed on your system in order to use Ionide

For more detailed instructions on installing F# :

* [Installing F# on Linux](http://fsharp.org/use/linux/)
* [Installing F# on OSX](http://fsharp.org/use/mac/)
* [Installing F# on Windows](http://fsharp.org/use/windows/)


**FSC** _(F# Compiler)_ and **FSI/fsharpi** on Mono _(F# Interactive)_ need to be added to your system **PATH**.
The default location on 64-bit Windows is `C:\Program Files (x86)\Microsoft SDKs\F#\4.0\Framework\v4.0\`,
on 32-bit Windows is `C:\Program Files\Microsoft SDKs\F#\4.0\Framework\v4.0`.

## Quick Install Guide

### Windows

[You can download F# 4.0 here for Windows](https://www.microsoft.com/en-us/download/details.aspx?id=48179)

If you use [chocolatey](https://chocolatey.org/), you can install all the pre-requisites easily:

```batch
choco install windows-sdk-8.0 -y
choco install visualfsharptools -y
choco install microsoft-build-tools --version 14.0.25420.1 -y
:: for vscode
choco install visualstudiocode -y
:: for atom
choco install atom -y
```

## VS Code

Ionide plugins for VS Code can be installed using new [VS Code extension gallery](https://marketplace.visualstudio.com/#VSCode) - [Ionide-fsharp](https://marketplace.visualstudio.com/items/Ionide.Ionide-fsharp) is one of the featured extensions there, and there are also individual plugins for [Paket](https://marketplace.visualstudio.com/items/Ionide.Ionide-Paket) and [FAKE](https://marketplace.visualstudio.com/items/Ionide.Ionide-FAKE).

If you're interested in how Ionide functions within VS Code, checkout the [VS Code Getting Started Documentation](https://code.visualstudio.com/Docs)


## Atom

The easiest way to get Ionide is via the Atom package manager. In Atom, open the **Settings** pane and navigate to the **Install** tab. There, you can search for *ionide-installer* package and click **Install** button to install it.

Alternatively, if you are more comfortable using the command line, you can install it using *apm*:

~~~
apm install ionide-installer
~~~

The first time you start Atom after installing the *ionide-installer* package, you will have to wait a few seconds for the installer to determine which Ionide packages it needs to install.

If you're interested in how Ionide functions within Atom, checkout the [Atom Getting Started Documentation](https://atom.io/docs)
