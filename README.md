# Xdeptck-D3

A typechecker for assigning static semantics
to the D3-level syntax that is based on a linear dependent
type system (where the dependent types are of DML-style)

## Download

```
git clone --recursive https://github.com/xanadu-lang/Xdeptck-D3.git
```

## Prerequisites

ATS2-0.4.0 or a later version is required,
which is available [here](http://www.ats-lang.org/Downloads.html)

## Build with ATS2

```
(cd Xdeptck-D3 && sh build.sh)
```

## Testing

```
cd Xdeptck-D3
./bin/xdeptck -h
make -C srcgen/TEST test > output
```

## Remarks

- Xdeptck-D3 is for supporting a form of static debugging based on
  the notion of linear dependent types of DML-style.

- This project should be constantly under construction for quite some time
