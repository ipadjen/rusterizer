# Rusterizer

Convert 3D geometries to a 2D raster.

### Data formats
Input: Wavefront OBJ

Output: [Esri ASCII](https://en.wikipedia.org/wiki/Esri_grid)

### Compilation
Download the repository and do

```
cargo build --release
```

Access the executable by typing

```
./target/release/rusterizer
```

You can get Cargo [here](https://www.rust-lang.org/tools/install).

### Usage
```rusterizer -i <input> -o <output> <cellsize>```, e.g. ```rusterizer -i input.obj -o output.asc 0.5```


