# Dancingbrush Labs

Building practical software and creative works.

Dancingbrush Labs is the top-level home for publication work, practical desktop
software, and future connected analysis products.

Our goal is simple: build useful things that are enjoyable to create and easy to
use.

## Structure

```text
Dancingbrush Labs
├─ Dancing Brush
│  └─ Publication and picture-book related website
├─ Curve Trace
│  └─ Product website for fast image digitizing
└─ Quicklog
   └─ Planned quick log analysis application connected with Curve Trace
```

## Projects

### Dancing Brush

Publication and picture-book related website.

This area will cover published works, upcoming titles, and creative publication
projects.

### Curve Trace

Fast image digitizer for charts, scanned figures, and log images.

Curve Trace focuses on practical digitizing workflows: load an image, calibrate
the axes, trace the curve, review the result, and export the data.

### Quicklog

Planned quick log interpretation program.

Quicklog is intended to connect with Curve Trace after digitizing. A future
workflow may pass digitized results into Quicklog through a direct connection
button or handoff action.

## Repositories

| Area | Repository | Purpose | Visibility |
| --- | --- | --- | --- |
| Dancingbrush Labs | `Dancingbrushlabs/dancingbrushlabs` | Top-level homepage | Public |
| Dancing Brush | `Dancingbrushlabs/publication` | Publication website | Public |
| Curve Trace website | `Dancingbrushlabs/curvetrace` | Product introduction page | Public |
| Curve Trace app | `Dancingbrushlabs/curvetrace-app` | Application source code | Private |
| Quicklog app | `Dancingbrushlabs/quicklog-app` | Planned log analysis application source code | Private |

## Philosophy

We believe software should be:

- Simple
- Fast
- Practical
- Enjoyable to use

Instead of building software with every possible feature, we focus on creating
tools that solve real problems with intuitive workflows.

## Website

This repository hosts the public Dancingbrush Labs homepage.

## Local Preview

```bash
python3 -m http.server 8083
```

Then open:

```text
http://localhost:8083
```
