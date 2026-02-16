# Dream Villa VR Experience

## Overview
Dream Villa VR Experience is a web-based virtual reality project built using **A-Frame**, designed to simulate a modern residential villa that users can explore in a browser or VR headset. The project focuses on realistic architectural visualization, intuitive navigation, and immersive interaction through WebXR technologies.

The environment includes a furnished modern house, outdoor landscaping, animated swimming pool, vehicles, and lighting designed to create a believable virtual home experience.

---

## Project Goals
The main objectives of this project were:

- Create a realistic modern villa inspired by a real architectural reference.
- Provide at least three fully decorated rooms (living room, bedroom, kitchen).
- Add environmental elements such as trees, vehicles, and a swimming pool.
- Implement smooth navigation for desktop and VR users.
- Optimize performance for browser-based rendering.

---

## Technologies Used

### A-Frame
The project is built with **A-Frame**, a web framework for creating 3D, AR, and VR experiences using HTML and an entity-component architecture. A-Frame simplifies WebXR development by handling rendering, device compatibility, and scene setup automatically. :contentReference[oaicite:0]{index=0}

### Entity-Component System (ECS)
A-Frame uses an ECS architecture, allowing objects to be composed of reusable components, making the scene modular and scalable. :contentReference[oaicite:1]{index=1}

### glTF Models
3D assets are loaded using the `gltf-model` component. glTF was selected because it supports modern materials, animation, hierarchical objects, and efficient web delivery. :contentReference[oaicite:2]{index=2}

### Environment Component
The environment system provides background scenery and ground presets to quickly create realistic outdoor areas while keeping performance efficient. :contentReference[oaicite:3]{index=3}

### Physics System
The project uses an A-Frame physics extension for object interactions, collisions, and physical behavior. :contentReference[oaicite:4]{index=4}

---

## Features

### 🏠 Modern Villa Design
- Realistic villa layout based on architectural references.
- Exterior compound with driveway and landscaping.
- Multiple rooms designed for natural movement.

### 🛋️ Furnished Interior
- Living room with decor and furniture.
- Bedroom with modern arrangement.
- Kitchen with appliances and layout for realism.

### 🌊 Animated Swimming Pool
- Water animation for visual realism.
- Positioned outside the villa to enhance environment appeal.

### 🚗 Outdoor Details
- Cars parked inside the compound.
- Trees and plants surrounding the property.
- Large ground area for free movement.

### 💡 Lighting System
- Ambient lighting for natural brightness.
- Directional lighting for sun simulation.
- Point lights for interior highlights.

### 🎮 Navigation & Controls
- WASD keyboard movement.
- Mouse look controls.
- VR controller and laser interaction support.

---

## Project Structure

