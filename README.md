# Discrete-Mathematics-Project
1st year student project at Habib University

## Problem Statement: How to Optimize Art Gallery Security with Minimum Guards

**Overview**

The art gallery security problem revolves around determining the minimum number of guards required to observe the entire gallery. To achieve effective observation, guards should be strategically placed to cover all points within the gallery without their lines of sight being obstructed. This problem can be visualized as a polygon, where each vertex represents a guard position.

**Chvátal's Art Gallery Theorem**

Chvátal's art gallery theorem provides valuable insights into solving this problem. It states that for a simple polygon with n vertices, a minimum of n/3 guards are always sufficient and may sometimes be necessary. Fisk's proof, using the 3-coloring method, demonstrates that dividing the polygon into triangles and assigning three colors to the vertices allows us to determine the minimum and maximum number of guards required. With three colors utilized, at least n/3 guards will be necessary.

**Boundary Guards vs. Exterior Guards**

If guards are positioned solely along the boundary of the polygon, a minimum of ⌈n/2⌉ guards are sometimes necessary and always sufficient. However, if guards are allowed to be placed anywhere outside the polygon, then ⌈n/3⌉ guards are sometimes necessary and always sufficient. This indicates that covering the infinite space outside the polygon poses a greater challenge than covering the finite space inside it.

**Approximation Algorithms**

Due to the difficulty of finding an exact solution, mathematicians have developed algorithms to approximate the minimum number of guards required. These algorithms employ various techniques to make the best estimate, but they have inherent limitations. These approaches help identify the most optimal guard positions, considering the given constraints and available information.

**Variations and Solutions**

The art gallery problem features several variations, including scenarios where a specific number of guards, k, are given, and the task is to determine if it's possible to guard the polygon with k or fewer guards. Solving these variations may differ in complexity, and mathematicians have devised efficient algorithms to find the minimum number of vertex guards required.

**Conclusion**

In conclusion, the art gallery problem poses a challenging task with diverse variations and approaches to its solution. Optimizing art gallery security requires strategically placing guards while considering different constraints. Mathematicians continue to explore innovative techniques and algorithms to address this problem effectively. By minimizing the number of guards needed, we can achieve efficient security measures for art galleries and similar spaces.

