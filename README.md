# soxel
The **soxel** project  extends the notion of **pixel** and **voxel** to sound spatialization and offers a matrix based spatialization library for Pure Data.

### Features

#### Synthesis
- [x] xel.2d.syn.pencil~: The abstraction synthesizes independently the signals of each soxel with one or several sound sources and depending on the coefficients of one or several matrices.

- [x] xel.2d.syn.brush~: The abstraction synthesizes the signals of the soxels with a sound source depending on coordinates like a brush that automatically erases its previous drawing at each new position.

- [x] xel.2d.syn.bucket~: The abstraction synthesizes the signals of the soxels with a sound source using variable delay lines without flanging effect. The goal is to create a spatial smudge effect.

- [x] xel.2d.syn.spray~: The abstraction synthesizes the signals of the soxels with a sound source using a quasi-synchronous granular synthesizer (QSGS). The idea is to create a spatial spray effect.

#### Projection

- [x] xel.2d.proj.dbap~: The abstraction projects the signals of the soxels onto a set of loudspeakers using distance based amplitude panning (DBAP).

- [ ] xel.2d.proj.wfs~: The abstraction projects the signals of the soxels onto a set of loudspeakers using wave field synthesis (WFS).

#### Transformation

- [x] xel.2d.fx.eraser~: The abstraction decreases the amplitude of the signals of a set of soxels to erase or to attenuate some parts of the sound space.

- [x] xel.2d.fx.kernel~: The abstraction applies a kernel on the sound space. Depending on the kernel, the convolution can result a wide range of effects: blur, sharpening, etc. 
