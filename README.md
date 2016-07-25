# trade-engine-docs
Documentation accompanying Trade Engine Solution

## Table of Contents

  - [Introduction](#introduction)
  - [Overview](#overview)
  - [Architecture](#architecture)
  - [Demo](#demo)

![docs-diagram](https://cloud.githubusercontent.com/assets/6519496/17114781/5b4eabf4-52a8-11e6-9c2c-65646679ad30.png)

## Introduction

This Trade Engine is a simulation of a Currency exchange platform created as part of the hiring process with Currency Fair. 
Trades are submitted, processed, matched and the resulting statistics are rendered in the UI on the front-end.
This is a ficticious plaform encorporating a simple processing engine, a simple matching engine, and a GEO locating reporting front end. 
No Authentication is requred to use this platform.

## Overview

The goal of this project is to showcase a microservice architecture based on Java and Spring Boot.

## Architecture
Three components make up this microservice archtecture.
- https://github.com/sligokid/trade-engine-api
- https://github.com/sligokid/trade-engine-pub
- https://github.com/sligokid/trade-engine-web

Data flows API -> PUB -> Web

##Demo

POST trades to this endpoint:

http://ec2-52-16-13-114.eu-west-1.compute.amazonaws.com:8102/api/trade

See https://github.com/sligokid/trade-engine-api for more details


Visit the Web UI for corresponding statistics:

http://ec2-52-16-13-114.eu-west-1.compute.amazonaws.com:8100/

<img width="1375" alt="preview-web" src="https://cloud.githubusercontent.com/assets/6519496/17103716/9b9b08b4-5277-11e6-8cd3-5279b9f5ee02.png" style="max-width:100%;">

