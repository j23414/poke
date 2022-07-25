# poke

This repo is a ramp up into a regular programming cadence. Delete this later. 

YAPL = Yet Another Programming Language

## Rust

### Data Types

The data types in Rust are memory aware, a nice departure from the dynamic typed languages. 

* https://doc.rust-lang.org/book/ch03-02-data-types.html

**Scalar Types**

```
// 1) Integers; 2) Floats; 3) Booleans; 4) Characters 
let i: u8 = "1_000".parse().expect("Not a unsigned integer with 8 bits")
```

`let` `varname`: `datatype with memory size` `=` `value`.`parse().expect("Exception statement")`

The `let` statements is giving me Haskel vibes.

If a value is assigned outside of a variable's memory range, it will panic during debug mode, but wrap around during release mode. Ergo it is standard to write a `wrapping_` , `overflowing_*`, ... methods. This may make it easier cover common edge cases by default.

**Compound Types**


```
// Tuples
let tup: (i32, f64, u8) = (500, 6.4, 1); 
```

The explicit types is kinda slick in that a programmer/reviewer can immediately see that `tup` takes up `32+64+8=104` bits of memory.

#### Functions

```
fn main() {
  
}
```



