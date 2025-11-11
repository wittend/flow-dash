API documentation
==================

This project provides two kinds of documentation:

- Sphinx user and operator docs (these pages)
- Doxygen-generated API reference for the TypeScript/JavaScript source

Viewing the API reference
-------------------------

If you built the docs locally using Doxygen, open the generated HTML index:

- ``docs/doxygen/html/index.html``

On Read the Docs, the build configuration generates the Doxygen output and publishes it under the static files folder. Use this direct link:

- ``_static/doxygen/index.html`` (relative to the Sphinx site root)

Notes
-----
- The Doxygen configuration is tuned for TS/JS and extracts brief descriptions from JSDoc/Doxygen-style comments.
- Only files under ``lib/``, ``public/``, and the top-level ``main.ts`` are scanned.
