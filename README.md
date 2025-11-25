# OSINTLens

**OSINTLens** is a context-aware OSINT tool that extracts actionable intelligence from images and screenshots. By analyzing visual and textual content, it identifies potential geolocations, objects, and contextual clues to support investigative and cybersecurity tasks.


## Features

- **Metadata Extraction**: Reads EXIF data, geotags, and embedded metadata from images.  
- **Text Extraction (OCR)**: Detects and extracts text from images and screenshots using Tesseract and OpenCV.  
- **Object Detection**: Identifies key objects and landmarks with pre-trained models like YOLO.  
- **Geolocation Hints**: Matches visual clues to maps or satellite imagery to suggest possible locations.  
- **Contextual Linking**: Combines metadata, text, and object detection results to provide a summarized contextual insight.  


## Tech Stack

- **Languages**: Python  
- **Libraries**: OpenCV, Tesseract OCR, PyTorch (YOLO/Detectron), NumPy, Pandas  
- **APIs**: Google Maps / Street View API, OpenStreetMap  
- **Visualization**: Streamlit / Dash, Folium for maps
