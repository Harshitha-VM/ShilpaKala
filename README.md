# ShilpaKala – Handmade Craft Branding App

ShilpaKala is an Android application designed to support Karnataka artisans by helping them professionally capture, brand, and share handcrafted products using a mobile device.

The app provides a clean camera interface, product branding system, bilingual support (English & Kannada), and catalog-style image generation for handcrafted wooden products.

---

## Features

- Live Camera Preview using CameraX
- Product Alignment Overlay
- Tilt Detection using Accelerometer Sensor
- Kannada and English Language Support
- Product Branding Footer Generation
- Add Artisan Name, Wood Type, and Price
- Save Branded Images to Gallery
- Share Product Images
- Elegant Karnataka Handicraft Inspired UI

---

## Technologies Used

- Kotlin
- Android Studio
- CameraX
- SensorManager
- Canvas & Bitmap Processing
- MediaStore API
- ConstraintLayout

---

## App Workflow

1. Open Camera
2. Align Product using Overlay
3. Capture Product Image
4. Enter:
   - Artisan Name
   - Wood Type
   - Product Price
5. App Generates Branded Catalog Image
6. Save or Share Product

---

## Project Structure

```text
app/
 ├── java/com/example/shilpakala/
 │    ├── MainActivity.kt
 │    ├── OverlayView.kt
 │
 ├── res/
 │    ├── layout/
 │    │    └── activity_main.xml
 │    ├── drawable/
 │    ├── values/
 │
 ├── AndroidManifest.xml
