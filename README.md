# Digital ID & Neural Portfolio

Interactive 3D WebGL physics portfolio of Vasudev Singh Jamwal, featuring custom kinetic drag drivers, zero-dependency FakeScroll physics, and dynamic vCard generation.

## Technical Architecture
- **Rendering Pipeline**: HTML5 WebGL particle acceleration with clamped delta time.
- **Gesture Physics**: Hardware-accelerated pointer event listeners with deceleration curves.
- **Export Protocols**: RFC 6350 vCard 3.0 / 4.0 compliant contactless payload.

## Core Modules
- `CanvasParticles`: Self-contained WebGL point cloud shader with smooth radial displacement.
- `FakeScrollDriver`: Direct DOM manipulation decoupling native browser scrolling from canvas render loop.

## Browser Compatibility Matrix
Tested and verified across Safari 15+, Chromium 90+, and Firefox 88+ on desktop, iOS, and Android viewports.

## Performance Benchmarks
Maintains 60fps stable frame budget on mobile and 120Hz/144Hz on high-refresh ProMotion/gaming panels with sub-16ms paint times.
