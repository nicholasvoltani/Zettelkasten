---
Date: 2023-10-07
tags:
  - physics
---
up:: [[Work (Physics)|Work]]

The work of a resultant force done upon a particle with mass $m$ equals the change of its kinetic energy. 
$$
W_L = \frac{mv_f^2}{2} - \frac{m v_i^2}{2} = \Delta K
$$
# Proof
Given a resultant force $\vec{F}_R$ acting on a particle of mass $m$, we have, from [[Newton's Second Law]] that $\vec{F}_R = \frac{d\vec{p}}{dt} = m \frac{d\vec{v}}{dt}$.

From the definition of [[Work (Physics)|Work]], we have that
$$
W = \int_L \vec{F}_R \cdot d\vec{l} = \int_{t_0}^{t_1} \vec{F}_R \cdot \vec{v} \, dt = \frac{m}{2} \int_{t_0}^{t_1} \frac{d(\vec{v} \cdot \vec{v})}{dt} dt = \frac{mv_f^2}{2} - \frac{m v_i^2}{2}
$$
