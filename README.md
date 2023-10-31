# Gelato Raas Account Abstraction

This repo contains the approach to Account Abstraction (AA) on Gelato Raas. 
For the time being we have deployed one solution for AA using web3Auth, Safe and Gelato Relay. However, moving forward we will add other solutions.  

[![Video Walkthrough](https://img.youtube.com/vi/2_orD-Z5uW4/0.jpg)](https://youtu.be/2_orD-Z5uW4)


## Web3Auth / Safe / Gelato Relay

<img src="docs/aa-flow.png" width="400">

### SDKs
---
Following SDKs are required
| Package| SDK |
| --- | ----------- |
| web3Auth | @web3auth/modal |
| Safe AA | zkatana-gelato-account-abstraction-kit|
| Safe AA | @safe-global/safe-core-sdk-types|
| Safe Relay | zkatana-gelato-relay-kit|

The packages `zkatana-gelato-account-abstraction-kit`, `zkatana-gelato-relay-kit` implement under the hood the custom packages `zkatana-gelato-protocol-kit` and ` zkatana-gelato-safe-deployments`

We have prepared two starter kits to get up and running. One with a React UI implementation and the second with a backend implementation  


## AA UI Starter Kit  
 A project showcasing a React implementation of how to use web3Auth with Safe and Gelato on Gelato Raas.

 [https://raas-ui-starter.web.app/](https://raas-ui-starter.web.app/)

  <img src="docs/ui.png" width="500"/>

Please visit the [UI Starter Kit repo](https://github.com/gelatodigital/gelato-raas-aa-ui-starter)


## zKatana Starter Kit
In this project we showcase how to implement Account Abstraction and gasless transactions with Safe and help to get started with zKatana.
Please visit the [zKatana Starter Kit](https://github.com/gelatodigital/astar-zkatana-starter-kit)


## Ressources
[web3Auth docs](https://web3auth.io/docs)  
[Safe docs](https://docs.safe.global/getting-started/readme)  
[Gelato Relay docs](https://docs.gelato.network/developer-services/relay)  

[zkatana-gelato-protocol-kit](https://www.npmjs.com/package/zkatana-gelato-protocol-kit)  
[zkatana-gelato-account-abstraction-kit](https://www.npmjs.com/package/zkatana-gelato-account-abstraction-kit)  
[zkatana-gelato-relay-kit](https://www.npmjs.com/package/zkatana-gelato-relay-kit)  
