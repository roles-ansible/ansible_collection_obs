 Ansible role to export LUFS from OBS Plugin via Websocket
==============================

This ansible role collects the LUFS values from the [Loudness OBS Plugin](https://obsproject.com/forum/resources/loudness-dock.1751/) via OBS-Studio Websocket as prometheus exporter.

Variables
---------

| Name | Value | Description |
| --- | --- | --- |
| ``lufs_exporter__user`` | ``lufs_exporter`` | Linux Username |
| ``lufs_exporter__group`` | ``lufs_exporter`` | Linux Gruppe |
| ``lufs_exporter__home`` | ``/var/lib/obs_lufs_exporter`` | Linux User Home |
| ``lufs_exporter__obsws`` | ``localhost:5544`` | Komma seperated list of obs websocket (with port) |
| ``lufs_exporter__obsws_passwd`` | | Optional Websocket Password |
| ``submodules_versioncheck`` | ``false`` | Optional simple versionscheck |

Licese: MIT
Author: L3D
