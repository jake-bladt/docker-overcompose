# docker-overcompose

## Overview

A proof-of-concept application meant to demonstrate a technique for Windows and Linux containers to play nicely together in Windows

## Questions to answer

* How to automate docker-for-windows switch between targeting Windows and targeting Linux
* Is it possible to create an overlay network between Windows and its own WSL?
* Is it possible to create an overlay network between a Windows host and its own docker-machine VM?
* If not overlay, ipvlan or l2bridge?
* Can docker-compose accept its launch document as a stream?
