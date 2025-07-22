# 🛠️ Hardware Assembly - sUAS Quadcopter Build

This guide walks through the step-by-step **hardware assembly** of the quadcopter frame and major components used in this project.

---

## 📦 Components Used

- **Frame:** ImpulseRC ApexDC EVO 5" FPV Frame Kit
- **Motors:** Axisflying AE2207 V2 1860KV 6S Motors (x4)
- **Flight Stack:** SpeedyBee F405 V4 + 4-in-1 55A ESC Stack
- **Battery:** Tattu R-Line 6S 1050mAh 130C XT60
- **Propellers:** Gemfan Hurricane 51477 3-Blade Props
- **Video System:** DJI O3 Air Unit (mounted separately)

---

## 1. 🧱 Frame Assembly

### ⚙️ Rear vs Front Arms
- The ApexDC EVO uses a **deadcat layout**:
  - **Shorter arms go in the front**
  - **Longer arms go in the rear**
- This improves HD camera visibility by reducing front prop intrusion.

### 🛠️ Mounting Procedure
- Lay out the **main bottom plate**.
- Mount all 4 arms using supplied press nuts, screws, and brace plates.
- Assemble the top plate and side braces.

> 💡 If your kit is missing standoffs, check online vendor or contact ImpulseRC for replacements.

---

## 2. ⚡ Install 4-in-1 ESC

- Mount the **SpeedyBee 4-in-1 ESC** directly onto the frame using **nylon or silicone grommeted standoffs**.
- Align orientation so motor pads M1–M4 match with the correct corners.
- **Do not solder anything yet** — dry fit first.

---

## 3. 🔧 Mount Motors

- Secure each AE2207 motor to an arm with **correct-length M3 screws**.
  - Check depth so they don't hit the windings (~6-8mm screws).
- Use **Loctite 243** to secure into metal threads (not plastic).
- Route motor wires neatly toward the ESC.

---

## 4. 🔌 Solder Motors to ESC

- Solder each motor’s 3 wires to ESC pads:
  - M1: Front Right
  - M2: Rear Right
  - M3: Rear Left
  - M4: Front Left
- Wire order doesn’t matter for now — direction will be set in Betaflight/BLHeli.

---

## 5. 🔋 Solder XT60 & Capacitor

- Solder XT60 pigtail to ESC’s main power pads (RED = +, BLACK = –).
- Add a **low-ESR capacitor** across the pads (optional but recommended).
- Use shrink wrap or electrical tape to protect solder joints.

---

## 6. 🧠 Mount Flight Controller

- Mount the **SpeedyBee F405 V4 FC** above the ESC using included stack screws.
- Use the supplied soft silicone mounting gummies.
- Connect the FC to ESC via JST harness.

---

## 7. 📡 Install Peripherals

- Mount and wire:
  - **DJI O3 Air Unit** (or analog VTX)
  - **Receiver** (ELRS, TBS, FrSky, etc.)
  - **GPS**, if used
  - **Buzzer / LEDs** (optional)

Use the SpeedyBee pinout to solder signal and power wires.

---

## 8. 🧪 Initial Power-On

- Plug in via USB or smoke-stopper for the first time.
- Check for:
  - Power LED on FC
  - No smoke/smell from ESC
  - Motors idle (not spinning)

> ✅ Ready for software setup next (see `docs/02_software_setup.md`)

---

## 📸 Photos

_You can add images here once uploaded to `/img` folder:_
