# Dancingbrush Labs

Public homepage repository for Dancingbrush Labs.

Dancingbrush Labs is the top-level home for publication work, practical desktop
tools, and future connected analysis products.

## Site Structure

```text
Dancingbrush Labs
├─ Dancing Brush
│  └─ Publication and picture-book related website
├─ Curve Trace
│  └─ Product website for fast image digitizing
└─ Quicklog
   └─ Planned quick log analysis application connected with Curve Trace
```

## Repositories

| Area | Repository | Purpose | Visibility |
| --- | --- | --- | --- |
| Dancingbrush Labs | `Dancingbrushlabs/dancingbrushlabs` | Top-level homepage | Public |
| Dancing Brush | `Dancingbrushlabs/publication` | Publication website | Public |
| Curve Trace website | `Dancingbrushlabs/curvetrace` | Product introduction page | Public |
| Curve Trace app | `Dancingbrushlabs/curvetrace-app` | Application source code | Private |
| Quicklog app | `Dancingbrushlabs/quicklog-app` | Planned log analysis application source code | Private |

## Product Direction

Curve Trace will focus on fast image digitizing. After digitizing a curve, the
workflow may connect directly to Quicklog through a button or handoff action for
quick log interpretation.

## Local Preview

```bash
python3 -m http.server 8083
```

Then open:

```text
http://localhost:8083
```
