# robochart-normalisation

### Repository and projects' structure.

This repository is structured as follows. 

The project `normalisationRC` contains the Epsilon transformation rules, organized by purpose into folders `normalisation`, `openstm` and `packages`.

```
normalisationRC [Epsilon model-to-model transformation]
|
+--- erules (containing Epsilon programs)
|  |
|  +-- normalization (rules for normalisation in RoboChart)
|  +-- openstm (rules for extracting and manipulating OpenStateMachines)
|  +-- packages (rules for cloning RoboChart modules and packages)
|
+-- scripts (containing ANT scripts)
```

## Transformations

As discussed above, the Epsilon rules are stored in the folder `erules` of the project `normalisationRC`. Currently, Epsilon programs are invoked using ANT scripts defined in the folder `scripts`.




