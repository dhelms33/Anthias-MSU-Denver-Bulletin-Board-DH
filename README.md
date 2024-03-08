# Anthias-MSU-Denver Bulletin Board - Senior Project

## About Our Anthias Fork

This repository is a modified version of the Anthias digital signage platform for Raspberry Pi. It is created as part of a senior project, where we aim to create a Real-Time Bulletin Board for MSU Denver faculty and other authorized users to post updates by adding our website into the Anthias application which supports instant updates and announcement capabilities. The key features of our fork will include:

- Faculty exclusive access
- Remote posting capability
- Real-time updates
- Dedicated Display
- Separate technical clearance

## Project Goals

Our senior project focuses on delivering bulletin board functionality custom tailored to MSU Denver faculty, enabling users to share information in real-time and separate access for technical access. The added features cater to the specific needs of faculty members, allowing for exclusive access and remote posting capabilities.

## Getting Started

To use our modified version of Anthias, you can follow the installation instructions provided below.

### Balena disk images

The quickest way to get started is to use [Raspberry Pi Imager](https://www.screenly.io/blog/2022/12/13/anthias-and-screenly-now-in-rpi-imager/), where you can find Anthias under `Other specific-purpose OS`. Alternatively, you can find our pre-built disk images (powered by [Balena Hub](https://hub.balena.io/)) [here](https://github.com/YourOrganization/Anthias/releases/latest/).

Please be aware that our fork is a work in progress, and some bugs may still exist. Track the known issues [here](https://github.com/MSU-Denver-Bulletin-Board/Anthias-MSU-Denver-Bulletin-Board). Engage in discussions and seek support in the [Anthias forums](https://forums.screenly.io).

### Important note for installing on a VM

We were not able to successfully run Anthias on a VM. We attempted to try this on Windows 10 and Windows 11 using VMbox on a Debian OS. We were able to install the Anthias software, but we were not able to access the web interface. 

We were also not able to access the web interface on the Raspberry Pi OS Lite. We would recommend using the Raspberry Pi OS with the desktop environment for the best results and using ethernet to connect the Raspberry Pi to the network.

### Installing on Raspberry Pi OS Lite

To install on [Raspberry Pi OS](https://www.raspberrypi.com/software/) Bullseye Lite, run the following command:

```bash
$ bash <(curl -sL https://install-anthias.srly.io)

Follow the prompts during the installation, and reboot as instructed.

**Note**: This installation may take 15 minutes to several hours, depending on hardware specifications and internet speed.

**Note**: If you are using WIFI to connect to the internet, you will need to connect to the internet via Ethernet to complete the installation.

TODO: Correct the above **Note** for installing on Raspberry Pi OS Lite once completed.

## Installing with Balena

Follow the steps in [this documentation](/docs/balena-fleet-deployment.md) to deploy the MSU-Denver Bulletin Board on your Balena fleet with our modifications.

## Quick Links

- [Forum](https://forums.screenly.io/)
- [Website](https://anthias.screenly.io) (hosted on GitHub, source [here](https://github.com/YourOrganization/Anthias/tree/master/website))
- [General documentation](https://github.com/YourOrganization/Anthias/blob/master/docs/README.md)
- [Developer documentation](https://github.com/YourOrganization/Anthias/blob/master/docs/developer-documentation.md)

We appreciate your interest and support. 
