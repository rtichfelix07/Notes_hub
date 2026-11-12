CLASS NOTES HUB
================

Overview
--------
Class Notes Hub is a simple, responsive student resource website prototype.
It provides a place to browse academic units, filter units by semester, search
for units, and open learning-resource files.

Current project files
---------------------
index.html
    Main website page. It contains the HTML structure, CSS styling, sample
    unit data, semester filters, and search functionality.

readme.txt
    Project information and setup notes.

How to preview
--------------
1. Download or clone the repository.
2. Open index.html in a modern web browser.
3. Use the semester tabs to filter the displayed units.
4. Enter a unit name in the search field to find a unit.

Configure resource downloads
----------------------------
The current index.html uses a placeholder storage address:

https://YOUR-BUCKET.s3.YOUR-REGION.amazonaws.com/public/

Before expecting downloads to work, replace the BASE value in index.html
with the real public storage URL.

The sample unit names and PDF filenames are demonstration data. Update the
units array in index.html with the actual units and resource filenames.
Make sure each resource URL points to the correct file. Files with the same
filename in different units may need separate folders or unique object keys
to avoid linking every unit to the same document.

Current functionality
---------------------
- Responsive unit-card layout
- Semester 1, Semester 2, and All filters
- Search by unit name
- Links to learning resources

Not yet implemented
-------------------
- User accounts and authentication
- Student resource uploads
- Upload moderation and administrator tools
- Database-backed units and resources
- Resource preview and download tracking

Development notes
-----------------
This is currently a static HTML/CSS/JavaScript prototype. No backend or
database is configured yet. Do not place private credentials or secret keys
in frontend files.

Future development can introduce a backend, database, secure file storage,
student contributions, and administration features as the project grows.
