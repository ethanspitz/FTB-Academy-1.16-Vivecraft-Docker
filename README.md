# FTB-Academy-1.16-Vivecraft-Docker

FTB Academy 1.16 Docker Image

Based on the docker image from Jonas Bonno: https://github.com/JonasBonno/docker-ftb-revelation See it for information on using it.

Updated to use Amazon Corretto 8 and some minor tweaks to support it instead of the openjdk 8 image. Using 8u312 as FTB-Academy seems to suffer from the following bug: https://github.com/McModLauncher/modlauncher/issues/91

Includes Log4j patch for Minecraft server.

Also includes Vivecraft mod for VR support.