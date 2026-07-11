# CTRL TP4 Overlay
An on-screen overlay that extends the Traktor Pro 4 interface with essential live information and controls not available in the standard UI.

## Why use this overlay?
- **Missing UI Information:** The Native Instruments Traktor Pro 4 interface does not display several pieces of information that are available on dedicated hardware controllers such as the Traktor Kontrol D2, S5, S8, and S4 MK3.
- **Hardware Independence:** Users without these specialized Traktor controllers can now view critical live information, including FX parameter values and Hotcue names, directly within the software interface.

## How does the app work?
- **CTRL TP4 Overlay** utilizes Traktor's native QML framework to create transparent overlay windows positioned directly over the Traktor interface. These overlays read and display live Traktor data using the same internal properties available to Native Instruments' hardware controllers.
- The overlay is fully integrated with Traktor and does not require screen capture, OCR, image recognition, or external automation tools.

## Does the app save settings?
- **Automatic Persistence:** Yes. Overlay settings are automatically saved and restored each time Traktor is launched.

<img width="709" height="291" alt="image" src="https://github.com/user-attachments/assets/8891f392-94c7-496b-9322-b1e54f7b8357" />

## Version History

### v1.0
- **Initial Release:** First public release of CTRL TP4 Overlay.
- **Resolution Limit:** Optimized for a fullscreen resolution of 1920 × 1080.
- **FX Support:** Supports FX Units 1 and 2 using the Single FX layout.
- **FX Controls:** Includes clickable FX On, FX Button 1–3, and Previous/Next FX selection controls directly within the overlay.
- **Known Limitation:** The standard Traktor FX selection dropdown is replaced with Previous and Next buttons due to overlay window limitations.



## Planned Additions

### Overlay Modules
- Hotcue names displayed directly over the Traktor hotcue buttons.
- Preview player controls.
- Additional FX Unit support (Units 3 and 4).
- Support for Group FX mode.
- Support for Pattern Player mode.
- Touchscreen optimization.
- Configurable user settings

### User Experience
 - Additional supported screen resolutions.
 - Customizable overlay positioning and layout.
 - Per-module enable/disable options.

### Controls
- Clickable Hotcue labels.
- Additional interactive overlay controls.

### Compatibility
- Compatibility with future Traktor Pro releases.
- Additional hardware mapping support.
