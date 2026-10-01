# 🔬 SONOFRAME: An Acoustic Emission Prognosticator System

**Bantayan I Entry for the Science Innovation Project Expo 2026**  
**Innovators:** Kristine Mae N. Cordova, Chris Apple Joy D. Nepangue, John Paul P. Villaceran  
**Research Coach:** Mr. Christopher Rae B. Gigantana  
**Institution:** Bantayan Science High School (Ticad, Bantayan, Cebu)  

---

## 📝 Project Abstract
SONOFRAME is a low-cost, portable, and standalone structural health monitoring system that integrates passive acoustic-emission sensing with active piezoelectric inspection to detect, classify, and localize hidden mesoscale defects in engineering material systems. Developed as an alternative to expensive industrial monitoring systems, the device utilizes an ESP32-S3 microcontroller coupled with a high-attenuation PZT ceramic disc array to detect subsurface structural degradation (such as barely visible impact damage, deep cracks, and wide cracks) before it compromises structural integrity. Experimental validations on Palochina timber specimens demonstrate a 88–100% classification accuracy, significantly outperforming conventional visual inspections.

---

## 🛠️ System Enclosures & 3D Interactive Models
The prototype architecture utilizes a modular, 3D-printed PLA/PETG shell layout to isolate specific hardware signal layers and preserve mechanical coupling performance. 

Use the directory below to view, rotate, and interact with the custom CAD modules directly in your web browser:

| Component Module | 3D Interactive Link | Engineering Function & Design Context |
| :--- | :--- | :--- |
| **SONO TX-BODY** | [🔗 Open 3D Viewer](./SONO%20TX-BODY.stl) | Lower main chassis housing for the transmitter node electronics. |
| **SONO TX-LID** | [🔗 Open 3D Viewer](./SONO%20TX%20-LID.stl) | Top protective enclosure lid for the transmitter node, complete with clear deburred branding reliefs. |
| **SONO RX-BODY** | [🔗 Open 3D Viewer](./SONO%20RX-BODY.stl) | Main sensor node housing block designed to channel discrete shielded sensor lines. |
| **SONO RX-LID** | [🔗 Open 3D Viewer](./SONO%20RX-LID.stl) | Upper cover shell layout designed to form a snug friction seal with the receiver body. |
| **MAIN PROCESSING BOX** | [🔗 Open 3D Viewer](./SONOFRAME%20BODY-MAIN%20PROCESSING%20BOX.stl) | Central motherboard box (SF-01) with dedicated standoffs for the ESP32-S3, INA226 module, and dual OLED arrays. |
| **PROCESSING BOX LID** | [🔗 Open 3D Viewer](./SONOFRAME%20LID-MAIN%20PROCESSING%20BOX.stl) | Top operator interface plate showcasing portrait cutouts for the dual OLED window, joystick caps, and status LEDs. |

---

## 📐 Manufacturing & Print Specifications
All structural components are configured with robust, field-ready slicing patterns optimized to suppress structural resonance within the enclosures during sweep emissions:
* **Material:** Gray PLA or PETG filament (chosen for high structural stability)
* **Layer Resolution:** 0.2 mm layer height with 4 solid top/bottom shell layers
* **Perimeters:** 3 perimeter wall perimeters minimum
* **Infill Density:** 20% Gyroid pattern infill (optimized to resist mechanical torsion during clamp setups)
* **Fastener Tolerances:** Sized for M2 × 8 mm machine screws matching internal pilot bosses fitted with M2 brass threaded heat-set inserts (3.2 mm OD × 3.5 mm length).

---
*💡 Note: For the optimal viewing experience on mobile devices, please allow a brief moment for your browser's WebGL graphics engine to render the structural mesh geometry after selecting a 3D link.*
