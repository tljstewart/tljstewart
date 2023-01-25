---
layout: page
title: Shader Editor Draft
permalink: /shader-editor/
---

:construction: Please don't mind the progress here, I'm working on something cool :construction: 
<link type="text/css" rel="stylesheet" href="https://raw.githubusercontent.com/patriciogonzalezvivo/glslEditor/main/build/glslEditor.css">
<script type="application/javascript" src="https://raw.githubusercontent.com/patriciogonzalezvivo/glslEditor/main/build/glslEditor.min.js"></script>


<body>
    <div id="glsl_editor"></div>
</body>
<script type="text/javascript">
    const glslEditor = new GlslEditor('#glsl_editor', { 
        canvas_size: 500,
        canvas_draggable: true,
        theme: 'monokai',
        multipleBuffers: true,
        watchHash: true,
        fileDrops: true,
        menu: true
    });
</script>
