# soxel
The **soxel** project  extends the notion of **pixel** and **voxel** to sound spatialization and offers a matrix based spatialization library for Pure Data.

### Features
Here is a list of the main abstraction.

#### Sound Space Synthesis
- [x] xel.2d.syn.pencil~: The abstraction synthesizes independently the signals of each soxel with one or several sound sources and depending on the coefficients of one or several matrices.

- [x] xel.2d.syn.brush~: The abstraction synthesizes the signals of the soxels with a sound source depending on coordinates like a brush that automatically erases its previous drawing at each new position.

- [x] xel.2d.syn.bucket~: The abstraction synthesizes the signals of the soxels with a sound source using variable delay lines without flanging effect. The goal is to create a spatial smudge effect.

- [x] xel.2d.syn.spray~: The abstraction synthesizes the signals of the soxels with a sound source using a quasi-synchronous granular synthesizer (QSGS). The idea is to create a spatial spray effect.

#### Sound Space Projection
- [x] xel.2d.proj.dbap~: The abstraction projects the signals of the soxels onto a set of loudspeakers using distance based amplitude panning (DBAP).

- [ ] xel.2d.proj.wfs~: The abstraction projects the signals of the soxels onto a set of loudspeakers using wave field synthesis (WFS).

#### Sound Space Transformation
- [x] xel.2d.fx.eraser~: The abstraction decreases the amplitude of the signals of a set of soxels to erase or to attenuate some parts of the sound space.

- [x] xel.2d.fx.kernel~: The abstraction applies a kernel on the sound space. Depending on the kernel, the convolution can result a wide range of effects: blur, sharpening, etc.

#### Sound Space Visualization
- [x] xel.2d.gui.scope~: The abstraction displays the rms amplitude of the signals of the soxels inside a canvas.

- [x] xel.2d.gui.meter~: The abstraction displays the contributions of a set of loudspeakers in a space.

#### Matrix Operations
- [x] xel.2d.gui.mat: The abstraction displays the coefficients of a matrix inside a canvas and allows to interact with them.

- [x] xel.2d.mat.random: The abstraction generates a matrix filled with random values. The sum of the absolutes values of the elements equals one. The matrix can be used for kernel filter.

- [x] xel.2d.mat.blur.box: The abstraction generates a matrix filled with a normalized constant value that equals one over the number of elements. The matrix can be used for kernel filter.

- [x] xel.2d.mat.blur.gaussian: The abstraction generates a matrix filled with a value generated with the gaussian function. The matrix can be used for kernel filter.

- [x] xel.2d.mat.fltr.log: The abstraction generates a matrix filled with values generated with the laplacian of gaussian. The matrix can be used for kernel filter.

- [x] xel.2d.mat.clip: The abstraction clips the values of a matrix.

- [x] xel.2d.mat.brush: The abstraction applies pattern to a matrices

- [x] xel.2d.gui.mat.brush: The abstraction facilitates the usage of patterns.

- [x] xel.2d.mat.history: The abstraction allows to save and to recall an history of matrices of coefficients.
