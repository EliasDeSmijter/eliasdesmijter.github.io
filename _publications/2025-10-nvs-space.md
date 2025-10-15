---
title: "On the Geometric Accuracy of Implicit and Primitive-Based Representations Derived From View Rendering Constraints"
collection: publications
category: conferences
permalink: /publication/2025-10-nvs-space
excerpt: 'We present the first systematic comparison of implicit and explicit Novel View Synthesis methods for space-based 3D object reconstruction, evaluating the role of appearance embeddings.'
date: 2025-10-08
venue: '18th Symposium on Advanced Space Technologies in Robotics and Automation'
paperurl: 'https://arxiv.org/pdf/2509.10241?'
# slidesurl:''
citation: 'De Smijter, Elias and Detry, Renaud and De Vleeschouwer, Christophe. (2025). &quot;On the Geometric Accuracy of Implicit and Primitive-Based Representations Derived From View Rendering Constraints.&quot; <i>18th Symposium on Advanced Space Technologies in Robotics and Automation</i>.'
---
We present the first systematic comparison of implicit and explicit Novel View Synthesis methods for space-based 3D object reconstruction, evaluating the role of appearance embeddings. While embeddings improve photometric fidelity by modeling lighting variation, we show they do not translate into meaningful gains in geometric accuracy — a critical requirement for space robotics applications. Using the SPEED+ dataset, we compare K-Planes, Gaussian Splatting, and Convex Splatting, and demonstrate that embeddings primarily reduce the number of primitives needed for explicit methods rather than enhancing geometric fidelity. Moreover, convex splatting achieves more compact and clutter-free representations than Gaussian splatting, offering advantages for safety-critical applications such as interaction and collision avoidance. Our findings clarify the limits of appearance embeddings for geometry-centric tasks and highlight trade-offs between reconstruction quality and representation efficiency in space scenarios.