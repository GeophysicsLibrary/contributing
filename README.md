# Lesson Guidelines for the Geophysics Library

The goal of the Geophysics Library project is to provide open modular
computational lessons for various topics in geophysics:

**Open**: All lesson material (including data and code) should be free to use
and available under permissive licenses (CC-BY, MIT, BSD, etc). Our goals is to
not only enable widespread use of this material, but also to encourage the
community to help develop and maintain it.

**Modular**: Lessons/activities should be designed to be taught in a single
session (~1-3 hours) and cover a specific topic (e.g., a case study, regional
isostasy models, etc). This maximizes the usability of the material across
different courses, which can vary a lot depending on instructor
preferences/styles.

**Computational**: Lessons should involve some form of computation that
students can follow and/or perform for themselves (implementing a model,
plotting a dataset, etc). Knowledge is easily accessible through internet
searches and text books. But open-source computational tools enable students
to *put their knowledge into practice* through interactive exploration and
looking at real world data.

## Lesson types

Our lessons that fall under these main categories:

1. **Core concepts**: Exploring a geophysical concept from the point of view of
   available data, models, geologic/geodynamic context, etc. *Examples:
   apparent resistivity in ERT surveys, upward continuation of potential field
   data, linear inversion, cooling of the oceanic lithosphere.*
2. **Case studies**: An example of using geophysics to understand the world (or
   *a* world). Can be taken from the literature or exploring a particular
   application that illustrates a core concept. Ideally, case studies should
   use open data and open-source software. *Examples: lithospheric flexure in
   Hawai'i from bathymetry and gravity anomalies, reproducing results from a
   paper or textbook using open tools/data.*
3. **Tutorials**: How to use an open-source tool to accomplish a task. These
   lessons would focus on teaching the tool rather than teaching the concepts
   behind it (which would ideally be done in a *core concepts* lesson).
   *Examples: loading seismic data with `segyio`, DC resistivity inversion with
   `SimPEG`, Euler deconvolution with `harmonica`.

TODO:

* Layout lesson design
* How to contribute a lesson
* Technologies

## License

You are free to reuse, share, and modify the contents of this lesson under the
terms of the Creative Commons Attribution 4.0 license and the BSD-3-clause
license (see [LICENSE.md](LICENSE.md) for details).
