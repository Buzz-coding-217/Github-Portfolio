---
layout: default
title: Shravel Sharma's Projects
---

Welcome to my portfolio!

This site showcases my key projects, covering areas such as **IoT**, **Edge Computing**, **Machine Learning**, **Cloud Platforms**, and **Web Development**.

# Featured Projects

## 🛒 Smart Shopping Store using IoT

A customer-centric embedded system that uses sensors and edge devices to:
- Detect items picked from shelves.
- Update cart and billing in real-time.
- Enhance in-store experience through automation.

_Stack: Raspberry Pi, Sensors, MQTT, Node.js_

## 🍄 IoT-Based Mushroom Growth Monitor

Developed a smart farming solution to monitor mushroom cultivation by tracking:
- Humidity, Temperature, and Light using sensors.
- Alerts and controls via edge dashboard.

_Stack: Raspberry Pi, HiveMQ, Python, Web Interface_

> "Making farming smarter through data-driven insights."

## 🧠 Energy-Aware Edge ML System

Worked on optimizing **machine learning inference on edge devices** while reducing power consumption using:
- Custom scheduling algorithms (Min-Min, Max-Min, MET, etc.)
- Performance vs Energy trade-off analysis on Raspberry Pi clusters

> "Bringing intelligence closer to data."

## 🚶 Crowd Monitoring with YOLOv5

Built a real-time crowd detection system:
- Customized YOLOv5 to detect only people.
- Defined zones to assess density and movement patterns.

_Image & video inputs analyzed at the edge._

## 🛍️ Fashion E-Commerce Platform

Currently developing a personalized platform with features like:
- Dynamic product filtering
- Smart recommendations
- Admin analytics dashboard

_Frontend: HTML/CSS/JS, Backend: Node.js, DB: MongoDB_

# Code Snippet

```js
// Connecting an IoT device with MQTT broker
const mqtt = require("mqtt");
const client = mqtt.connect("mqtt://broker.hivemq.com");

client.on("connect", () => {
  client.subscribe("mushroom/growth");
  console.log("Connected & Subscribed");
});
