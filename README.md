# singularity-hyperfine
Singularity recipe for [hyperfine](https://github.com/sharkdp/hyperfine).

## Installing the container on Bridges 2
Copy the

* `SIF` file
* and the `hyperfine` script

to `/opt/packages/hyperfine/1.11.0`.

Copy the file `modulefile.lua` to `/opt/modules/hyperfine` as `1.11.0`.

## Building the image using the recipe

### To build the image locally
Run the script `build.sh` to build image locally

```
bash ./build.sh
````

### To build the image remotely
Run the script `rbuild.sh` to build image remotely

```
bash ./rbuild.sh
```

## To run tests
To run the available tests, run the command

```
bash ./test.sh
```

---
Copyright © 2020-2021 Pittsburgh Supercomputing Center. All Rights Reserved.

[icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Pittsburgh Supercomputing Center](http://www.psc.edu) in the [Mellon College of Science](https://www.cmu.edu/mcs/) at [Carnegie Mellon University](http://www.cmu.edu).
