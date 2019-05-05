* Compare images based on file properties (e.g. SHA256)
* Compare images based on content (phashes)
* Derive timestamps based on:
    * Metadata (duh)
    * Filename
    * Neighbours/Relative ordering
* Adjust timestamps based on relative ordering, i.e. knowing the absolute date of adjacent files adjusts the possible window
* Derive location based on likely neighbours
* Filter images on
    * Filename (e.g. `WA000*` for WhatsApp images)
    * Path (e.g. `received files`)
    * Camera
    * Location
    * Date range
* Import metadata from
    * JSON
    * HTML files (e.g. specify a `<div>` with a timestamp from an album, i.e. Facebook dump)
* Export adjustments to file