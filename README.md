# Common Ground

**Open-source Rhino 8 and Grasshopper tools for 3D Tiles and Cesium, built for civic site planning.**

Common Ground connects the design model to the real world and back again. Designers pull accurate, georeferenced site context into Rhino, and publish design options as 3D Tiles that residents can explore on a phone, in their own language.

Developed by [Studio RNB](https://studiornb.com), an Atlanta architecture and development firm, with students at Kennesaw State University.

> Status: in planning. Development begins in early 2027. Watch this repository for releases.

## Why

- Rhino and Grasshopper are core design tools in architecture schools and practice, but there is no supported path from Rhino to 3D Tiles and Cesium.
- Early site models are often traced by hand, so terrain and neighboring buildings are approximate.
- Design options reach the public as flat images. Residents who do not read plans, or do not read English, are left out of the conversation.

## What it will include

| Component | What it does |
| --- | --- |
| **Ground In** (Grasshopper) | Set a site by address or coordinates; bring in terrain (Cesium World Terrain or USGS 3DEP), building context (Cesium OSM Buildings or OpenStreetMap) and parcels, in local coordinates. |
| **Ground Out** (Grasshopper) | Publish Rhino and Grasshopper geometry as 3D Tiles 1.1 with per-element metadata (option, use, height, floor area, phase, custom fields). Write locally or upload to Cesium ion in one step. |
| **Zoning Envelope** (Grasshopper) | Generate a buildable envelope from parcel, setbacks and height limits, with floor-area metadata. |
| **Common Ground Viewer** (CesiumJS) | A forkable, mobile-first public engagement page: compare options on real terrain, multilingual labels, feedback pins exported to GeoJSON. |
| **Classroom module** | Three labs on accurate site modeling, publishing 3D Tiles and running a public review, with sample data and tutorials. |

## Roadmap

| Milestone | Target |
| --- | --- |
| Ground In alpha | March 2027 |
| Ground Out and Zoning Envelope | May 2027 |
| Viewer and proposed first city pilot (Clarkston, GA) | July 2027 |
| v1.0 release, course module, tutorials | September 2027 |

## Data and licensing

- Code, docs, curriculum and sample data: Apache License 2.0.
- Terrain and buildings come from open sources. Google Photorealistic 3D Tiles are displayed only inside the CesiumJS viewer, consistent with Google's terms.
- Client project data is never published without the client's approval.

## Contact

Rourke Brakeville, Studio RNB
rbrakeville@studiornb.com
