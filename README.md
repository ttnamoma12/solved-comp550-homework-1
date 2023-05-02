Download Link: https://assignmentchef.com/product/solved-comp550-homework-1
<br>
<strong>Algorithmic Robotics</strong>







Please read the honor code and the additions described in the course syllabus. Present your work and your work only. You must <em>explain </em>all of your answers. Answers without explanation will be given no credit.

<ol>

 <li>(20 points) Describe two trade-offs between the Bug 1 and Bug 2 algorithms. Limit your response to no more than half a page.</li>

 <li>(30 points) Suppose you are planning for a point robot in a 2D workspace with polygonal obstacles. The start and goal locations of the robot are given. The visibility graph is defined as follows:

  <ul>

   <li>The start, goal, and all vertices of the polygonal obstacles compose the vertices of the graph.</li>

   <li>An edge exists between two vertices of the graph if the straight line segment connecting the vertices does not intersect any obstacle. The boundaries of the obstacles count as edges.</li>

  </ul></li>

</ol>

Answer the following questions:

<ul>

 <li>(15 points) Provide an upper-bound of the time it takes to construct the visibility graph in big-O notation. Give your answer in terms of <em>n</em>, the total number of vertices of the obstacles. Provide a short algorithm in pseudocode to explain your answer. Assume that computing the intersection of two line segments can be done in constant time.</li>

 <li>(15 points) Can you use the visibility graph to plan a path from the start to the goal? If so, explain how and provide or name an algorithm that could be used. Provide an upper-bound of the run-time of this algorithm in big-O notation in terms of <em>n </em>(the number of vertices in the visibility graph) and <em>m </em>(the number of edges of the visibility graph). If not, explain why.</li>

</ul>

<ol start="3">

 <li>(20 points) Let A be a unit disc centered at the origin in a workspace W =R<sup>2</sup>. Assume that A is represented by a single algebraic primitive <em>H </em>= { (<em>x</em><em>,y</em>) | <em>x</em><sup>2</sup>+<em>y</em><sup>2 </sup>≤ 1 }. Show that if this primitive is rotated about the origin that the transformed primitive is unchanged. This can be shown by showing that any point within the transformed primitive <em>H</em><sup>0 </sup>must be within <em>H</em>, and vice versa.</li>

 <li>(30 points) You are given the endpoints to two line segments, <em>A</em><sub>1</sub><em>B</em><sub>1 </sub>and <em>A</em><sub>2</sub><em>B</em><sub>2</sub>, in a 2D workspace. The line segments include their endpoints. Provide an algorithm in pseudocode to compute the intersection points of these two line segments, if one exists. Be careful and consider all corner cases. Your algorithm must provide the correct output with every input. Hint: There are many ways to represent line segments. Choosing wisely will allow for a shorter and more efficient implementation.</li>

</ol>