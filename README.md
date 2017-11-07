# soxel
The **soxel** project  extends the notion of **pixel** and **voxel** to sound spatialization and offers a matrix based spatialization library for Pure Data.

### Features

#### Synthesis
- xel.2d.syn.pencil~: The abstraction synthesizes independently the signals of each soxel with one or several sound sources and depending on the coefficients of one or several matrices.

- xel.2d.syn.brush~: The abstraction synthesizes the signals of the soxels with a sound source depending on coordinates like a brush that automatically erases its previous drawing at each new position.

- xel.2d.syn.bucket~: The abstraction synthesizes the signals of the soxels with a sound source using variable delay lines without flanging effect. The goal is to create a spatial smudge effect.

- xel.2d.syn.spray~: The abstraction synthesizes the signals of the soxels with a sound source using a quasi-synchronous granular synthesizer (QSGS). The idea is to create a spatial spray effect.
