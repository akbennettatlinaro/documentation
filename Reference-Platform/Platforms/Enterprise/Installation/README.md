# Installation

This page offers generic installation instructions for the Enterprise Reference Platform on supported hardware. A list of approved hardware can be found in the ["Approved Hardware"](../Hardware/README.md) section of this documentation set.

Be sure to check out the [Release Notes](../ReleaseNotes.md) before installing.

***

## Step 1: Upgrade firmware to latest version

<table align="center">
<tr>
    <th>UEFI/EDK2</td>
    <td align="center"><a href="http://releases.linaro.org/reference-platform/enterprise/firmware/">Download</a><br>Get the latest pre-built firmware images</td>
    <td align="center"><a href="Firmware/Build.md">Build</a><br>Instructions for building latest firmware images</td>
    <td align="center"><a href="Firmware/Install.md">Install</a><br>Instructions on how to install firmware</td>
    <td align="center"><a href="Firmware/README.md">Read more</a><br>Learn more about UEFI/EDK2</td>
</tr>
</table>

***

## Step 2: Set up PXE on your network

<table align="center">
<tr>
    <th>Centos</td>
    <td> https://wiki.centos.org/HowTos/NetworkInstallServer</td>
</tr>
<tr>
    <th>Debian</td>
    <td>https://wiki.debian.org/PXEBootInstall</td>
</tr>
</table>

***

## Step 3: Use a PXE to boot a network installer

Choose your network installer, download or build, and proceed to the installation instructions

**Network Installers:**
  
<table>
<tr>
    <th>Centos</td>
    <td><a href="http://releases.linaro.org/reference-platform/enterprise/installers/centos/16.06/">Download</a></td>
    <td><a href="Centos/README.md">Install</a></td>
</tr>
<tr>
    <th>Debian Jessie</td>
    <td><a href="http://releases.linaro.org/reference-platform/enterprise/installers/debian/16.06/">Download</a></td>
    <td><a href="Debian/README.md">Install</a></td>
</tr>
</table>

***
