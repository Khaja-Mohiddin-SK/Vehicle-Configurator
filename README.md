# Vehicle Configurator

Interactive real-time 3D vehicle configurator developed in Unreal Engine 5.

The project demonstrates Blueprint-based interactions, UI development, paint color switching, camera controls, lighting, and interactive vehicle components

## Opening the Project

This project uses Git LFS for Unreal Engine assets.

### Recommended

1. Install Git and Git LFS.
2. Run:

```bash
git lfs install
git clone https://github.com/Khaja-Mohiddin-SK/Vehicle-Configurator.git
cd Vehicle-Configurator
git lfs pull
```
3. Open VehicleConfigurator.uproject in Unreal Engine 5.

## Features

- Real-time vehicle paint color switching
- Animated left and right doors
- Headlight controls with emissive lighting
- Multiple vehicle inspection camera views
- UMG-based user interface
- Showroom environment and vehicle-focused lighting
- Vehicle asset adjustments using Blender
- Mesh separation and pivot correction for interactive components

## Technologies & Tools

- Unreal Engine 5
- Blueprints
- UMG
- Blender
- Unreal Material System
- Git LFS

## Project Overview

The project was created as an interactive automotive visualization application.

Imported 3D vehicle assets were organized and adjusted in Blender and Unreal Engine, including mesh separation, pivot correction, and component setup for interaction.

Blueprints are used to control user interactions such as vehicle color changes, door animations, headlights, and camera switching.

The user interface was created using Unreal Motion Graphics (UMG).

## Controls / Interaction

The UI allows the user to:

- Change the vehicle paint
- Open and close the left door
- Open and close the right door
- Turn headlights on and off
- Switch between different vehicle camera views

## Screenshots

The screenshots below demonstrate the current Vehicle Configurator, including the showroom environment, interactive controls, paint color switching, animated components, headlights, and multiple inspection views.

<table>
  <tr>
    <td align="center">
      <img src="screenshots/Front%20View.png" width="300"><br>
      <b>Front View</b>
    </td>
    <td align="center">
      <img src="screenshots/Front%20View%20-%20Interaction%20UI.png" width="300"><br>
      <b>Front View Interaction UI</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="screenshots/Right%20View%20-%20door%20%20interaction.png" width="300"><br>
      <b>Door Interaction</b>
    </td>
    <td align="center">
      <img src="screenshots/Headlights.png" width="300"><br>
      <b>Headlight</b>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="screenshots/Right%20View.png" width="300"><br>
      <b>Right View</b>
    </td>
    <td align="center">
      <img src="screenshots/Back%20View.png" width="300"><br>
      <b>Back View</b>
    </td>
  </tr>
</table>

## Asset Note

The vehicle model and selected environment assets used in this project are third-party assets. My work focused on Unreal Engine integration, Blueprint interactions, UI, material configuration, lighting, camera systems, and adjustments required for interactive components.

## Demo

Download the Windows build on itch.io:

https://khaja-mohiddin-sk.itch.io/vehicle-configurator
