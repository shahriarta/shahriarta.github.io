---
layout: page
title: Computer Programming with Python
description: Computer Programming with Python M 20 P (Fall 2025 @ UCLA)
img: /assets/img/teachings/CP.png
importance: 1
category: current courses
---

<div class="row">
  <div class="col-md-8">
   <p indent="2em">
  An introduction to <b>computer programming and computational thinking</b> with a focus on the <b>Python 3 language</b>. The course starts from first principles—variables, branching, loops—and advances to object-oriented design, algorithmic efficiency, and practical software engineering techniques such as testing and debugging. Key programming concepts include basic data types, control structures, input/output, functions, recursion, and object-oriented programming with an emphasis on Python-based data structures, writing efficient, modular code and testing/debugging techniques.
  <br>
   </p>
  </div>
  <div class="col-md-4">
    {% include figure.html path="/assets/img/teachings/CP.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>


Examples and exercises are drawn from engineering, mathematics, and the physical sciences to ground abstract concepts in real-world problem solving. Instruction blends mini-lectures, live-coding sessions, and hands-on exercises to ensure students leave each class with runnable code and a clear mental model of how it works. Time permitting, a brief module on <b>ethics, reproducibility, and responsible AI/tool use</b> will be included.
<br><br>


<!-- ===== Course Logistics ===== -->
<p style="font-size:15pt"><b>Course Logistics</b></p>
<ul>
  <li><strong>Instructor:</strong> Dr. Shahriar Talebi, <a href="mailto:s.talebi@ucla.edu">s.talebi@ucla.edu</a></li>, office: Eng IV, 38-137F
  <li><strong>Teaching Assistant:</strong> Yasamin Foroutani, <a href="mailto:yforoutani@g.ucla.edu">yforoutani@g.ucla.edu</a> </li>
  <li>
    <strong>Office Hours:</strong>
    TBA | <a href="https://zoom-link">Zoom</a><br>
    <!-- Q&amp;A hosted on <a href="https://piazza.com/instructors/ucla#">Piazza</a> -->
  </li>
  <li>
    <strong>Structure &amp; Workload:</strong><br>
    Lecture · 2 h&nbsp;/ week | Discussion · 2 h&nbsp;/ week | Laboratory · 2 h&nbsp;/ week | Outside study · ≈ 6 h&nbsp;/ week
  </li>
  <li><strong>Prerequisite:</strong> Mathematics 33A</li>
  <li><strong>Grading:</strong> Letter</li>
  <li><strong>Class Time:</strong> Thursdays 4pm-5:50pm &amp; Wednesdays 8am-9:50am </li>
  <li><strong>Class Location:</strong> Kinsey Science Teaching Pavilion 1220B (in person)
  </li>
  <li><strong>Laboratory Time:</strong> Thursdays 4pm-5:50pm &amp; Wednesdays 12pm-1:50pm </li>
  <li><strong>Laboratory Location:</strong> Boelter Hall 4404 </li>
</ul>

<!-- ===== Course Websites ===== -->
<p style="font-size:15pt"><b>Course Websites</b></p>
<ul>
  <li>Main site: <a href="https://shahriarta.github.io/teachings/computer_programming" target="_blank">shahriarta.github.io/teachings/computer_programming</a></li>
  <li>Canvas: Lecture slides; Homework and excercise submissions</li>
</ul>

<!-- ===== Texts & References ===== -->
<p style="font-size:15pt"><b>Main Texts &amp; References</b></p>
<ol>
  <li>
    <a href="https://allendowney.github.io/ThinkPython/" target="_blank">
      <em>Think&nbsp;Python</em> (3rd ed.) – Allen Downey (Free Online)
    </a>
  </li>
  <li>
    <a href="https://search.library.ucla.edu/permalink/01UCS_LAL/17p22dp/alma9996708890906533" target="_blank">
      <em>Introduction to Computation &amp; Programming Using Python</em> – John Guttag
    </a>
  </li>
</ol>

<!-- ===== Other Texts & References ===== -->
<p style="font-size:15pt"><b>Other Texts &amp; Broader references (Mostly Free Online)</b></p>
<ol>
  <li>
    <a href="https://www.scribd.com/document/317302777/How-To-Solve-It-George-Polya-pdf" target="_blank">
      <em>How to Solve It</em> - George Pólya
    </a> (Read <a href="/assets/pdf/teach_cp/problem_solving_polya.pdf">this summary</a>!)
  </li>
    <li>
    <a href="https://search.library.ucla.edu/permalink/01UCS_LAL/17p22dp/alma9953637143606533" target="_blank">
      <em>Numerical Methods in Engineering with Python</em> - Jaan Kiusalaas
    </a>
  </li>
  <li>
    <a href="https://jakevdp.github.io/PythonDataScienceHandbook/" target="_blank">
      <em>Python Data Science Handbook</em> (2nd ed.) – Jake VanderPlas
    </a>
  </li>
  <li>
    <a href="https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/" target="_blank">
      <em>Introduction To Computer Science And Programming In Python</em> - MIT OpenCourseWare
    </a>
  </li>
</ol>

<table style="width:100%" border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr><th colspan="7"><p style="font-size:20pt">Course Schedule (Tentative)</p></th></tr>
    <tr>
      <th>Date</th>
      <th>Topic</th>
      <th>Lab</th>
      <th>Exercises<br>(Think Python 3e)</th>
      <th>Prerequisite</th>
      <th>Lecture notes/slides*</th>
      <th>Resources / Extra Reading</th>
    </tr>
  </thead>
  <tbody>
  <!-- 1 -->
  <tr>
    <th>Week 1</th>
    <td>Course logistics • Programming mindset<br><strong>Syntax, variables, types, operators, Basic I/O, code style</strong></td>
    <td>Variables &amp; control-flow drill + mini-debug (<code>pdb</code> watch-list) <em>Numerical tie-in:</em>  <b>NumPy warm-up</b>: Gaussian elimination; condition number &amp; least-squares</td>
    <td>Ch 01 &amp; 02</td>
    <td>Math 33A</td>
    <td></td> 
    <td>
      <strong>Guttag Ch 1 </strong>; Kiusalaas Ch 1<br>
      <a href="https://docs.python.org/3/tutorial/" target="_blank">Python tutorial (official)</a>,<br>
      <a href="https://peps.python.org/pep-0008/" target="_blank">PEP 8 style guide</a>,<br>
      <a href="https://www.alanturing.net/turing_archive/pages/reference%20articles/Turing%27s%20O-Machines.html" target="_blank">Turing Machine</a>,<br>
      <a href="https://realpython.com/python-bitwise-operators/" target="_blank">Bitwise Operators in Python</a>
    </td>
  </tr>

  <!-- 2 -->
  <tr>
    <th>Week 2</th>
    <td>Branching and conditionals, loops, ranges; Comparison/Boolean Operators; Data structures: lists, tuples; <strong>list comprehensions</strong></td>
    <td>Array exercises • Loop-based problem solving (max, sum, reverse) • Off-by-one error debugging <br><em>Numerical Methods:</em> <strong>Systems of linear algebraic equations</strong></td>
    <td>Ch 06 (Iteration) &nbsp;+ Ch 08 (Lists)<br><small>§03.12 list-comprehension *peek*</small></td>
    <td>Basic program structure</td>
    <td></td>
    <td>
      Guttag Ch 2–3; <strong>Kiusalaas Ch 2</strong><br>
      <a href="https://www.learnpython.org/" target="_blank">LearnPython.org interactive</a><br>
      <a href="https://realpython.com/python-for-loop/" target="_blank">Real Python • Loops</a><br>
      <a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank">Python docs – lists &amp; tuples</a>
    </td>
  </tr>

  <!-- 3 -->
  <tr>
    <th>Week 3</th>
    <td>Functions, scopes, *args/**kwargs, iterables, map, lambda function • <b>Testing mindset</b> (assertions &amp; pytest)<br></td>
    <td>Modular design • <b>Unit tests with <code>pytest</code></b> (assert patterns, simple fixtures) • Pair-programming warm-up • <em>Numerical Methods:</em> <strong>Interpolation and curve fitting</strong></td>
    <td>Ch 03 (Functions) &amp; Ch 05 §5.1-5.4 (Fruitful funcs)<br><small>*Skip recursion parts until L6*</small></td>
    <td>Branching &amp; loops</td>
    <td></td>
    <td>
      Guttag Ch 4 &amp; 8; <strong>Kiusalaas Ch 4</strong><br>
      <a href="https://realpython.com/defining-your-own-python-function/" target="_blank">Real Python • Defining functions</a><br>
      <a href="https://realpython.com/args-and-kwargs-python/" target="_blank">*args &amp; **kwargs explained</a><br>
      <a href="https://docs.python.org/3/library/__main__.html" target="_blank">Python docs – <code>__main__</code></a><br>
      <a href="https://realpython.com/python-testing/" target="_blank">pytest intro</a>
    </td>
  </tr>

  <!-- 4 -->
  <tr>
    <th>Week 4</th>
    <td>Recursion &amp; problem decomposition • Sorting (built-in &amp; custom) • Searching (linear / binary) • <strong>Big-O basics</strong><br></td>
    <td>Sort/search challenges + timing decorator (simple profiler) + Matplotlib multi-plot demo • <em>Numerical Methods:</em> <strong>Roots of equations</strong> (bisection, Newton)</td>
    <td>Ch 05 §5.5-5.9 (Recursion) &amp; Ch 13 §13.3-13.6 (Search &amp; Selection)</td>
    <td>Dictionaries &amp; files</td>
    <td></td>
    <td>
      Guttag Ch 11, 14–15; <strong>Kiusalaas Ch 3</strong><br>
      <a href="https://bigocheatsheet.com/" target="_blank">Big-O Cheat Sheet</a><br>
      <a href="https://www.cs.usfca.edu/~galles/visualization/Search.html" target="_blank">Visual Algo • Search animations</a><br>
      <a href="https://www.geeksforgeeks.org/python-programming-examples/" target="_blank">GfG sorting/search practice</a>
    </td>
  </tr>

  <!-- 5 -->
  <tr>
    <th>Week 5</th>
    <td>Dictionaries, sets, mutability vs hashability • Hash-based problem solving (freq maps, memoization)<br></td>
    <td>Strings review • Anagrams &amp; hashmap puzzles (with logging) • (problem selection &amp; spec) <em>Numerical Methods:</em> <strong>Numerical differentiation</strong>: finite differences; error vs. step-size</td>
    <td>Ch 07 (Strings review) &amp; Ch 09 (Dictionaries)<br>Ch 10 §10.2-10.4 (Tuples vs lists)</td>
    <td>Functions &amp; testing</td>
    <td></td>
    <td>
      Guttag Ch 5 &amp; 7; <strong>Kiusalaas Ch 5</strong><br>
      <a href="https://pythontutor.com/" target="_blank">Python Tutor visualizer</a><br>
      <a href="https://realpython.com/python-dicts/" target="_blank">Real Python • Dictionaries</a><br>
      <a href="https://realpython.com/python-sets/" target="_blank">Real Python • Sets</a>
    </td>
  </tr>

  <!-- 6 -->
  <tr>
    <th>Week 6</th>
    <td>File I/O (text, CSV, JSON) • Script execution (<code>if __name__ == "__main__"</code>) • Modules &amp; packages • <strong>Defensive programming</strong> (try/except, assertions, basic debugging)<br></td>
    <td>
      File parsing + input validation + <b>Unit testing</b> (pytest markers) • <b>Tooling:</b> VS Code/PyCharm, venv, Git/GitHub<br>
      <em>Numerical Methods:</em> <strong>Numerical integration</strong>: trapezoidal/Simpson; error vs. step-size
    </td>
    <td>Ch 11 (Files &amp; Exceptions) &amp; Ch 12 (Modules)</td>
    <td>Sequences overview</td>
    <td></td>
    <td>
      Guttag Ch 6, 8–9; <strong>Kiusalaas Ch 6</strong><br>
      <a href="https://automatetheboringstuff.com/" target="_blank">Automate the Boring Stuff – Ch 10-11</a><br>
      <a href="https://realpython.com/read-write-files-python/" target="_blank">Real Python • File I/O</a><br>
      <a href="https://matplotlib.org/stable/users/getting_started/" target="_blank">Matplotlib getting started</a><br>
      <a href="https://numpy.org/doc/stable/reference/routines.linalg.html" target="_blank">NumPy <code>linalg</code> guide</a><br>
      <a href="https://code.visualstudio.com/docs/python/python-tutorial" target="_blank">VS Code • Python</a><br>
      <a href="https://docs.python.org/3/tutorial/venv.html" target="_blank">Python <code>venv</code></a><br>
      <a href="https://git-scm.com/doc" target="_blank">Git docs</a>
    </td>
  </tr>

  <!-- 7 -->
  <tr>
    <th>Week 7</th>
    <td><strong>OOP I:</strong> Classes, constructors, encapsulation, <code>__str__</code>/<code>__repr__</code>; Data Structures I (stacks/queues/heap)<br></td>
    <td>Stack/queue/heap drills + class-based simulation (with doctest) • <b>Structured code review</b> via GitHub PRs • <em>Numerical Methods:</em> <strong>Initial value problems</strong> (ODEs): Euler &amp; RK4; compare with <code>scipy.integrate.solve_ivp</code>; stability &amp; step-size</td>
    <td>Ch 14 &amp; 15 (Classes &amp; Objects)</td>
    <td>Recursion &amp; complexity</td>
    <td></td>
    <td>
      Guttag Ch 10 &amp; 13; <strong>Kiusalaas Ch 7</strong><br>
      <a href="https://docs.python.org/3/library/heapq.html" target="_blank">heapq docs</a><br>
      <a href="https://realpython.com/python-data-structures/" target="_blank">Real Python • Stacks &amp; Queues</a><br>
      <a href="https://leetcode.com/tag/stack/" target="_blank">LeetCode stack practice</a>
    </td>
  </tr>

  <!-- 8 -->
  <tr>
    <th>Week 8</th>
    <td><strong>OOP II:</strong> Inheritance, polymorphism, abstract base classes • Graphs (adjacency lists, DFS/BFS, shortest path) • DP intro<br></td>
    <td>Graph problems (maze reachability, shortest path) + inheritance refactor • 
    • <b>Interpolation &amp; curve fitting</b> (NumPy/SciPy; OOP wrapper; residuals) • <em>Numerical Methods:</em> <b>Two-point boundary value problems:</b> shooting/finite differences
    </td>
    <td>Ch 17 (Inheritance) &amp; Ch 18 §18.1-18.3 (Simple DP)</td>
    <td>OOP concepts</td>
    <td></td>
    <td>
      Guttag Ch 12 &amp; 15; <strong>Kiusalaas Ch 8</strong><br>
      <a href="https://networkx.org/documentation/stable/" target="_blank">NetworkX docs</a><br>
      <a href="https://khanacademy.org/computing/computer-science/algorithms#graphs" target="_blank">Khan Academy • Graph intro</a><br>
      <a href="https://cp-algorithms.com/graph/" target="_blank">CP-Algorithms • Graph guide</a>
    </td>
  </tr>

  <!-- 9 -->
  <tr>
    <th>Week 9</th>
    <td><strong>Testing &amp; Debugging Deep-Dive:</strong> pytest fixtures, coverage, <code>pdb</code>, logging config, profiling; Exception hierarchies, input validation; <b>Ethics &amp; reproducibility</b><br></td>
    <td>End-to-end debugging workflow on prior homework • Responsible tool/AI usage caselets • <em>Numerical Methods:</em> <strong>Symmetric matrix eigenvalue problems</strong>: power iteration &amp; Rayleigh quotient, compare with <code>numpy.linalg.eig</code> </td>
    <td>Appendix B (Debugging) &amp; Ch 11 §11.4 (try/except)</td>
    <td>Algorithm analysis</td>
    <td></td>
    <td>
      Guttag Ch 8–9; <strong>Kiusalaas Ch 9</strong><br>
      <a href="https://realpython.com/python-debugging-pdb/" target="_blank">pdb tutorial (Real Python)</a><br>
      <a href="https://docs.python.org/3/howto/logging.html" target="_blank">Logging How-To</a><br>
      <a href="https://docs.pytest.org/en/stable/how-to/usage.html" target="_blank">pytest usage guide</a><br>
      <a href="https://www.acm.org/code-of-ethics" target="_blank">ACM Code of Ethics</a>
    </td>
  </tr>

  <!-- 10 -->
  <tr>
    <th>Week 10</th>
    <td><strong>Capstone:</strong> Data analysis pipeline, advanced visualization (Matplotlib), intro ML (scikit-learn glimpse) • Project wrap-up &amp; interview-style review<br></td>
    <td>Pandas + NumPy project support (CSV → DataFrame); mock tech-interview round-robin  <em>Numerical Methods:</em> <strong>Introduction to optimization</strong>: gradient descent &amp; <code>scipy.optimize.minimize</code></td>
    <td>Ch 19 (Case study: Data analysis)</td>
    <td>All prior material</td>
    <td></td>
    <td> 
      Guttag Ch 23–26; <strong>Kiusalaas Ch 10</strong><br>
      <a href="https://pandas.pydata.org/docs/getting_started/intro_tutorials/" target="_blank">Pandas intro tutorials</a>;<br>
      <a href="https://scikit-learn.org/stable/tutorial/basic/tutorial.html" target="_blank">scikit-learn basic tutorial</a>;<br>
      <a href="https://realpython.com/python-data-science/" target="_blank">Real Python • Data science pipeline</a>;<br>
      <a href="https://www.mathworks.com/products/matlab/matlab-and-python.html" target="_blank">Integrate Python in MATLAB (Cheat Sheet)</a>
    </td>
  </tr>
  </tbody>
</table>

<p>*Lecture slides will be available on the course website as we progress through the course. Part of the lecture materials are adapted from the cited references above.</p>
<p>*Slides may not cover everything discussed in class.</p>

<!-- ===== Milestones ===== -->
<p style="font-size:15pt"><b>Course Milestones</b></p>
<ul>
  <li><b>Exercises</b> ~2 Jupyter Notebooks/week: <b> due Wednesdays 11:59 pm PT</b>.</li>
  <li><b>Problem Sets</b> ~1 problem set/week: <b> due Tuesdays 11:59 pm PT</b>.</li>
  <li><b>Final Project</b>: <i>Proposal</i> (Week 8), <i>Checkpoint</i> (Week 9), <i>Final</i> (Finals week, date TBA).</li>
</ul>

<hr>
<p style="font-size:15pt"><b>Grading Policy</b></p>
<ul style="font-size:13pt">
  <li><b>Weekly Problem Sets&nbsp;(~1 problem set/week)</b> &mdash; <b>40 %</b><br>
      Released each Wednesday, due the following Tuesday at&nbsp;11:59 pm PT — Canvas submission.</li>

  <li><b>Exercises</b> &mdash; <b>15 %</b><br>
      The completed and compiled Jupyter notebook (including the exercises) — Canvas submission. Due the midnight before each class (Wednesdays 11:59 pm PT).</li>

  <li><b>Check-in Quizzes &amp; Participation</b> &mdash; <b>15 %</b><br>
      Quiz based on last lecture. Attendance, discussion, Piazza/Ed posts, peer-citation, and <b>structured peer code reviews</b>.</li>

  <li><b>Final (Individual) Capstone Project</b> &mdash; <b>30 %</b><br>
      (1) Analysis, (2) simulation, and (3) code documentation. Proposal &amp; checkpoint required. Collaborations on data collection/design discussion encouraged, but <b>code must be individual</b> unless otherwise specified — Canvas submission.</li>
</ul>

<p style="font-size:12pt"><b>Letter-grade bands</b>: A ≥ 93, A- ≥ 90, B+ ≥ 87, B ≥ 83, B- ≥ 80, C+ ≥ 77, C ≥ 73, C- ≥ 70, D ≥ 60, F &lt; 60.</p>

<p style="font-size:12pt"><b>Late Policy</b>: You have <b>3 late-day tokens</b> for the quarter. You may apply up to <b>2 tokens</b> to any single problem set or exercise (each token = 24 hours). Tokens <b>may not</b> be used for quizzes, the midterm, or the capstone final deliverable unless explicitly allowed. Beyond tokens, late submissions are not accepted. If you anticipate any other issues, contact me at least 48 hours before the deadline to discuss.</p>

<p style="font-size:12pt"><b>Collaboration &amp; Academic Integrity</b>: Discuss concepts freely; all submitted code and write-ups must be your own (or your team’s, when team work is explicitly permitted). <b>You must follow</b> the instructions provided for each activity, specifically whether the use of AI is allowed or not. <b>You must precisely cite</b> any external resources or generative-AI assistance (what you used and how). Follow PEP8 and course style guidelines. Reproducibility matters: include clear instructions for setup (venv), running tests, and reproducing results.</p>



<!-- ===== Syllabus PDF ===== -->
<p style="font-size:15pt"><b>Syllabus PDF</b></p>
<button onclick="window.print()">Print/save the syllabus as PDF</button>