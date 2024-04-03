<!-- markdownlint-configure-file { "MD004": { "style": "consistent" } } -->
<!-- markdownlint-disable MD033 -->
#

<p align="center">
    <a href="https://pi-hole.net/#gh-light-mode-only">
        <img src="https://github.com/pi-hole/graphics/blob/master/Vortex/Vortex_Vertical_wordmark_lightmode.png?raw=true)" alt="Pi-hole">
    </a>
        <a href="https://pi-hole.net/#gh-dark-mode-only">
        <img src="https://github.com/pi-hole/graphics/blob/master/Vortex/Vortex_Vertical_wordmark_darkmode.png?raw=true" alt="Pi-hole">
    </a>
    <br>
    <strong>Network-wide ad blocking via your own Linux hardware</strong>
</p>
<!-- markdownlint-enable MD033 -->

The Pi-hole® is a [DNS sinkhole](https://en.wikipedia.org/wiki/DNS_Sinkhole) that protects your devices from unwanted content without installing any client-side software.

  **Alpine version: x86, x86_64, armv7l and aarch64**: This repository provides an automated script to install Pi-hole on Alpine Linux (32-bit and 64-bit) working with musl.
   The 32-bit version for Alpine compiles the [Faster-than-light Engine](https://github.com/pi-hole/ftl).
   More information is available at the original Gitlab of the project [repository](https://gitlab.com/yvelon/pihole-FTL-alpine).

   **Information about Pi-hole**: please check out the [Pi-hole official repository](https://github.com/pi-hole/pi-hole).

   **Original code source can be found at the user yvelon Gitlab [here](https://gitlab.com/yvelon/pi-hole)!**

-----
## Important note

This script runs exclusively on Alpine Linux.
If you wish to install Pi-hole on another distribution, please refer to [Pi-hole's official installation](https://github.com/pi-hole/pi-hole)

## Installing on Alpine Linux

1. Before running, install `bash` and `git`.
2. Enable the _edge_ _community_ repository by editing `/etc/apk/repositories`
`nano /etc/apk/repositories`
http://dl-cdn.alpinelinux.org/alpine/edge/main

4. Clone the current repository
`git clone https://github.com/rcosta-uk/alpine-pi-hole`
5. `cd` to the cloned folder
6. Execute the script `bash automated\ install/basic-install.sh`
7. During installation, the user is prompted to select whether to download a precompiled binary or compile it locally.
    Local compilation may be slow on some devices.
    Only select downloading precompiled binaries if you trust this repository.
    In that case, be sure to select `yes` when prompted because the default action implies local compilation.

## Donations
If you found this project useful and wish to donate, you can use the following links:

<a href='https://ko-fi.com/rcostauk' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='ko-fi.com' /></a>

Bitcoin: <code>bc1qhh0qjrva9f6x4wywmt87a974c6quvs8s5vzack</code>


