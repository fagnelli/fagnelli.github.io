---
layout: archive
title: "Research"
permalink: /research2/
author_profile: true
---

## Level set topology optimization for the design of metamaterials

<p style="text-align: justify;"> Present day additive manufacturing techniques permit the rapid processing of three-dimensional objects, imparted with a microarchitecture of unprecedented complexity, for several types of materials (e.g., metal alloys, ceramics, polymers), at different scales and at a continuously decreasing cost. The ability to control the microstructure's geometry via the manufacturing process offers exciting opportunities to further program the materials' response. Starting from elementary arrangements of material in a designed representative cell, complex structures can be obtained either by periodic tessellation or by spreading the cells to obtain a desired macroscopic distribution of properties. Yet, the high expectations of printing technologies and of achitectured sheets' structural applications raise a series of challenges in their design: </p>
- Optimal shape design, i.e., finding the material distribution (or pattern) yielding the desired set of properties;
- Influence of process parameters on the final structure and on its response.

<p style="text-align: justify;">
The works of my thesis propose a systematic procedure to synthesize the elementary cell for periodic architectured thin sheets. This study is placed within the framework of materials with linear elastic behaviors and relies on asymptotic homogenization, and topology optimization with the level set method. Periodic sheets are characterized by a thickness, and a elementary pattern length (denoted by period), both being small with respect to the other characteristic dimensions. For a given material distribution inside the representative cell, the macroscopic mechanical response can be numerically approximated using asymptotic homogenization. The macroscopic behavior associated to the sheets response is obtained according to the cell's aspect ratio, i.e. the ratio r between the thickness and the period (Fig. 1). More specifically:
</p>
- <p style="text-align: justify;">When the thickness of the sheet is small with respect to the period (r ≪ 1), the unit cell features a two-dimensional pattern, hence the characterization of the in-plane behavior is sufficient to describe the sheets' three-dimensional response. In particular, the flexural response can be retrieved from the in-plane behavior.</p>
- <p style="text-align: justify;">When the thickness is comparable to the period (r ~ 1), the unit cell is a cuboid featuring a volume material distribution, hence the in-plane and out of the plane response can be programmed independently. Moreover, an extension–bending coupling can appear during the deformation. Patterned sheets featuring these characteristics are referred to as panels.</p>

<img src='/images/architectured-sheet.png'>

<p style="text-align: justify;">
The two above configurations offer distinct performances that can be harnessed in different application. Therefore, the investigations on their design and characterization have been conducted in the two separate sections, that can be read independently.
</p>

### Design of 3D printable architectured thin sheet materials (r ≪ 1)

The first aspect of the thesis focused on the systematic design cycle for several auxetic thin sheet materials. The term auxetic indicates materials with a negative Poisson's ratio, i.e. materials which tend to expand transversely to an applied uniaxial stretching load and vice versa. This property is obtained from deformation mechanisms at the level of the internal microstructure when loaded. Moreover, it is often associated to other interesting properties, such as enhanced stiffness and energy absorption capabilities, indentation resistance, fracture toughness, making auxetic materials suitable in targeted applications [10].

A topology optimization algorithm involving the level set method [11], the classical shape derivative and asymptotic homogenization permits to synthetize a microstructure within the unit cell given a prescribed effective elasticity stiffness tensor that controls the Poisson's ratio(s). The material design problem is formulated to minimize the norm of the difference between a specified target and the effective elastic stiffness tensor. In contrast to a raster discretization of the standard density-based approaches, the level set model precisely captures the interfacial boundaries naturally and performs topological changes accurately. The efficiency of the resolution method is illustrated through four numerical examples where the designed shape gives a significant negative Poisson's ratio. Remarkably, some of the optimal shapes obtained are in fact microstructures already well known in the literature.

The space of admissible elastic tensors associated to two-dimensional microstructures carrying the orthotropic material symmetry is identified using the bounds of Milton and Kohn [12]. The analysis reveals that it is possible to attain shapes with orthotropic symmetri es exhibiting an effective Poisson's ratio lower than -1 in one direction (Fig. 2).

### Design of 3D printable thin composite panels (r ~ 1)

The second part is devoted to the study of composite panels featuring an extension–bending coupling mechanism, which can be harnessed to manufacture panels that change shape. Materials that change their shape in response to external stimuli open up new prospects for efficient and versatile design and shaping of three-dimensional objects.

Building upon our previous work, we devise a topology optimization procedure to the case of elastic panels in order to control their macroscopic behavior, simultaneously taking into account in-plane stiffness, out-of-plane stiffness and extension–bending coupling effects. The procedure combines inverse homogenization, Hadamard shape derivative and a level set method to systematically capture boundaries within the unit cell the optimal microarchitecture.

The efficiency of the solution method is illustrated through four numerical examples where the designed shape gives an important extension–flexion coupling. The strain responses under tensile load are numerically evaluated on both the complete periodic panel and its homogenized twin plate. The results demonstrate that the simultaneous control of the in-plane, out-of-plane and their coupled behavior can transform a flat panel into a domed or saddle-shaped structure (Fig. 6). We note that the microstructure can be tailored can exhibit significant changes in curvature depending on the loading direction. Moreover, the obtained unit cells are elementary blocks to create directly 3D printable objects with shape morphing capabilities.