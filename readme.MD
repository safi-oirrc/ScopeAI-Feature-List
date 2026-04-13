# ScopeAI Viewer (Based on OHIF)

This document lists the core and custom features available in ScopeAI, along with demo references.

---

## Feature List

| Feature ID | Feature Name                                       | Video / Demo Link |
| ---------- | -------------------------------------------------- | ----------------- |
| 1          | IR to B-scan Correspondence                        | URL               |
| 2          | Multi-Viewport Support (Side-by-Side Viewing)      | URL               |
| 3          | Upload Support (DICOM, .tgz, .e2e, MAIA3)          | URL               |
| 4          | Delete Files from Frontend                         | URL               |
| 5          | Patient Visit Grouping in Sidebar                  | URL               |
| 6          | Adjustable Viewport Ratio (Drag to Resize)         | URL               |
| 7          | Default OCT Layout (30-70 IR & B-scans)            | URL               |
| 8          | Auto Scroll with FPS Control                       | URL               |
| 9          | Navbar Tools (Zoom, Pan, Rotate, Screenshot, etc.) | URL               |
| 10         | IR to B-scan Mapping API Trigger (Same Visit)      | URL               |

---

## Feature Descriptions

### 1. IR to B-scan Correspondence

When IR and B-scan images from the same visit are opened side by side, the system establishes correspondence between them using mapping logic.

### 2. Multi-Viewport Support

Allows multiple imaging files to be viewed simultaneously for better comparison and analysis.


### 3. Upload Support

Users can upload imaging data in multiple formats including DICOM, .tgz, .e2e, and MAIA3.


### 4. Delete Files from Frontend

Users can directly delete uploaded files from the UI without backend intervention.

### 5. Patient Visit Grouping

All visits belonging to the same patient are grouped together in the sidebar for quick navigation.

### 6. Adjustable Viewport Ratio

Users can drag between viewports to dynamically adjust the layout proportions.

### 7. Default OCT Layout

OCT files automatically open in a 30-70 layout, showing IR image and B-scans in an optimized configuration.

### 8. Auto Scroll with FPS Control

Supports automatic scrolling through image frames with adjustable frames-per-second for precise control.

### 9. Navbar Tools

Includes essential tools such as zoom, pan, rotation, screenshot capture, and other viewing utilities.

### 10. IR to B-scan Mapping API Trigger

When IR and B-scans from the same visit are opened, a mapping API is triggered to synchronize navigation.

---

## Notes

* Replace 'URL' with actual demo or video links.
* Videos can be embedded directly using Markdown if hosted publicly.

### Example Video Embed

```md
![Feature Demo](https://your-video-link.com/demo.mp4)
```

Or using HTML:

```html
<video src="https://your-video-link.com/demo.mp4" controls></video>
```

---

## End of Document
