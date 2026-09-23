# PDF.js mobile manuscript viewer

Vendored from Mozilla's PDF.js v6.3.289 legacy distribution:
https://github.com/mozilla/pdf.js/releases/download/v6.3.289/pdfjs-6.3.289-legacy-dist.zip

The legacy build includes compatibility support for older browsers. Minerva
loads this self-hosted viewer on small screens and coarse-pointer devices;
desktop readers continue to use their browser's native PDF viewer.

The upstream LICENSE and bundled resource licenses are retained. Source maps
and the example PDF are omitted. Local customizations are the document title
and the linked `web/minerva-viewer.css` stylesheet. Keep these changes when
updating the vendored release.

To check the mobile regression, open `/minerva` in a touch-capable browser,
scroll within the PDF past page 1, jump to a later page, and check zooming.
