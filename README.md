# Statistical-Steganography-Detection-Tool
This project implements first-order statistical steganalysis techniques including histogram analysis, even–odd pixel distribution testing, LSB entropy measurement, and image complexity awareness to detect potential LSB-based steganography.

**🔍 Overview**

This project implements first-order statistical steganalysis techniques to detect potential LSB-based steganography in digital images.
The system analyzes pixel-level statistical deviations introduced by hidden data embedding.

**⚙️ Techniques Used**

**=>** Pixel Intensity Histogram Analysis
**=>** Even–Odd LSB Distribution Test
**=>** LSB Entropy Measurement
**=>** Image Complexity Awareness (Texture & Color Diversity)
**=>** Suspicion Scoring Engine

**Detection Pipeline**
Image → Histogram → Even-Odd Test → LSB Entropy → Complexity Check → Suspicion Score → Verdict

**📊 Key Concept**
LSB steganography introduces artificial randomness into the least significant bit plane.
This tool detects statistical anomalies caused by such embedding.

**⚠️ Note**
Entropy alone is not sufficient for detection.
The system correlates multiple statistical indicators to reduce false positives.
