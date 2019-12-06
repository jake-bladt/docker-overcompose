# docker-overcompose

## Overview

A proof-of-concept application meant to demonstrate a technique for Windows and Linux containers to play nicely together on a single Windows server

## Questions to answer

* How to automate docker-for-windows switch between targeting Windows and targeting Linux
* Is it possible to create an overlay network between Windows and its own WSL?
* Is it possible to create an overlay network between a Windows host and its own docker-machine VM?
* If not overlay, ipvlan or l2bridge?
* When adding a container to a network, is it possible to add a DNS name as well? (Subject: service discovery)
* Can docker-compose accept its launch document as a stream?

## Research

* [Working with Linux and Windows Containers simultaneously on Docker Desktop](https://markheath.net/post/docker-desktop-windows-and-linux)
