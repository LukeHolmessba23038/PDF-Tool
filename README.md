# PDF-Tool

SplitStitch: Your Client-Side PDF & Image Utility
SplitStitch is a powerful, privacy-focused web application designed to help you merge, edit, and split PDF documents, as well as stitch and enhance your images, all directly within your web browser. Your files are never uploaded to any server, ensuring complete privacy and security for your sensitive documents and photos.

✨ Features
PDF Tools
Merge PDFs:

Combine multiple PDF files into a single document.

Drag-and-drop support for easy file selection and reordering.

Clear interface to manage your file list.

Edit PDFs:

Load and manage pages of a single PDF document.

Visual thumbnail previews of each page.

Drag-and-drop to reorder pages.

Select multiple pages for batch operations (using Ctrl/Cmd + Click or Shift + Click).

Remove selected pages.

Extract selected pages into a new PDF.

Add blank pages at any position.

Rotate selected pages (90° Left, 90° Right, 180°).

Insert pages from another PDF at a specified location.

Undo/Redo functionality for all editing operations.

Right-click context menu for quick page actions.

Full-page preview modal with zoom controls.

Split PDFs:

Divide a single PDF document into multiple smaller PDFs.

Flexible splitting options:

Each Page: Creates a separate PDF for every page.

Every X Pages: Splits into files of a fixed page count (e.g., every 5 pages).

Custom Page Ranges: Define specific page ranges to extract into individual new PDFs.

By Top-Level Bookmarks: Splits the PDF based on its top-level bookmarks (if available).

Provides individual download links for each generated PDF.

Image Tools
Image Stitching:

Combine multiple JPG or PNG images into a single long image (collage or panorama).

Drag-and-drop support for file selection.

Drag-and-drop to reorder image previews.

Choose vertical or horizontal stitching direction.

Adjust spacing between images.

Set alignment (Left/Top, Center, Right/Bottom) for images within the stitched canvas.

Add watermark text with customizable position.

Image Editing (Per-Image):

Rotate individual images left or right from their previews.

Crop individual images using an interactive cropping tool.

Adjust Brightness of individual images.

Remove individual images from the list.

Output Control:

Set output filename.

Choose JPG or PNG output format.

Adjust JPG quality (for JPG output).

Select background color (for PNG output).

Convert stitched image directly to a multi-page PDF (supports various page sizes like A4, A3, Letter).

Live Preview: See a low-resolution, real-time preview of your stitched image as you adjust settings.

Undo/Redo: Track and revert/reapply changes to your image list and edits.

"Clear Images" and "Reset All" options for quick workflow management.

🚀 How to Use
Open Integrated.html in a modern web browser (e.g., Chrome, Firefox, Edge, Safari).

Select a Tab: Choose between "PDF Tools" or "Image Tools" using the main navigation at the top.

Using PDF Tools:
Merge PDFs:

Click the "Merge PDFs" sub-tab.

Click "Choose PDF files" or drag and drop your PDF documents onto the designated area.

Reorder the files by dragging them in the list.

Click "Merge PDFs" and then "Download Merged PDF" when ready.

Edit PDF:

Click the "Edit PDF" sub-tab.

Click "Choose a PDF file to edit" to select a single PDF.

Once pages load, drag and drop thumbnails to reorder.

Click on a page thumbnail to see a larger preview, or right-click for more options (rotate, delete, extract).

Select multiple pages using checkboxes for batch operations (Remove, Extract, Rotate).

Use the "Insert Pages" section to add pages from another PDF.

Click "Save and Download Edited PDF" to get your modified document.

Split PDF:

Click the "Split PDF" sub-tab.

Click "Choose a PDF file to split" to select a single PDF.

Choose your desired splitting method (e.g., "Split every page", "Split into files of a fixed page count", "Extract page ranges", or "Split by top-level bookmarks").

If using "Custom Page Ranges", click "Add Page Range" and enter your desired start and end pages.

Click "Split PDF" and then download the generated files individually.

Using Image Tools:
Select Images:

Click the "Image Tools" tab.

Click "Select File(s)" within the drop zone or drag and drop your JPG/PNG images onto the drop zone.

Arrange & Edit:

Reorder image previews by dragging them.

Hover over an image preview to reveal controls for Rotate, Crop, Brightness, and Remove.

Configure Stitching:

Adjust "Stitch Direction", "Image Spacing", "Image Alignment".

Set "Output Format" (JPG/PNG), "JPG Quality" (if applicable), and "Background Color" (for PNG).

Add "Watermark Text" and choose its "Position" if desired.

Stitch & Download:

Click "Stitch Images" to generate the final image.

A low-resolution "Live Stitched Preview" will update as you change settings.

Once complete, use "Download Image" or "Download as PDF" to save your stitched file.

Keyboard Shortcuts
Esc: Close any open modal (previews, crop, confirmation).

PDF Tools (when active):

Ctrl/Cmd + A: Select/Deselect all pages.

Ctrl/Cmd + Z: Undo last PDF operation.

Ctrl/Cmd + Y: Redo last undone PDF operation.

Delete or Backspace: Remove selected PDF pages.

Image Tools (when active):

Ctrl/Cmd + O: Open image file selection.

Ctrl/Cmd + Enter: Trigger "Stitch Images".

Ctrl/Cmd + Z: Undo last image operation.

Ctrl/Cmd + Y or Shift + Ctrl/Cmd + Z: Redo last undone image operation.

🔒 Privacy & Security
SplitStitch is designed with your privacy in mind:

Client-Side Processing: All PDF and image operations happen directly within your web browser. Your files are processed entirely on your device.

No Uploads: Your documents and images are never uploaded to any external server. This means your sensitive data remains private and secure.

Secure by Design: As files do not leave your device, there's no risk of interception or storage on remote servers.

Open Source Libraries: We leverage robust and widely-used open-source JavaScript libraries for core functionalities, ensuring transparency and reliability:

pdf-lib: For high-level PDF manipulation.

PDF.js: For rendering PDF documents in the browser.

jsPDF: For generating PDF files (specifically used for image-to-PDF conversion).

Cropper.js: For interactive image cropping.

🛠️ Technologies Used
HTML5

Tailwind CSS: For responsive and utility-first styling.

JavaScript (Vanilla JS): For all application logic and interactivity.

PDF-LIB: PDF manipulation.

PDF.js: PDF rendering.

jsPDF: PDF creation (from images).

Cropper.js: Image cropping.
