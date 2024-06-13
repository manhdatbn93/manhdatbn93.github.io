---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1"
collection: portfolio
---

This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML. 


<div id="stl_cont"></div>

<script src="https://cdn.jsdelivr.net/npm/stl-viewer/dist/stl_viewer.min.js"></script>
<script>
    const stlViewer = new StlViewer(
        document.getElementById("stl_cont"), {
            models: [
                { id: 0, filename: "./images/Cottage_FREE.stl" }  // Ensure this path is correct
            ]
        }
    );
</script>