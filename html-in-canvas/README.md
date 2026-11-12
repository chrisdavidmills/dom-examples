# MDN HTML-in-canvas examples

This set of examples demonstrates usage of the [HTML-in-canvas API](https://github.com/WICG/html-in-canvas):

- [Canvas 2D context example](2d-context-example/): Demonstrates how an HTML form can be rendered on a 2D canvas, have a pixel distortion effect applied to it on mouseover, but still remain accessible, interactive, and submittable ([run example live](https://mdn.github.io/dom-examples/html-in-canvas/2d-context-example/)).
- [WebGL example](webgl-example/): This example shows how to render an HTML form as a texture onto all six sides of a rotating 3D cube. When the form is hovered or focused, the rotation pauses and you can interact with form on the front-most cube face as expected (clicking into it, etc.). Again, it still remains accessible, interactive, and submittable ([run example live](https://mdn.github.io/dom-examples/html-in-canvas/webgl-example/)).
- [WebGPU example](webgpu-example/): This example is the same as the WebGL example, only converted to use WebGPU instead ([run example live](https://mdn.github.io/dom-examples/html-in-canvas/webgpu-example/)).
- [Canvas 2D context nested canvases example](2d-context-nested-canvases/): Demonstrates how the paint events fire in nested canvases ([run example live](https://mdn.github.io/dom-examples/html-in-canvas/2d-context-nested-canvases/)).
