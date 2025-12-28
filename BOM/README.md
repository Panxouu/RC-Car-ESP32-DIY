# RC-Car-ESP32-DIY - Bill of Materials 📦

*Author: Francisco Cáceres* ✍️

This document details the complete list of hardware, electronics, and 3D printed parts required to build the **RC-Car-ESP32-DIY**.

---

## English Version 🇺🇸

### 📋 1. Hardware & Electronics
Components mounted on the custom PCB.

| Component Name | Description / Specs | Qty | Notes |
| :--- | :--- | :---: | :--- |
| **Microcontroller** | ESP32 Dev Module (30/38 pin) | 1 | **Do not solder directly** (Use Headers) |
| **Motor Driver** | TB6612FNG Dual H-Bridge | 1 | **Do not solder directly** (Use Headers) |
| **Female Headers** | 2.54mm Female Pin Headers | 1 set | Sockets for ESP32 & Driver mounting |
| **DC Motors** | Yellow Gearbox Motor (Ratio 1:48) | 2 | Standard "TT" motors |
| **Switch** | Mini Toggle Switch SPDT ON-ON | 1 | Power control (PCB Mount) |
| **Caster Wheel** | Metal Ball Caster | 1 | Front support |
| **Batteries** | Li-Ion 18650 (3.7V) | 2 | Power source |
| **Battery Holder** | 2x18650 Holder (Commercial) | 1 | Screw-mounted to adapter |
| **LEDs** | 3mm or 5mm LEDs | 4 | 2 Front / 2 Back |
| **Resistor** | 220 Ohms | 4 | For correct led funtioning |
| **Bolts M3x8** | ISO M3 Cylindrical Head | 8 | Motor & Support assembly |
| **Bolts M4x6** | ISO M4 Cylindrical Head | 4 | For caster wheel |
| **Custom PCB** | Designed for RC-Car-DIY | 1 | Manufactured by JLCPCB |

### 🖨️ 2. 3D Printed Parts

> **📂 CAD FILES LOCATION:**
> * **Editable:** `MAIN/CAD/Fusion` (`.f3z`)
> * **Exported:** `MAIN/CAD/STEP` (`.step`)

| Part Name (Filename) | Description | Qty | Material |
| :--- | :--- | :---: | :---: |
| `Portamotor_Derecho` | Right side motor mount | 1 | PLA |
| `Portamotor_Izquierdo` | Left side motor mount | 1 | PLA |
| `Rin` | Wheel rim for motor shaft | 2 | PLA |
| `Neumatico` | Flexible tire for the rim | 2 | **TPU** |
| `Adaptador_Porta_Baterias` | Interface between PCB and Battery Holder | 1 | PLA |
| `Adaptador_Rueda_Loca` | Mount/Spacer for metal caster | 1 | PLA |

### 🛠️ 3. Tools Required
* **Soldering Iron & Solder:** For Switch, LEDs, and Headers.
* **Screwdrivers / Allen Keys:** M3 & M4.
* **Xbox Controller:** For Bluetooth control.

---

## Versión en Español 🇪🇸

Este documento detalla la lista completa de hardware, electrónica y piezas impresas en 3D necesarias para construir el **RC-Car-ESP32-DIY**.

### 📋 1. Hardware y Electrónica
Componentes a montar en la PCB personalizada.

| Nombre Componente | Descripción / Specs | Cant. | Notas |
| :--- | :--- | :---: | :--- |
| **Microcontrolador** | ESP32 Dev Module (30/38 pines) | 1 | **No soldar directo** (Usar Headers) |
| **Driver Motor** | TB6612FNG Dual H-Bridge | 1 | **No soldar directo** (Usar Headers) |
| **Headers Hembra** | Tiras de pines hembra 2.54mm | 1 set | Zócalos para montar ESP32 y Driver |
| **Motores DC** | Motor caja reductora amarilla (1:48) | 2 | Estándar "TT" |
| **Switch** | Mini Toggle Switch SPDT ON-ON | 1 | Control encendido (Montaje PCB) |
| **Rueda Loca** | Rueda loca de metal (bola) | 1 | Apoyo frontal |
| **Baterías** | Ion de Litio 18650 (3.7V) | 2 | Fuente de poder |
| **Portapilas** | Soporte para 2x18650 (Comercial) | 1 | Se atornillan al adaptador |
| **LEDs** | LEDs de 3mm o 5mm | 4 | 2 Delanteros / 2 Traseros |
| **Resistencia** | 220 Ohm | 4 | Correcto funcionamiento de las leds |
| **Pernos M3x8** | Cabeza cilíndrica ISO M3 | 8 | Montaje de motores y soportes |
| **Pernos M4x6** | Cabeza cilíndrica ISO M4 | 4 | Montaje de la Rueda Loca |
| **PCB Personalizada** | Diseño para RC-Car-DIY | 1 | Fabricada por JLCPCB |

### 🖨️ 2. Piezas Impresas en 3D

> **📂 UBICACIÓN ARCHIVOS CAD:**
> * **Editables:** `MAIN/CAD/Fusion` (`.f3z`)
> * **Exportados:** `MAIN/CAD/STEP` (`.step`)

| Nombre Pieza (Archivo) | Descripción | Cant. | Material |
| :--- | :--- | :---: | :---: |
| `Portamotor_Derecho` | Soporte motor lado derecho | 1 | PLA |
| `Portamotor_Izquierdo` | Soporte motor lado izquierdo | 1 | PLA |
| `Rin` | Llanta para el eje del motor | 2 | PLA |
| `Neumatico` | Cubierta flexible para la llanta | 2 | **TPU** |
| `Adaptador_Porta_Baterias` | Interfaz entre PCB y Portapilas | 1 | PLA |
| `Adaptador_Rueda_Loca` | Montura/Espaciador para rueda loca | 1 | PLA |

### 🛠️ 3. Herramientas Necesarias
* **Cautín y Estaño:** Para Switch, LEDs y Headers.
* **Destornilladores / Llaves Allen:** M3 y M4.
* **Mando de Xbox:** Para control Bluetooth.