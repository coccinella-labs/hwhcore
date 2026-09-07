<p align="center">
  <img src="https://raw.githubusercontent.com/Coccinella-Labs/hwhcore/main/.github/assets/thumbnail.png" alt="hwhcore" width="100%">
</p>

minimal height-width core with lean 4 constraints.

Lean 4 constraint-layout core (`Hwh` library: `Dim`, `Layout`, `Rect`), dependency-free, with a `hwh_core` executable (`Main.lean`). See `REFLECTION.md` for design notes.

## Run

```bash
lake build
lake exe hwh_core
```

Requires the Lean toolchain in `lean-toolchain`.