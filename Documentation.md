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

• **Event Management**: Create, fire, and remove events with ease.
• **Buffer Handling**: Add and edit buffers for data management.
• **Rate Limiting**: Enforce rate limits on events.
• **Priority System**: Handle events based on priority levels.

---

## Installation

Copy the NetLite module script into your project and include the required dependencies (`Types`, `BufferFormating`, etc.).

---

## API Reference

### `NetLite.New`

Creates a new instance of the NetLite framework.

```lua
local framework = NetLite.New()
```
Returns a new `NetLite` instance.

### `NetLite:CreateEvent`

Registers a new event in the framework.

```lua
framework:CreateEvent(eventName, eventSettings, eventFunc)
```
#### Parameters:

• `eventName` (string): Name of the event.
• `eventSettings` (EventSettings): Event configuration, including priority and rate limits.
• `eventFunc` (function): Callback function for the event.

### `NetLite:RemoveEvent`

Removes an event from the framework.

```lua
framework:RemoveEvent(eventName)
```
#### Parameters:

• `eventName` (string): Name of the event to remove.


### `NetLite:FireEvent`

Triggers a specific event by its name.

```lua
local success, result = framework:FireEvent(eventName, ...)
```
#### Parameters:

• `eventName` (string): Name of the event.
• `...` (any): Arguments to pass to the event function.

#### Returns:

• `success` (boolean): Whether the event executed successfully.
• `result` (any): The result of the event function.

