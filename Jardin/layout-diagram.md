# Garden Layout — Mermaid Diagram

Rendered version of the garden plan. View in any Markdown editor with Mermaid support (VS Code, GitHub, etc.).

---

## Top-Down Layout

```mermaid
block-beta
  columns 4

  block:north:4
    n["North buffer — 1 m access path"]
  end

  block:allium_zone:4
    allium["Allium Bed\nshallot · garlic\n2 × 2 m"]:2
    open["(open area)"]:2
  end

  block:main_zone:4
    brassica["Brassica Bed\ncabbage · kale\nbroccoli · kohlrabi\n+ greens trial\n2 × 5 m"]:1
    path["PATH\n2 m wide"]:1
    rootA["Root Bed A\npotato\n1 × 5 m"]:1
    rootB["Root Bed B\ncarrot · parsnip\n1 × 5 m"]:1
  end

  block:trellis_zone:4
    t["Trellis zone — spans full 6 m width"]:4
  end

  block:trellis_beds:4
    space:1
    rb1["RB 1\nmâche"]:1
    rb2["RB 2\nrocket"]:1
    rb3["RB 3\nmicrogreens"]:1
  end

  block:south:4
    s["South (front) ← entrance and trellis side"]
  end

  style allium fill:#e8d5e8,stroke:#9b59b6,color:#333
  style brassica fill:#a8d5a2,stroke:#27ae60,color:#333
  style rootA fill:#f0d9a0,stroke:#e67e22,color:#333
  style rootB fill:#f5c6a0,stroke:#d35400,color:#333
  style rb1 fill:#b8d8e8,stroke:#3a7cbd,color:#333
  style rb2 fill:#b8d8e8,stroke:#3a7cbd,color:#333
  style rb3 fill:#b8d8e8,stroke:#3a7cbd,color:#333
  style path fill:#d4c9a8,stroke:#b8a97e,color:#555
  style open fill:#f0ece2,stroke:#ccc,color:#999
  style t fill:#d6e8f0,stroke:#5b9bd5,color:#3a7cbd
  style n fill:#eee,stroke:#ccc,color:#999
  style s fill:#eee,stroke:#ccc,color:#999
```

---

## Orientation Key

| Direction | Feature |
|---|---|
| **North** (top) | Rear of garden — buffer path |
| **South** (bottom) | Front — trellis and raised beds |
| **West** (left) | Fence line — Brassica Bed + Allium Bed |
| **East** (right) | Entrance — Root Beds A + B |

---

## Bed Areas

| Bed | Dimensions | Area |
|---|---|---|
| Brassica Bed | 2 × 5 m | 10 m² |
| Allium Bed | 2 × 2 m | 4 m² |
| Root Bed A | 1 × 5 m | 5 m² |
| Root Bed B | 1 × 5 m | 5 m² |
| Trellis RB 1–3 | 0.9 × 1.2 m × 3 | 3.24 m² |
| **Total growing area** | | **~27 m²** |
