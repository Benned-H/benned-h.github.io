---
layout: page
title: "Task and Skill Planning"
description: "Hierarchical Robot Planning with Black-Box Skills"
permalink: /tasp/
nav: false
---

<div class="text-center mt-2 mb-4">
  <h4 class="text-muted">ICRA 2026 &nbsp;·&nbsp; Vienna, Austria</h4>

  <p class="mt-3">
    <a href="/">Benned Hedegaard</a><sup>*,1</sup>&ensp;
    Yichen Wei<sup>*,1</sup>&ensp;
    Ziyi Yang<sup>1</sup>&ensp;
    Ahmed Jaafar<sup>1</sup>&ensp;
    <a href="https://cs.brown.edu/people/stellex/">Stefanie Tellex</a><sup>1</sup>&ensp;
    <a href="https://cs.brown.edu/people/gdk/">George Konidaris</a><sup>1</sup>&ensp;
    Naman Shah<sup>1,2</sup>
  </p>
  <p class="text-muted small">
    <sup>1</sup>Department of Computer Science, Brown University &nbsp;&nbsp;
    <sup>2</sup>Allen Institute for AI &nbsp;&nbsp;
    <sup>*</sup>Equal contribution
  </p>

  <div class="mt-3">
    <a href="/assets/pdf/TASP-ICRA-2026.pdf" class="btn btn-sm btn-outline-dark me-2" target="_blank">
      <i class="fas fa-file-pdf"></i> &nbsp;Paper
    </a>
    <a href="#bibtex" class="btn btn-sm btn-outline-dark">
      <i class="fas fa-quote-right"></i> &nbsp;BibTeX
    </a>
  </div>
</div>

---

## Abstract

Task and motion planning (TAMP) is a well-established approach for solving long-horizon robot planning problems. Although TAMP methods have historically assumed that each task-level robot action, or skill, can be reduced to kinematic motion planning, recent work has explored integrating closed-loop controllers and learned skills into TAMP-style systems.

Our approach integrates pre-existing, heterogeneous robot skills - including learned, force-controlled, and black-box policies - into a hierarchical planner while preserving the object-centric failure reasoning of typical TAMP solvers. We leverage **Composable Interaction Primitives (CIPs)** to synthesize head and tail motion plans bridging consecutive skills, facilitating both planning-time refinement and execution-time adjustment.

We validate our ****Task and Skill Planning (TASP)** approach through real-world experiments on a bimanual manipulator and a mobile manipulator, demonstrating that CIPs enable diverse robots to combine heterogeneous skills to solve complex, long-horizon tasks, including multi-room mobile manipulation problems with non-monotonic task structure.

---

## BibTeX

```bibtex
@inproceedings{hedegaard2026tasp,
  title     = {Task and Skill Planning: Hierarchical Robot Planning with Black-Box Skills},
  author    = {Hedegaard, Benned and Wei, Yichen and Yang, Ziyi and Jaafar, Ahmed
               and Tellex, Stefanie and Konidaris, George and Shah, Naman},
  booktitle = {Proceedings of the IEEE International Conference on Robotics and Automation (ICRA)},
  year      = {2026}
}
```

---

## Acknowledgments

This work was supported by ONR REPRISM MURI N00014-24-1-2603, ONR grant 00014-22-1-2592, and the Robotics and AI Institute (RAI).
