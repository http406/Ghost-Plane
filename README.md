# Ghost-Plane

### **What is the Ghost Plane?**  
The **Ghost Plane** is a fascinating 3D parametric surface that emerges from mathematical transformations involving hyperbolic and trigonometric functions. It appears as a complex and mesmerizing structure, resembling ghostly, intertwined loops. The shape arises from a carefully constructed equation that maps a two-dimensional domain \((u, v)\) onto a three-dimensional surface.

This surface is mainly studied in **differential geometry** and **mathematical visualization**, where it exhibits interesting properties such as singularities and self-intersections.

---

### **Understanding the Equation in the Code**  

The equation used in the code to define the **Ghost Plane Surface** is:  

\[
x = \frac{\cos(u) \sinh(v)}{\cosh(v) - \cos(u)}
\]

\[
y = \frac{\cos(u) \sin(u)}{\cosh(v) - \cos(u)}
\]

\[
z = \sin(u)
\]

#### **Breaking it Down:**
1. **Parametric Variables \( u \) and \( v \):**  
   - The equation defines a **parametric surface**, meaning that every point \((x, y, z)\) depends on two input variables: \( u \) and \( v \).  
   - These variables are mapped to a range:  
     \[
     -\pi \leq u \leq \pi, \quad -\pi \leq v \leq \pi
     \]
  
2. **Hyperbolic and Trigonometric Functions:**  
   - \( cosh(v) \) and \( sinh(v) \) are **hyperbolic functions**, similar to cosine and sine but defined for exponential growth and decay.
   - \( cos(u) \) and \( sin(u) \) are standard **trigonometric functions**.

3. **Singularities and Structure:**  
   - The denominator, **\( cosh(v) - cos(u) \)**, plays a crucial role in shaping the surface.  
   - When this denominator approaches **zero**, the equation creates points of extreme stretching or singularities, leading to intricate self-intersecting loops.
  
4. **Behavior of Each Coordinate:**  
   - **\( x \)-coordinate:** Involves a mix of cosine and hyperbolic sine, producing the surface’s **expanding and looping** behavior.  
   - **\( y \)-coordinate:** Contains a product of \( \cos(u) \) and \( \sin(u) \), influencing the **twisting motion** of the surface.  
   - **\( z \)-coordinate:** Defined purely by **\( \sin(u) \)**, which determines the **vertical oscillation** of the surface.

---

### **Why is it Called a "Ghost Plane"?**
- The surface **vanishes** in certain regions due to the denominator approaching zero, making parts of it appear "ghostly."
- The structure creates **looping, ephemeral** shapes that resemble spectral figures.
- When visualized with **thin wireframes and glowing effects**, it gives a mystical, otherworldly appearance.
