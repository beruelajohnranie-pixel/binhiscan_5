

## BinhiScan v8 (old homepage preserved)
- This package restores the original homepage/splash from the older project.
- The existing trained TensorFlow.js model and its labels/weights are unchanged.
- Borderline predictions are shown as "Possible match", not as a confirmed seed.
- "Try demo scan" is a clearly labelled UI-only test; it does not represent a real AI prediction.
- The model can only recognize labels listed in `model/metadata.json`. A seed type not listed there requires retraining.
- For a real test, use one supported seed per image, centered, close, and well lit.
