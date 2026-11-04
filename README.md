# cad-practice

Beginner parametric CAD exercises in [SolidCraft](https://solidcraft.io), an open-source CAD app. Each exercise is a small part with a brief, the design file, a preview and review notes.

Goal: learn the sketch → constrain → feature → parameter workflow, coming from a graphic-design background (Illustrator), with a view toward physical AI and robotics hardware.

## Exercises

| # | Part | Skills | Status |
|---|------|--------|--------|
| 01 | [Mounting plate](01-plate/) | sketch, constraints, named parameters, extrude, fillet, holes | in progress |

## Layout

```
NN-name/
  README.md   brief and acceptance checks
  *.sc        SolidCraft design
  *.png       preview
```

## Opening the files

Install SolidCraft and open any `.sc` file, or inspect from the terminal:

```sh
solidcraft-cli eval 01-plate/01-plate.sc
```

## License

MIT
