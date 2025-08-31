---
title: Resources
permalink: /resources/
---

**Machine Learning**
- 机器学习入门，[吴恩达课程](https://www.bilibili.com/video/BV1owrpYKEtP/?spm_id_from=333.337.search-card.all.click)
- 卷机神经网络，[吴恩达课程](https://www.bilibili.com/video/BV1Rf4y1b7NP?spm_id_from=333.788.videopod.episodes)
- Transformer详解，[tutor](https://www.bilibili.com/video/BV1v3411r78R?spm_id_from=333.788.videopod.episodes)

**Quantum Many Body Physics**
- [Mahan](../books/Mahan2000_Book_Many-ParticlePhysics.pdf)


**Install Quantum expresso with wannier90**
- install lapack
- prepare QE library
- tar -xzvf qe-7.4.1.ReleasePack.targ.gz
- ./configure --prefix=/path-to-QE/qe-7.4.1/build
- cd external
- mkdir lapack
- cd lapack
- cp /path-to-lapack-lib/* .
- cd ../../
- make all
- make install
- find applications in /build/bin
- [how to calculate projected band structure](https://pranabdas.github.io/espresso/hands-on/wannier/) 