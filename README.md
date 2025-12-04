# MoPER
The **Mobile PiPER (MoPER)** is a modularized, holonomic robot designed specifically for indoor Embodied-AI tasks. It offers a versatile platform with multiple configurations to suit various research needs:
* **Mobile Base:** 4-DOF holonomic movement.
* **Single PiPER:** Mobile base + single arm (11-DOF).
* **Dual PiPER:** Mobile base + dual arms (18-DOF).
<p align="center">
  <img src="images/MoPER-demo-pic-2-clean.jpg" height="400">
  <img src="images/moper_v1_side_crop.jpg" height="400">
</p>


## Design & Extensibility
The MoPER robot features a spacious, multi-tiered design comprising four key sections:
1.  **Mobile Base**
2.  **Sensor Floor**
3.  **Extendable Floor**
4.  **Manipulation Floor**

This modular architecture ensures there are no strict space limitations when adjusting or adding hardware. This makes MoPER highly suitable for tasks such as **teleoperation**, **data collection**, and **model evaluation**.

> **Note:** For specific teleoperation setups, please refer to the [PieMoPER](https://github.com/shentan-shiina/piemoper) repository.

<p align="center">
  <img src="images/demo_open_drawer_pick_bottle_v1.gif" height="400" alt="MoPER Demo GIF">
</p>

## Assets
We currently provide the following model formats for MoPER:

| Format   | Scope                                                       |
| :------- | :---------------------------------------------------------- |
| **STL**  | Model files for all assembly parts.                    |
| **URDF** | Available for Mobile Base, Single Arm, and Dual Arm setups. |
| **USD**  | Available for the Single Arm setup.                         |


<p align="center">
  <img src="images/moper_sw_render_1.jpg" height="400">
  <img src="images/MoPER_dual_bullet.png" height="400">
  <img src="images/MoPER_isaacsim.png" height="400">
</p>

## Miscellanous
1. **Adjustable Height:** We leverage 3 electric push rods for the extendable floor, allowing for dynamic height and space adjustment.
2. **Assembly:** For detailed assembly instructions, please contact us directly.
3. ...
