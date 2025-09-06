---
layout: page
title: Computer Programming with Python (under construction)
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
Examples and exercises are drawn from engineering, mathematics, and the physical sciences to ground abstract concepts in real-world problem solving. Instruction blends mini-lectures, live-coding sessions, and hands-on notebook exercises to ensure students leave each class with runnable code and a clear mental model of how it works.
<br><br>

<!-- 
  <i>Lecture, two hours; discussion, two hours; laboratory, two hours; outside study, six hours. Requisite: Mathematics 33A. Letter grading.</i> 

<p><b>Class Time:</b> TBA </p>
<p><b>Class Room:</b> TBA / <a href="https://zoom-link">Zoom Link</a> </p>
<p><b>Office Hours:</b> TBA / <a href="https://zoom-link">Zoom Link</a>. We will be using <a href="https://piazza.com/instructors/ucla#">Piazza</a> for Q&A. </p>
<p><b>Class websites:</b> <a href="https://shahriarta.github.io/teachings/computer_programming" target="_blank">https://shahriarta.github.io/teachings/computer_programming</a> and Canvas page (homework submissions) </p>

<p>You can download a PDF copy of this syllabus <a href="/assets/pdf/python_programming/syllabus.pdf" target="_blank">here</a>.</p>
<p>Main interactive textbook (free): <a href="https://allendowney.github.io/ThinkPython/" target="_blank"><i>Think Python</i> (3rd ed.)</a>.</p>
<p>Data Science reference (free): <a href="https://jakevdp.github.io/PythonDataScienceHandbook/" target="_blank">Jake VanderPlas, <i>Python Data Science Handbook</i>, 2nd Ed</a>.</p>
<p>Conceptual reference: <a href="https://mitpress.mit.edu/9780262529624/introduction-to-computation-and-programming-using-python" target="_blank">J. Guttag, <i>Introduction to Computation & Programming Using Python</i></a>.</p>
-->

<!-- ===== Course Logistics ===== -->
<p style="font-size:15pt"><b>Course Logistics</b></p>
<ul>
  <li>
    <strong>Structure &amp; Workload:</strong><br>
    Lecture · 2 h&nbsp;/ week | Discussion · 2 h&nbsp;/ week | Laboratory · 2 h&nbsp;/ week | Outside study · ≈ 6 h&nbsp;/ week
  </li>
  <li><strong>Prerequisite:</strong> Mathematics 33A</li>
  <li><strong>Grading:</strong> Letter</li>
  <li><strong>Class Time:</strong> TBA</li>
  <li>
    <strong>Location:</strong>
    TBA (in person) | <a href="https://zoom-link">Zoom</a>
  </li>
  <li>
    <strong>Office Hours:</strong>
    TBA | <a href="https://zoom-link">Zoom</a><br>
    Q&amp;A hosted on <a href="https://piazza.com/instructors/ucla#">Piazza</a>
  </li>
</ul>

<!-- ===== Course Websites ===== -->
<p style="font-size:15pt"><b>Course Websites</b></p>
<ul>
  <li>Main site: <a href="https://shahriarta.github.io/teachings/computer_programming" target="_blank">shahriarta.github.io/teachings/computer_programming</a></li>
  <li>Canvas (homework submissions)</li>
</ul>

<!-- ===== Syllabus PDF ===== -->
<p style="font-size:15pt"><b>Syllabus PDF</b></p>
<p><a href="/assets/pdf/python_programming/syllabus.pdf" target="_blank">Download the full syllabus (PDF)</a></p>

<!-- ===== Texts & References ===== -->
<p style="font-size:15pt"><b>Main Texts &amp; References</b></p>
<ol>
  <li>
    <a href="https://allendowney.github.io/ThinkPython/" target="_blank">
      <em>Think&nbsp;Python</em> (3rd ed.) – Allen Downey (Free Online)
    </a>
  </li>
  <li>
    <a href="https://mitpress.mit.edu/9780262529624/introduction-to-computation-and-programming-using-python" target="_blank">
      <em>Introduction to Computation &amp; Programming Using Python</em> – John Guttag
    </a>
  </li>
  
</ol>

<!-- ===== Other Texts & References ===== -->
<p style="font-size:15pt"><b>Other Texts &amp; Broader references (Mostly Free Online)</b></p>
<ol>
  
  <li>
  <!-- https://www.hlevkin.com/hlevkin/90MathPhysBioBooks/Math/Polya/George_Polya_How_To_Solve_It_.pdf -->
    <a href="https://www.scribd.com/document/317302777/How-To-Solve-It-George-Polya-pdf" target="_blank">
      <em>How to Solve It</em> - George Pólya
    </a> (Read <a href="/assets/pdf/teach_cp/problem_solving_polya.pdf">this summary</a>!)
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


<!-- Course syllabus (re-aligned) -->
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
    <th>Lecture 1</th>
    <td>Course logistics • Programming mindset<br><strong>Syntax, variables, types, operators, Basic I/O, code style</strong></td>
    <td>Variables & control-flow drill + mini-debug (pdb watch-list)</td>
    <td>Ch 01 & 02</td>
    <td>Math 33A</td>
    <td></td>
    <td>
      Guttag Ch 1;<br>
      <a href="https://docs.python.org/3/tutorial/" target="_blank">Python tutorial (official)</a>,<br>
      <a href="https://peps.python.org/pep-0008/" target="_blank">PEP 8 style guide</a>,<br>
      <a href="https://www.alanturing.net/turing_archive/pages/reference%20articles/Turing%27s%20O-Machines.html" target="_blank">Turing Machine</a><br>, <a href="https://realpython.com/python-bitwise-operators/" target="_blank">Bitwise Operators in Python</a><br>
    </td>
  </tr>

  <!-- 2 -->
  <tr>
    <th>Lecture 2</th>
    <td>Branching and conditionals, loops, ranges; Comparison/Boolean Operators; Data structures:lists, tuples;<strong>list comprehensions</strong></td>
    <td>Array exercises <br>Loop-based problem solving (max, sum, reverse) <br> off-by-one error debuging</td>
    <td>Ch 06 (Iteration) &nbsp;+ Ch 08 (Lists)<br><small>§03.12 list-comprehension *peek*</small></td>
    <td>Basic program structure</td>
    <td></td>
    <td>
      Guttag Ch 2-3;<br>
      <a href="https://www.learnpython.org/" target="_blank">LearnPython .org interactive</a><br>
      <a href="https://realpython.com/python-for-loop/" target="_blank">Real Python • Loops</a><br>
      <a href="https://docs.python.org/3/tutorial/datastructures.html#more-on-lists" target="_blank">Python docs – lists &amp; tuples</a>
    </td>
  </tr>

  <!-- 3 -->
  <tr>
    <th>Lecture 3</th>
    <td>Functions, scopes, *args/**kwargs, iterables, map, lambda function</td>
    <td>Modular design &amp; </td>
    <td>Ch 03 (Functions) &amp; Ch 05 §5.1-5.4 (Fruitful funcs)<br><small>*Skip recursion parts until L6*</small></td>
    <td>Branching &amp; loops</td>
    <td></td>
    <td>
      Guttag Ch 4 & 8;<br>
      <a href="https://realpython.com/defining-your-own-python-function/" target="_blank">Real Python • Defining functions</a><br>
      <a href="https://realpython.com/args-and-kwargs-python/" target="_blank">*args & **kwargs explained</a><br>
      <a href="https://docs.python.org/3/library/__main__.html" target="_blank">Python docs – <code>__main__</code></a><br>
      <a href="https://realpython.com/python-testing/" target="_blank">pytest intro</a>
    </td>
  </tr>

  <!-- 4 -->
  <tr>
    <th>Lecture 4</th>
    <td>Recursion &amp; problem decomposition • Sorting (built-in &amp; custom) • Searching (linear / binary)<br>Root-finding (bisection) • <strong>Big-O basics</strong> </td>
    <td>Sort/search challenges + timing decorator (simple profiler) + Matplotlib multi-plot demo</td>
    <td>Ch 05 §5.5-5.9 (Recursion) &amp; Ch 13 §13.3-13.6 (Search & Selection)</td>
    <td>Dictionaries &amp; files</td>
    <td></td>
    <td>
      Guttag Ch 11, 14-15;<br>
      <a href="https://bigocheatsheet.com/" target="_blank">Big-O Cheat Sheet</a><br>
      <a href="https://www.cs.usfca.edu/~galles/visualization/Search.html" target="_blank">Visual Algo • Search animations</a><br>
      <a href="https://www.geeksforgeeks.org/python-programming-examples/" target="_blank">GfG sorting/search practice</a>
    </td>
  </tr>

  <!-- 5 -->
  <tr>
    <th>Lecture 5</th>
    <td>Dictionaries, sets, mutability vs hashability<br>Hash-based problem solving (freq maps, memoisation)</td>
    <td>Strings review; Anagrams &amp; hashmap puzzles (with logging)</td>
    <td>Ch 07 (Strings review) &amp; Ch 09 (Dictionaries)<br>Ch 10 §10.2-10.4 (Tuples vs lists)</td>
    <td>Functions &amp; testing</td>
    <td></td>
    <td>
      Guttag Ch 5 & 7;<br>
      <a href="https://pythontutor.com/" target="_blank">Python Tutor visualizer</a><br>
      <a href="https://realpython.com/python-dicts/" target="_blank">Real Python • Dictionaries</a><br>
      <a href="https://realpython.com/python-sets/" target="_blank">Real Python • Sets</a>
    </td>
  </tr>

  <!-- 6 -->
  <tr>
    <th>Lecture 6</th>
    <td>File I/O (text, CSV, JSON); <br>Script execution (<code>if __name__ == "__main__"</code>); Modules &amp; packages<br><strong>Defensive programming:</strong> try/except, assertions, basic debugging<br></td>
    <td>File parsing + input validation + Unit testing basics + TDD (pytest markers + assert patterns)<br><strong>Mini-lab:</strong> NumPy & Pandas warm-up (CSV → DataFrame) + <em>Quick intro to Matplotlib:</em> plot CSV columns</td>
    <td>Ch 11 (Files & Exceptions) &amp; Ch 12 (Modules)</td>
    <td>Sequences overview</td>
    <td></td>
    <td>
      Guttag Ch 6, 8-9;<br>
      <a href="https://automatetheboringstuff.com/" target="_blank">Automate the Boring Stuff – Ch 10-11</a><br>
      <a href="https://realpython.com/read-write-files-python/" target="_blank">Real Python • File I/O</a><br>
      <a href="https://matplotlib.org/stable/users/getting_started/" target="_blank">Matplotlib getting started</a><br>
      <a href="https://numpy.org/devdocs/user/quickstart.html" target="_blank">NumPy quickstart</a><br>
      <a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html" target="_blank">Pandas I/O guide</a>
    </td>
  </tr>

  <!-- 7 -->
  <tr>
    <th>Lecture 7</th>
    <td><strong>OOP I:</strong> Classes, constructors, encapsulation, <code>__str__</code>/<code>__repr__</code><br>Data Structures I: Stacks, queues, priority queues (<code>heapq</code>)<br>Interview patterns: balanced parentheses, sliding-window max</td>
    <td>Stack/queue/heap drills + class-based simulation (with doctest)</td>
    <td>Ch 14 &amp; 15 (Classes & Objects)</td>
    <td>Recursion &amp; complexity</td>
    <td></td>
    <td>
      Guttag Ch 10 & 13;<br>
      <a href="https://docs.python.org/3/library/heapq.html" target="_blank">heapq docs</a><br>
      <a href="https://realpython.com/python-data-structures/" target="_blank">Real Python • Stacks &amp; Queues</a><br>
      <a href="https://leetcode.com/tag/stack/" target="_blank">LeetCode stack practice</a>
    </td>
  </tr>

  <!-- 8 -->
  <tr>
    <th>Lecture 8</th>
    <td><strong>OOP II:</strong> Inheritance, polymorphism, abstract base classes<br><strong>Data Structures &amp; Graph Algorithms:</strong> adjacency lists, DFS, BFS, shortest path, memoisation<br>Dynamic Programming intro</td>
    <td>Graph problems (maze reachability, shortest path) + inheritance refactor</td>
    <td>Ch 17 (Inheritance) &amp; Ch 18 §18.1-18.3 (Simple DP)</td>
    <td>OOP concepts</td>
    <td></td>
    <td>
      Guttag Ch 12 & 15;<br>
      <a href="https://networkx.org/documentation/stable/" target="_blank">NetworkX docs</a><br>
      <a href="https://khanacademy.org/computing/computer-science/algorithms#graphs" target="_blank">Khan Academy • Graph intro</a><br>
      <a href="https://cp-algorithms.com/graph/" target="_blank">CP-Algorithms • Graph guide</a>
    </td>
  </tr>

  <!-- 9 -->
  <tr>
    <th>Lecture 9</th>
    <td><strong>Testing &amp; Debugging Deep-Dive:</strong> pytest fixtures, coverage, pdb, logging config, profiling<br>Exception hierarchies, input validation patterns</td>
    <td>End-to-end debugging workflow on prior homework</td>
    <td>Appendix B (Debugging) &amp; Ch 11 §11.4 (try/except)</td>
    <td>Algorithm analysis</td>
    <td></td>
    <td>
      Guttag Ch 8-9;<br>
      <a href="https://realpython.com/python-debugging-pdb/" target="_blank">pdb tutorial (Real Python)</a><br>
      <a href="https://docs.python.org/3/howto/logging.html" target="_blank">Logging How-To</a><br>
      <a href="https://docs.pytest.org/en/stable/how-to/usage.html" target="_blank">pytest usage guide</a>
    </td>
  </tr>

  <!-- 10 -->
  <tr>
    <th>Lecture 10</th>
    <td><strong>Capstone:</strong> Data analysis pipeline, advanced visualization, intro ML (scikit-learn glimpse)<br>Project wrap-up &amp; interview-style review</td>
    <td>Pandas + NumPy project support, mock tech-interview round-robin</td>
    <td>Ch 19 (Case study: Data analysis)</td>
    <td>All prior material</td>
    <td></td>
    <td>
      Guttag Ch 23-26;<br>
      <a href="https://pandas.pydata.org/docs/getting_started/intro_tutorials/" target="_blank">Pandas intro tutorials</a>;<br>
      <a href="https://scikit-learn.org/stable/tutorial/basic/tutorial.html" target="_blank">scikit-learn basic tutorial</a>;<br>
      <a href="https://realpython.com/python-data-science/" target="_blank">Real Python • Data science pipeline</a>;<br>
      <a href="https://www.mathworks.com/products/matlab/matlab-and-python.html" target="_blank">Integrate Python in MATLAB</a> with this <a href="https://www.mathworks.com/content/dam/mathworks/fact-sheet/calling-python-from-matlab-cheat-sheet.pdf?s_v1=61219&elqem=4918544_EM_NA_DIR_25-08_MOE-CG-A&rec_id=ee22b06468874a1e8d7e0a6fedda5901">CheatSheet</a>
    </td>
  </tr>

  </tbody>
</table>
* Part of the lecture materials are adapted from the cited references and will be available on the course website as we progress through the course.

<!-- <table style="width:100%" border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Problem Set</th>
      <th>Topic</th>
      <th>Starter Notebook</th>
      <th>Due Date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Problem Set 0</td>
      <td>Diagnostic</td>
      <td><a href="/assets/notebooks/CPP/pset0_diagnostic.ipynb" target="_blank">pset0_diagnostic.ipynb</a></td>
      <td>TBD</td>
    </tr>
    <tr>
      <td>Problem Set 1</td>
      <td>Branching & Iteration</td>
      <td><a href="/assets/notebooks/CPP/pset1_branching_iteration.ipynb" target="_blank">pset1_branching_iteration.ipynb</a></td>
      <td>TBD</td>
    </tr>
    <tr>
      <td>Problem Set 2</td>
      <td>Functions & Recursion</td>
      <td><a href="/assets/notebooks/CPP/pset2_functions.ipynb" target="_blank">pset2_functions.ipynb</a></td>
      <td>TBD</td>
    </tr>
    <tr>
      <td>Problem Set 3</td>
      <td>Data Collections</td>
      <td><a href="/assets/notebooks/CPP/pset3_data_collections.ipynb" target="_blank">pset3_data_collections.ipynb</a></td>
      <td>TBD</td>
    </tr>
    <tr>
      <td>Problem Set 4</td>
      <td>Object-Oriented Programming</td>
      <td><a href="/assets/notebooks/CPP/pset4_oop.ipynb" target="_blank">pset4_oop.ipynb</a></td>
      <td>TBD</td>
    </tr>
    <tr>
      <td>Problem Set 5</td>
      <td>Algorithms & Testing</td>
      <td><a href="/assets/notebooks/CPP/pset5_algorithms.ipynb" target="_blank">pset5_algorithms.ipynb</a></td>
      <td>TBD</td>
    </tr>
  </tbody>
</table> -->





<!-- Problem sets -->
<hr>
<p style="font-size:15pt"><b>Grading Policy</b></p>
<ul style="font-size:13pt">
  <li><b>Weekly Problem Sets&nbsp;(7)</b> &mdash; <b>30 %</b><br>
      Released each Friday, due the following Thursday at&nbsp;11:59 pm ET--Canvas submission.</li>

  <li><b>Exercises</b> &mdash; <b>20 %</b><br>
      The completed and compiled Jupyter notebook (including the exercises)--Canvas submission. Due the midnight  before each class (Wednesdays 11:59pm) </li>

  <li><b>Check-in Quizes&amp;Participation </b> &mdash; <b>20 %</b><br>
      Quize is based on last lecture. Attendance, discussion, Piazza/Ed posts, peer-citation, and peer-code reviews.</li>

  <li><b>Final (Individual) Capstone Project</b> &mdash; <b>30 %</b><br>
      (1) Analysis, (2) simulation, and (3) code documentation will be due on date:TBA. Collaborations are highly encouraged based on "Collaboration Policy"--Canvas submission. </li>
</ul>

<p style="font-size:12pt"><b>Letter-grade bands</b>: A ≥ 93, A- ≥ 90, B+ ≥ 87, B ≥ 83, B- ≥ 80, C+ ≥ 77, C ≥ 73, C- ≥ 70, D ≥ 60, F &lt; 60.</p>

<p style="font-size:12pt"><b>Late Policy</b>: Late submissions are not accepted. If you are unable to submit on time due to a valid reason, please contact me at least 48 hours before the deadline to discuss possible accommodations.
</p>

<p style="font-size:12pt"><b>Collaboration Policy</b>: Discuss concepts freely, but all submitted code and write-ups must be your own. You must also cite precisely and in detail any external resources or generative-AI assistance used.</p>
