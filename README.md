HTML5 Canvas & Drawing for Nim
==============================

The official repo can be found on GitLab:
https://gitlab.com/define-private-public/HTML5-Canvas-Nim

It is where most of the develoment takes place.  But there is a GitHub mirror
where issues can be logged and will be addressed:
https://github.com/define-private-public/HTML5-Canvas-Nim

This is still a work in progress, expect a better README later.


TODO:
 - [ ] Professional README
   - Don't forget to link to the mozilla docs
 - [x] List of functions/properties to bind (https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)
 - [ ] some examples/tests
 - [x] GitHub mirror
 - [ ] License mention in README


To Bind & Test.  Key: `b`=bound, `x`=bound & tested
 - [b] rgb()
 - [ ] Canvas
 - [ ] height
 - [ ] width 
 - [ ] toDataURL()
 - [ ] toBlob()
 - [ ] getContext()
 - [ ] clearRect()
 - [ ] fillRect()
 - [ ] strokeRect()
 - [ ] TextMetrics
 - [ ] fillText()
 - [ ] strokeText()
 - [ ] measureText()
 - [ ] lineWidth
 - [ ] lineCap
 - [ ] lineJoin
 - [ ] miterLimit
 - [ ] getLineDash()
 - [ ] setLineDash()
 - [ ] lineDashOffset
 - [ ] font
 - [ ] textAlign
 - [ ] textBaseline
 - [ ] direction
 - [ ] fillStyle
 - [ ] strokeStyle
 - [ ] createLinearGradient()
 - [ ] createRadialGraident()
 - [ ] CanvasImageSource
 - [ ] createPattern()
 - [ ] shadowBlur
 - [ ] shadowColor
 - [ ] shadowOffsetX
 - [ ] shadowOffsetY
 - [ ] beginPath()
 - [ ] closePath()
 - [ ] moveTo()
 - [ ] lineTo()
 - [ ] bezierCurveTo()
 - [ ] quadraticCurveTo()
 - [ ] arc()
 - [ ] arcTo()
 - [ ] ellipse()  [EXP]
 - [ ] rect()
 - [ ] fill()
 - [ ] stroke()
 - [ ] drawFocusIfNeeded()
 - [ ] scrollPathIntoView()
 - [ ] clip()
 - [ ] isPointInPath()
 - [ ] isPointInStroke()
 - [ ] currentTransform
 - [ ] rotate()
 - [ ] scale()
 - [ ] translate()
 - [ ] transform()
 - [ ] setTransform()
 - [ ] resetTransform()
 - [ ] SVGMatrix
 - [ ] globalAlpha
 - [ ] globalCompositeOperation
 - [ ] drawImage()
 - [ ] createImageData()
 - [ ] getImageData()
 - [ ] putImageData()
 - [ ] ImageData
 - [ ] imageSmoothingEnabled  [EXP]
 - [ ] save()
 - [ ] restore
 - [ ] canvas
 - [ ] addHitRegion()  [EXP]
 - [ ] removeHitRegion()  [EXP]
 - [ ] clearHitRegions()  [EXP]


Extra:
 - [ ] shadowOffset to take Nim's tuples instead?
 - [ ] SVGMatrix <-> Nim Matrix
 - [ ] Play nice with `colors` module
