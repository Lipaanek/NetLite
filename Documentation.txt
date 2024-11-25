# NetLite Framework

A lightweight and flexible event and buffer management framework for Roblox Studio.

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [API Reference](#api-reference)
  - [NetLite.New](#netlitenew)
  - [NetLite:CreateEvent](#netlitecreateevent)
  - [NetLite:RemoveEvent](#netliteremoveevent)
  - [NetLite:FireEvent](#netlitefireevent)
  - [NetLite:FireAllEvents](#netlitefireallevents)
  - [NetLite:AddBuffer](#netliteaddbuffer)
  - [NetLite:EditBuffer](#netliteeditbuffer)
  - [NetLite:BufferException](#netlitebufferexception)
- [Usage Examples](#usage-examples)
- [License](#license)

---

## Introduction

NetLite is a simple yet powerful framework designed for Roblox Studio, providing essential tools for managing events and buffers efficiently.

---

## Features

- **Event Management**: Create, fire, and remove events with ease.
- **Buffer Handling**: Add and edit buffers for data management.
- **Rate Limiting**: Enforce rate limits on events.
- **Priority System**: Handle events based on priority levels.

---

## Installation

Copy the NetLite module script into your project and include the required dependencies (`Types`, `BufferFormating`, etc.).

---

## API Reference

### `NetLite.New`

Creates a new instance of the NetLite framework.

```lua
local framework = NetLite.New()
