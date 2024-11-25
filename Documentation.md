# NetLite Framework

A lightweight and flexible event and buffer management framework for Roblox Studio.

---

## Table of Contents

• [Introduction](#introduction) </br>
• [Features](#features) </br>
• [Installation](#installation) </br>
• [API Reference](#api-reference) </br>
  &emsp;• [NetLite.New](#netlitenew) </br>
  &emsp;• [NetLite:CreateEvent](#netlitecreateevent) </br>
  &emsp;• [NetLite:RemoveEvent](#netliteremoveevent) </br>
  &emsp;• [NetLite:FireEvent](#netlitefireevent) </br>
  &emsp;• [NetLite:FireAllEvents](#netlitefireallevents) </br>
  &emsp;• [NetLite:AddBuffer](#netliteaddbuffer) </br>
  &emsp;• [NetLite:EditBuffer](#netliteeditbuffer) </br>
  &emsp;• [NetLite:BufferException](#netlitebufferexception) </br>
• [Usage Examples](#usage-examples) </br>
• [License](#license)

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
