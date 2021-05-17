---
permalink: /dev/
title: "Getting Started"
classes: single
---

MobiVM provides plugins for IntelliJ IDEA/Android Studio, Eclipse and Gradle. We provide both release and nightly snapshot builds.

## IntelliJ IDEA/Android Studio



To install the MobiVM plugin for IntelliJ IDEA or Android Studio you have two options:

### 1. Plugin Marketplace (Recommended)
Stable release plugin versions are available from the Jetbrains Plugin Marketplace:

1. Install Xcode on MacOS, open it once and agree to the license
2. Open IntelliJ IDEA/Android Studio, go to `Preferences -> Plugins -> Marketplace`
3. Type `MobiVM` on the search box and click `Install`

### 2. Manual Download

1. Install Xcode on MacOS, open it once and agree to the license
2. Download the MobiVM IntelliJ IDEA plugin Zip file:
    - [IntelliJ IDEA plugin **Snapshot** builds](/downloads.html?prefix=snapshots/idea)
    - [IntelliJ IDEA plugin **Release** builds](/downloads.html?prefix=releases/idea)
3. Open IntelliJ IDEA/Android Studio, go to `Preferences -> Plugins`
4. Click `Install plugin from disk...`
5. Select the Zip you downloaded and re-start IntelliJ IDEA/Android Studio

**WARNING:** Install the Zip file directly, don't uncompress it!
{: .notice--danger}

## Eclipse

To install the MobiVM plugin for Eclipse:

1. Install Xcode on MacOS, open it once and agree to the license
2. Open Eclipse, go to `Help -> Install New Software...`
3. Click `Add...` and enter the update URL from below
    - [Eclipse plugin **Snapshot** update URL]()
    - [Eclipse plugin **Release** update URL]()
4. Select `MobiVM for Eclipse` and finish the installation

## Gradle

To use the RoboVM plugin via Gradle, follow the [README in the repository](https://github.com/MobiDevelop/robovm/tree/master/plugins/gradle).

<br/>

# Documentation

- [Wiki](https://github.com/mobidevelop/robovm/wiki) (WIP).
- Legacy RoboVM [official documentation]()

<br/>

# Community
Ask questions or connect with like-minded people in:

- The official Gitter room [![Join the chat at https://gitter.im/MobiVM/robovm](https://badges.gitter.im/MobiVM/robovm.svg)](https://gitter.im/MobiVM/robovm?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
- GitHub [MobiVM Discussions](https://github.com/MobiVM/robovm/discussions)

<br/>

# Source Code & Contributing

Contribute with an issue or a PR on [GitHub](https://github.com/mobidevelop/robovm).

Contributions to the runtime code (Java class libraries, iOS bindings, native code, ...) must be licensed under [Apache 2](http://www.apache.org/licenses/LICENSE-2.0). Contributions to any other parts must be licensed under [GPLv3](http://www.gnu.org/licenses/quick-guide-gplv3.en.html).
