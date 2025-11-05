```markdown
# 🚀 Gravitational Slingshot Simulation

This project is a **PyScript/pygame-based simulation** of the *gravitational slingshot effect* (gravity assist maneuver).  
It demonstrates how a spacecraft's trajectory can be altered by planetary gravity, a technique widely used in space exploration.

---

## 🎯 Enhanced Features

### 🪐 **Multi-Planet System**
- **Single or dual planet configurations** - Choose between 1 or 2 planets
- **Realistic planetary images** - Jupiter and Mars with proper scaling
- **Dynamic planet sizing** - Planet size scales logarithmically with mass

### 🎮 **Interactive Controls & UI**
- **Start menu** with clean interface
- **Interactive instructions** panel
- **Real-time parameter adjustment**:
  - Gravitational constant **G**
  - Planet masses (base + exponent notation)
  - Ship mass
  - Number of planets (1 or 2)

### 🚀 **Enhanced Ship Mechanics**
- **Click-to-place** ship positioning
- **Drag-to-launch** velocity control with visual preview
- **Real-time velocity display** near each ship
- **Dynamic trails** showing ship trajectories
- **Collision detection** with planets

### 🌌 **Visual Improvements**
- **Space background** image
- **Planet-specific textures** (Jupiter and Mars)
- **Smooth animation** with proper time stepping
- **Trail effects** with length limiting
- **Center of mass visualization**

### ⚙️ **Technical Features**
- **Proper scientific notation** input (base × 10^exponent)
- **Pixel-to-meter scaling** for accurate physics
- **Configurable time steps** for simulation stability
- **Mass-based planet sizing** for visual realism

---

## 🎮 How to Use

1. **Start**: Click "Start Simulation" from the main menu
2. **Configure**:
   - Set planet masses using base/exponent inputs
   - Choose 1 or 2 planets from dropdown
   - Adjust gravitational constant and ship mass
3. **Launch Ships**:
   - **First click**: Place ship (red dot appears)
   - **Mouse move**: Preview velocity (green line shows direction/magnitude)
   - **Second click**: Launch with calculated velocity
4. **Monitor**: Watch velocity values and trajectories in real-time
5. **Control**: Use "Reset Ships" to clear or "Restart Defaults" to reset all parameters

---

## 🔧 Parameter Guide

- **Planet Mass**: Enter as `base × 10^exponent` (e.g., `5.97 × 10^24` for Earth mass)
- **Ship Mass**: Typically `1 × 10^3` kg (1000 kg)
- **Gravitational Constant**: Default `6.67 × 10^-11` N·m²/kg²
- **Planet Count**: Toggle between single Jupiter or Jupiter+Mars system

---

## 🎯 Educational Value

This simulation demonstrates:
- **Gravitational assist maneuvers** used in real space missions
- **Orbital mechanics** and conservation laws
- **Multi-body gravitational interactions**
- **The effect of mass and distance on gravitational forces**

---


*Experience the fascinating dynamics of orbital mechanics through this interactive gravitational slingshot simulator!*
```
