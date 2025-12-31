# ROii3 - Autonomous Vehicle Simulator

High-performance WebGL-based autonomous vehicle simulator with TSN network visualization.

## Features

- **Classic Analog Speedometer**: Retro-style gauge with needle animation
- **Acceleration Graph**: Real-time acceleration visualization
- **TSN Network Visualization**: Zone controllers, HPC, sensors with data flow
- **Optimized Performance**: 60 FPS target with frame rate limiting
- **Infinite Road**: Endless driving environment

## Controls

| Key | Action |
|-----|--------|
| W | Forward |
| S | Reverse |
| A/D | Steer Left/Right |
| Space | Brake |
| V | Change Camera View |

## Network Components

- **ACU_IT HPC**: Central high-performance computer
- **3x LAN9692**: Zone controllers (Front-L, Front-R, Rear)
- **17 Sensors**: LiDAR, Camera, Radar

## Demo

https://hwkim3330.github.io/roii3/

## Tech Stack

- Three.js
- WebGL
- HTML5 Canvas (speedometer)
