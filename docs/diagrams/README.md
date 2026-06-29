# Diagram sources (`.mmd`)

Each file here is **one diagram** from
[`../ARCHITECTURE.md`](../ARCHITECTURE.md), pulled out so you can import it into
[Excalidraw](https://excalidraw.com) one at a time.

All diagrams are styled **white / shades of gray** (Mermaid's `neutral` theme +
white/light-gray fills, dark-gray lines, black text) so they project clearly on a
beamer/projector.

## How to put one on an Excalidraw canvas

1. Open [excalidraw.com](https://excalidraw.com) (or the desktop app).
2. Toolbar → **More tools** → **Mermaid to Excalidraw** (desktop: `Ctrl/Cmd + M`).
   Fool-proof alternative: the [Mermaid-to-Excalidraw playground](https://mermaid-to-excalidraw.vercel.app/).
3. Open a `.mmd` file, copy **all** its text, paste it into the left box.
4. Click **Insert** → the shapes drop onto the canvas, ready to move/annotate.

> **If a diagram refuses to import:** delete the very first line
> `%%{init: {'theme':'neutral'}}%%` and paste again. That line only controls the
> grayscale theme; the diagram works without it (Excalidraw already draws on a
> white canvas).

## Editable vs. image-only

Excalidraw turns **flowcharts and sequence diagrams** into real, editable shapes.
Three files use other Mermaid types and come in as a (grayscale) **image** instead:

| File | Type | In Excalidraw |
|------|------|----------------|
| `02-tech-stack-mindmap.mmd` | mindmap | image |
| `15-er-data-model.mmd` | erDiagram | image |
| `23-state-machine-link-dialog.mmd` | stateDiagram | image |

Everything else (the other 20) imports as editable shapes. If you want those three
editable too, ask and I'll re-express them as flowcharts / a class diagram.

## Index

| # | File | What it shows |
|---|------|----------------|
| 01 | `01-system-architecture.mmd` | Browser ↔ Clerk ↔ Express ↔ MongoDB |
| 02 | `02-tech-stack-mindmap.mmd` | Every dependency, by layer |
| 03 | `03-request-end-to-end.mmd` | One full request round-trip |
| 04 | `04-component-hierarchy.mmd` | React provider/component tree |
| 05 | `05-routing-map.mmd` | URL → page, public vs protected |
| 06 | `06-page-anatomy.mmd` | fetch → reducer → render → dispatch |
| 07 | `07-reducer-state-flow.mmd` | How a reducer updates state |
| 08 | `08-collections-context-before.mmd` | The two-copies bug |
| 09 | `09-collections-context-after.mmd` | Single source of truth (fix) |
| 10 | `10-backend-module-structure.mmd` | Backend files & responsibilities |
| 11 | `11-express-middleware-pipeline.mmd` | Request middleware order |
| 12 | `12-attachuser-auth-flow.mmd` | Auth gate + lazy user creation |
| 13 | `13-get-links-query-builder.mmd` | Query params → `where` clause |
| 14 | `14-resolve-tag-ids.mmd` | Tag-name → tag-row resolution |
| 15 | `15-er-data-model.mmd` | Database entities & relations |
| 16 | `16-dfd-level-0.mmd` | Data flow: context diagram |
| 17 | `17-dfd-level-1.mmd` | Data flow: inside the system |
| 18 | `18-seq-add-link.mmd` | Sequence: add a link |
| 19 | `19-seq-toggle-favorite.mmd` | Sequence: toggle favorite |
| 20 | `20-seq-create-collection.mmd` | Sequence: create a collection |
| 21 | `21-seq-delete-collection.mmd` | Sequence: delete a collection |
| 22 | `22-ownership-security.mmd` | How per-user scoping is enforced |
| 23 | `23-state-machine-link-dialog.mmd` | Add/edit dialog states |
