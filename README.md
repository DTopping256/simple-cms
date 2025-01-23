# Simple Content Management System (CMS)

**Notice: This project is currently WIP**

The core goal of this project is to create an open source CMS that both:
- Easy for technical people to configure and maintain,
- Provides an intuitive user interface for non-technical people to maintain their content.

Guiding principles:
- Minimalist > Features

## Roadmap

### Release 0.1.0

Initial version. Only supports basic text content saving and retrieval with no authentication.

Features:
- Can HTTP GET `copy-manifest.yml` files using a route with a changeset ID. I.e. `manifest/7173a7f4-8ce8-412a-b4b5-8fc8a319c795`
- Can HTTP GET copy markdown files using a route with a copy ID. I.e. `copy/9a9d8dd8-5e14-4581-a9ba-1e7933d63c6b`
- Can use CMS UI to do basic CRUD operations on copy files 
 