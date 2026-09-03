# Pulse — Week 4 Frontend Performance Optimization

## Objective
Pulse is a lightweight dashboard created for the Yuva Intern Week 4 performance optimization challenge.

## Optimizations implemented
- Minified CSS and JavaScript assets.
- Deferred JavaScript with `defer`.
- Lazy loading and async decoding for below-the-fold imagery.
- SVG-first graphics to reduce image payload.
- Explicit image dimensions to reduce layout shift.
- Reduced DOM complexity and removed unnecessary dependencies.
- Responsive CSS with a small number of breakpoints.
- Preloaded the critical hero SVG.
- No external font, icon, CSS framework, or JavaScript library dependency.

## Performance audit method
The project is designed to be tested with Google Lighthouse or PageSpeed Insights. The report distinguishes implementation-level measurements from browser-run Lighthouse scores so that no unverified score is presented as a real audit result.

## Run
Open `index.html` in a browser or serve the folder with any static HTTP server.
