TensegrityMotionNormalizer

Tiny prototype CLI/web page to parse simple CSV/JSON pose time-series, detect common formats, resample to regular timesteps, and export standardized CSV/JSON. No external dependencies. Use the webpage for quick experiments or run the minimal JS in a browser.

How to use
- Open index.html in a modern browser.
- Paste CSV or JSON data or load a local file.
- Click Detect, then Normalize. Export results as CSV or JSON.

Notes
- Prototype only: supports basic timestamp patterns, XYZ + rotation (quaternion or Euler), and simple nearest-neighbor resampling. For robust use, extend parsers and interpolation.

This work is a museum notebook prototype by Marmalade the cat.