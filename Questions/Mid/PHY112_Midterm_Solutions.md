# PHY 112 — Principles of Physics II
## Mid Term Examination Solutions — Spring Semester 2026

**Constants used:**
- $k = \frac{1}{4\pi\epsilon_0} = 8.99 \times 10^9\ \text{N·m}^2\text{C}^{-2}$
- $\epsilon_0 = 8.85 \times 10^{-12}\ \text{C}^2\text{N}^{-1}\text{m}^{-2}$

---

## Question 1

**Given:**
- $q_1 = -4.0\ \mu\text{C}$, $q_2 = +4.0\ \mu\text{C}$ on the $y$-axis
- Both charges are 70 cm from point P on the $x$-axis
- The line from each charge to P makes an angle of **31°** with the $x$-axis

### Part (a) — Net Electric Field $\vec{E}$ at point P (4 marks)

**Distance from each charge to P:**
$$r = 70\ \text{cm} = 0.70\ \text{m}$$

**Magnitude of electric field from each charge:**
$$E = k\frac{|q|}{r^2} = (8.99 \times 10^9) \times \frac{4.0 \times 10^{-6}}{(0.70)^2}$$
$$E = \frac{8.99 \times 10^9 \times 4.0 \times 10^{-6}}{0.49} = 7.34 \times 10^4\ \text{N/C}$$

**Directions of the electric fields:**

- $\vec{E}_1$ (from $q_1 = -4.0\ \mu\text{C}$): points **toward** $q_1$ (upper left), so it points up and to the left — its $x$-component is negative and $y$-component is positive... 

  Wait — $q_1$ is negative, so the field at P points **toward** $q_1$ (upward along the dashed line):
  $$E_{1x} = -E\cos(31°),\quad E_{1y} = +E\sin(31°)$$

- $\vec{E}_2$ (from $q_2 = +4.0\ \mu\text{C}$): points **away** from $q_2$ (lower right → upward-right from P's perspective... actually away from $q_2$ which is below P), so it points downward from P:
  $$E_{2x} = -E\cos(31°),\quad E_{2y} = -E\sin(31°)$$

**Summing components:**

$$E_x = E_{1x} + E_{2x} = -E\cos(31°) - E\cos(31°) = -2E\cos(31°)$$
$$E_y = E_{1y} + E_{2y} = +E\sin(31°) - E\sin(31°) = 0$$

**Net field (magnitude and direction):**
$$|\vec{E}_{net}| = 2E\cos(31°) = 2 \times 7.34 \times 10^4 \times \cos(31°)$$
$$= 2 \times 7.34 \times 10^4 \times 0.857 = 1.26 \times 10^5\ \text{N/C}$$

The field points in the **negative $x$-direction:**
$$\boxed{\vec{E}_{net} = -1.26 \times 10^5\ \hat{i}\ \text{N/C}}$$

---

### Part (b) — Net Electric Potential $V$ at point P (3 marks)

Electric potential is a **scalar** quantity:
$$V = k\frac{q_1}{r_1} + k\frac{q_2}{r_2}$$

Both charges are at the same distance $r = 0.70\ \text{m}$:
$$V = \frac{k}{r}(q_1 + q_2) = \frac{8.99 \times 10^9}{0.70} \times [(-4.0 \times 10^{-6}) + (+4.0 \times 10^{-6})]$$

$$\boxed{V = 0\ \text{V}}$$

The equal and opposite charges cancel exactly, so the net potential at P is zero.

---

### Part (c) — Potential Energy of the System with $q_o$ at P (4 marks)

$q_o = +8.0\ \mu\text{C}$ is placed at point P.

The total potential energy of the three-charge system has three pairwise contributions:

**1. Interaction between $q_1$ and $q_2$:**

Distance between $q_1$ and $q_2$: since each is 70 cm from P at 31° above and below the $x$-axis:
$$d_{12} = 2 \times r\sin(31°) = 2 \times 0.70 \times 0.515 = 0.721\ \text{m}$$

$$U_{12} = k\frac{q_1 q_2}{d_{12}} = \frac{8.99 \times 10^9 \times (-4.0 \times 10^{-6})(+4.0 \times 10^{-6})}{0.721}$$
$$U_{12} = \frac{8.99 \times 10^9 \times (-16 \times 10^{-12})}{0.721} = \frac{-0.1438}{0.721} = -0.1995\ \text{J}$$

**2. Interaction between $q_1$ and $q_o$:**
$$U_{1o} = k\frac{q_1 q_o}{r} = \frac{8.99 \times 10^9 \times (-4.0 \times 10^{-6})(+8.0 \times 10^{-6})}{0.70}$$
$$U_{1o} = \frac{-287.68 \times 10^{-3}}{0.70} = -0.4110\ \text{J}$$

**3. Interaction between $q_2$ and $q_o$:**
$$U_{2o} = k\frac{q_2 q_o}{r} = \frac{8.99 \times 10^9 \times (+4.0 \times 10^{-6})(+8.0 \times 10^{-6})}{0.70}$$
$$U_{2o} = +0.4110\ \text{J}$$

**Total potential energy:**
$$U_{total} = U_{12} + U_{1o} + U_{2o} = -0.1995 + (-0.4110) + 0.4110$$

$$\boxed{U_{total} = -0.1995\ \text{J} \approx -0.20\ \text{J}}$$

---

## Question 2

**Given:**
- $v_0 = 7 \times 10^6\ \text{m/s}$ (horizontal, $x$-direction)
- Plate length $L = 2.0\ \text{cm} = 0.020\ \text{m}$
- Plate separation $d = 0.15\ \text{cm} = 1.5 \times 10^{-3}\ \text{m}$
- Vertical displacement at exit: $y = 0.15\ \text{cm} = 1.5 \times 10^{-3}\ \text{m}$
- $q_e = -1.6 \times 10^{-19}\ \text{C}$, $m_e = 9.1 \times 10^{-31}\ \text{kg}$

**Preliminary: Finding the electric field $E$ in the capacitor**

Time to traverse the capacitor horizontally:
$$t = \frac{L}{v_0} = \frac{0.020}{7 \times 10^6} = 2.857 \times 10^{-9}\ \text{s}$$

Using kinematic equation $y = \frac{1}{2}at^2$:
$$a = \frac{2y}{t^2} = \frac{2 \times 1.5 \times 10^{-3}}{(2.857 \times 10^{-9})^2} = \frac{3.0 \times 10^{-3}}{8.163 \times 10^{-18}} = 3.675 \times 10^{14}\ \text{m/s}^2$$

Electric field:
$$E = \frac{m_e \cdot a}{|q_e|} = \frac{9.1 \times 10^{-31} \times 3.675 \times 10^{14}}{1.6 \times 10^{-19}} = \frac{3.344 \times 10^{-16}}{1.6 \times 10^{-19}} = 2090\ \text{N/C} \approx 2.09 \times 10^3\ \text{N/C}$$

---

### Part (c) — Torque on the Dipole (3 marks)

**Given:** $\vec{p} = 6.2 \times 10^{-30}\ \hat{i}\ \text{C·m}$

The electric field inside the capacitor points in the $y$-direction (perpendicular to the plates). The dipole moment $\vec{p}$ points in the $\hat{i}$ (x) direction.

The angle between $\vec{p}$ and $\vec{E}$ is $\theta = 90°$.

Torque on a dipole in a uniform field:
$$\tau = pE\sin\theta = 6.2 \times 10^{-30} \times 2090 \times \sin(90°)$$
$$\tau = 6.2 \times 10^{-30} \times 2090 \times 1$$

$$\boxed{\tau = 1.30 \times 10^{-26}\ \text{N·m}}$$

---

### Part (d) — Work to Rotate Dipole by 180° (2 marks)

Work done by an external agent to rotate a dipole from angle $\theta_1$ to $\theta_2$:
$$W = \Delta U = U_f - U_i = -pE\cos\theta_2 - (-pE\cos\theta_1)$$
$$W = pE(\cos\theta_1 - \cos\theta_2)$$

Initial orientation: $\vec{p}$ is along $\hat{i}$, $\vec{E}$ is along $\hat{j}$, so $\theta_1 = 90°$.

After rotating by 180°: $\theta_2 = 90° + 180° = 270°$.

$$W = pE(\cos 90° - \cos 270°) = pE(0 - 0) = 0$$

Alternatively, using $W = 2pE\sin\theta_1\sin(\Delta\theta/2)$ for the general case, but more directly:

The potential energy is $U = -pE\cos\theta$:
- $U_i = -pE\cos(90°) = 0$
- $U_f = -pE\cos(270°) = -pE \times 0 = 0$

$$\boxed{W = 0\ \text{J}}$$

> **Note:** Because the dipole starts perpendicular to $\vec{E}$ ($\theta = 90°$), rotating it by 180° returns it to another perpendicular orientation ($\theta = 270°$), so both initial and final potential energies are zero. No net work is required.

---

## Question 3

**Given:**
- Cube with one corner at $x = 1.0\ \text{m}$, opposite corner at $x = 3.0\ \text{m}$
- Side length: $a = 3.0 - 1.0 = 2.0\ \text{m}$
- Electric field: $\vec{E} = 3.0\ \hat{i} + 4.0y\ \hat{j} + 2.0\ \hat{k}\ \ \text{N/C}$

The cube spans: $x: 1 \to 3\ \text{m}$, $y: 0 \to 2\ \text{m}$, $z: 0 \to 2\ \text{m}$ *(assuming corner at origin of cube)*

Flux through a face: $\Phi = \vec{E} \cdot \hat{n} \cdot A$, where $A = a^2 = 4\ \text{m}^2$.

---

### Part (a) — Electric Flux Through Each Face (12 marks)

#### Face 1: Left face ($x = 1.0\ \text{m}$), outward normal $\hat{n} = -\hat{i}$

Only the $\hat{i}$ component of $\vec{E}$ contributes. At $x = 1.0$, $E_x = 3.0\ \text{N/C}$ (constant, no $x$-dependence):
$$\Phi_1 = \vec{E} \cdot (-\hat{i}) \cdot A = -3.0 \times 4.0$$
$$\boxed{\Phi_1 = -12.0\ \text{N·m}^2/\text{C}}$$

#### Face 2: Right face ($x = 3.0\ \text{m}$), outward normal $\hat{n} = +\hat{i}$

$E_x = 3.0\ \text{N/C}$ (same, constant):
$$\Phi_2 = +3.0 \times 4.0$$
$$\boxed{\Phi_2 = +12.0\ \text{N·m}^2/\text{C}}$$

#### Face 3: Bottom face ($y = 0\ \text{m}$), outward normal $\hat{n} = -\hat{j}$

At $y = 0$: $E_y = 4.0(0) = 0\ \text{N/C}$:
$$\Phi_3 = E_y \cdot (-1) \cdot A = 0 \times 4.0$$
$$\boxed{\Phi_3 = 0\ \text{N·m}^2/\text{C}}$$

#### Face 4: Top face ($y = 2.0\ \text{m}$), outward normal $\hat{n} = +\hat{j}$

At $y = 2.0$: $E_y = 4.0 \times 2.0 = 8.0\ \text{N/C}$:
$$\Phi_4 = +8.0 \times 4.0$$
$$\boxed{\Phi_4 = +32.0\ \text{N·m}^2/\text{C}}$$

#### Face 5: Front face ($z = 0\ \text{m}$), outward normal $\hat{n} = -\hat{k}$

$E_z = 2.0\ \text{N/C}$ (constant, no $z$-dependence):
$$\Phi_5 = -2.0 \times 4.0$$
$$\boxed{\Phi_5 = -8.0\ \text{N·m}^2/\text{C}}$$

#### Face 6: Back face ($z = 2.0\ \text{m}$), outward normal $\hat{n} = +\hat{k}$

$E_z = 2.0\ \text{N/C}$ (same, constant):
$$\Phi_6 = +2.0 \times 4.0$$
$$\boxed{\Phi_6 = +8.0\ \text{N·m}^2/\text{C}}$$

#### Summary of Fluxes:

| Face | Normal | Flux (N·m²/C) |
|---|---|---|
| Left ($x = 1$ m) | $-\hat{i}$ | $-12.0$ |
| Right ($x = 3$ m) | $+\hat{i}$ | $+12.0$ |
| Bottom ($y = 0$ m) | $-\hat{j}$ | $0$ |
| Top ($y = 2$ m) | $+\hat{j}$ | $+32.0$ |
| Front ($z = 0$ m) | $-\hat{k}$ | $-8.0$ |
| Back ($z = 2$ m) | $+\hat{k}$ | $+8.0$ |

---

### Part (b) — Net Charge Enclosed (3 marks)

By Gauss's Law:
$$\Phi_{net} = \frac{Q_{enc}}{\epsilon_0}$$

$$\Phi_{net} = -12.0 + 12.0 + 0 + 32.0 - 8.0 + 8.0 = +32.0\ \text{N·m}^2/\text{C}$$

$$Q_{enc} = \epsilon_0 \cdot \Phi_{net} = (8.85 \times 10^{-12}) \times 32.0$$

$$\boxed{Q_{enc} = 2.83 \times 10^{-10}\ \text{C} \approx 283\ \text{pC}}$$
