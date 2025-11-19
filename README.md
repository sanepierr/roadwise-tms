# Roadwise-TMS: AI-Based Smart Traffic Management System with Cyclist Priority

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![React](https://img.shields.io/badge/React-18.0%2B-blue)
![Node.js](https://img.shields.io/badge/Node.js-16.0%2B-green)

## Overview

Roadwise-TMS is an AI-powered traffic management system designed to address urban traffic challenges in Kampala, Uganda. The system integrates computer vision, IoT hardware, and web/mobile interfaces to prioritize cyclist safety and reduce traffic congestion.

**Key Innovation**: Introduces a **blue light phase** specifically for cyclists and motorcyclists to reduce junction collisions.

## Problem Statement

Kampala faces severe traffic issues:
- 25,107 crashes reported in 2024
- 5,000+ annual road deaths in Uganda
- 14 daily fatalities on Ugandan roads
- Motorcycle accidents account for over 40% of incidents

## Solution Features

### AI-Powered Detection
- Real-time vehicle and cyclist detection using YOLOv8
- ≥90% detection accuracy under varying conditions
- Adaptive to Kampala's urban environment

### Smart Traffic Control
- Arduino/NodeMCU-based four-phase traffic lights
- Blue light phase for cyclist/motorcyclist priority
- Round-robin logic with congestion-responsive timing
- Target: 20-30% reduction in collision risks

### Management Interfaces
- **Web Dashboard**: React-based with Tailwind CSS
- Real-time manual override for traffic officers
- <100ms response time for officer interventions
- **Mobile App**: React Native for officer monitoring

### Technical Stack