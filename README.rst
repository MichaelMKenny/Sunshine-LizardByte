Overview
========
LizardByte has the full documentation hosted on `Read the Docs <https://sunshinestream.readthedocs.io/>`_.

About
-----
Sunshine is a Game stream host for Moonlight.
Sunshine is a self hosted, low latency, cloud gaming solution with support for AMD, Intel, and Nvidia gpus.
It is an open source implementation of NVIDIA's GameStream, as used by the NVIDIA Shield.
Connect to Sunshine from any Moonlight client, available for nearly any device imaginable.

These are the advantages of Sunshine over GeForce Experience.

- FOSS (Free and Open Source Software)
- Multi-platform

  - Linux
  - macOS
  - Windows

- Pair over web ui
- Supports AMD, Intel, and Nvidia GPUs for encoding
- Supports software encoding
- Supports streaming to multiple clients
- Web UI for configuration

System Requirements
-------------------

.. warning:: This table is a work in progress. Do not purchase hardware based on this.

**Minimum Requirements**

+------------+------------------------------------------------------------+
| GPU        | Nvidia: NVENC enabled cards, see `nvenc support matrix`_.  |
|            +------------------------------------------------------------+
|            | AMD: VCE 1.0 or higher, see `obs-amd hardware support`_.   |
+------------+------------------------------------------------------------+
| CPU        | Intel: Core i3-2100 3.1 GHz or higher                      |
|            +------------------------------------------------------------+
|            | AMD: Athlon II X4 630 2.8 GHz or higher                    |
+------------+------------------------------------------------------------+
| RAM        | 4GB or more                                                |
+------------+------------------------------------------------------------+
| OS         | Windows: 10+ (Windows Server not supported)                |
|            +------------------------------------------------------------+
|            | macOS: 11.7+                                               |
|            +------------------------------------------------------------+
|            | Linux/Debian: 11 (bullseye)                                |
|            +------------------------------------------------------------+
|            | Linux/Fedora: 36+                                          |
|            +------------------------------------------------------------+
|            | Linux/Ubuntu: 20.04+ (focal)                               |
+------------+------------------------------------------------------------+
| Network    | Host: 5GHz, 802.11ac                                       |
|            +------------------------------------------------------------+
|            | Client: 5GHz, 802.11ac                                     |
+------------+------------------------------------------------------------+

**4k Suggestions**

+------------+------------------------------------------------------------+
| GPU        | Nvidia: GeForce GTX 1080 or higher.                        |
|            +------------------------------------------------------------+
|            | AMD: Video Coding Engine 3.1 or higher.                    |
+------------+------------------------------------------------------------+
| CPU        | Intel: Core i5 or higher.                                  |
|            +------------------------------------------------------------+
|            | AMD: Ryzen 5 or higher.                                    |
+------------+------------------------------------------------------------+
| Network    | Host: CAT5e ethernet or better.                            |
|            +------------------------------------------------------------+
|            | Client: CAT5e ethernet or better.                          |
+------------+------------------------------------------------------------+

**HDR Suggestions**

+------------+------------------------------------------------------------+
| GPU        | Nvidia: Pascal-based GPU (GTX 10-series) or higher.        |
|            +------------------------------------------------------------+
|            | AMD: Video Coding Engine 3.4 or higher.                    |
+------------+------------------------------------------------------------+
| CPU        | Intel: todo                                                |
|            +------------------------------------------------------------+
|            | AMD: todo                                                  |
+------------+------------------------------------------------------------+
| Network    | Host: CAT5e ethernet or better                             |
|            +------------------------------------------------------------+
|            | Client: CAT5e ethernet or better                           |
+------------+------------------------------------------------------------+

Integrations
------------

.. image:: https://img.shields.io/github/actions/workflow/status/lizardbyte/sunshine/CI.yml?branch=master&label=CI%20build&logo=github&style=for-the-badge
   :alt: GitHub Workflow Status (CI)
   :target: https://github.com/LizardByte/Sunshine/actions/workflows/CI.yml?query=branch%3Amaster

.. image:: https://img.shields.io/github/actions/workflow/status/lizardbyte/sunshine/localize.yml?branch=nightly&label=localize%20build&logo=github&style=for-the-badge
   :alt: GitHub Workflow Status (localize)
   :target: https://github.com/LizardByte/Sunshine/actions/workflows/localize.yml?query=branch%3Anightly

.. image:: https://img.shields.io/readthedocs/sunshinestream?label=Docs&style=for-the-badge&logo=readthedocs
   :alt: Read the Docs
   :target: http://sunshinestream.readthedocs.io/

.. image:: https://img.shields.io/badge/dynamic/json?color=blue&label=localized&style=for-the-badge&query=%24.progress..data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-15178612-503956.json&logo=crowdin
   :alt: CrowdIn
   :target: https://crowdin.com/project/sunshinestream

Support
---------

Our support methods are listed in our
`LizardByte Docs <https://lizardbyte.readthedocs.io/en/latest/about/support.html>`_.

Downloads
---------

.. image:: https://img.shields.io/github/downloads/lizardbyte/sunshine/total?style=for-the-badge&logo=github
   :alt: GitHub Releases
   :target: https://github.com/LizardByte/Sunshine/releases/latest

.. image:: https://img.shields.io/docker/pulls/lizardbyte/sunshine?style=for-the-badge&logo=docker
   :alt: Docker
   :target: https://hub.docker.com/r/lizardbyte/sunshine

Stats
------
.. image:: https://img.shields.io/github/stars/lizardbyte/sunshine?logo=github&style=for-the-badge
   :alt: GitHub stars
   :target: https://github.com/LizardByte/Sunshine

.. image:: https://img.shields.io/badge/dynamic/json?color=blue&label=AUR&style=for-the-badge&query=$.results.0.NumVotes&url=https%3A%2F%2Fapp.lizardbyte.dev%2Funo%2Faur%2Fsunshine.json&logo=archlinux
   :alt: AUR votes
   :target: https://aur.archlinux.org/packages/sunshine

.. _obs-amd hardware support: https://github.com/obsproject/obs-amd-encoder/wiki/Hardware-Support
.. _nvenc support matrix: https://developer.nvidia.com/video-encode-and-decode-gpu-support-matrix-new
