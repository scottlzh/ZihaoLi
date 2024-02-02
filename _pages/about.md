---
permalink: /
title: "Howdy, y’all!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---




<p>Life is like a box of chocolates, you never know what you're going to get.</p>
<p style="text-align: right;">-- Forrest Gump (1994)</p>




<hr color="#FFFFFF" />

Biography
======

<!-- --------------------------------First Person --------------------------- -->

<div style="text-align: justify"> 

<p>Zihao 'Scott' Li is a final-year PhD student in the Zachry Department of Civil and Environment Engineering, at Texas A&M University under the supervision of <a href="https://engineering.tamu.edu/civil/profiles/yzhang.html" style="color:#5dbcd2;">Dr. Yunlong Zhang</a>. Meanwhile, he had been working with the <a href="https://mobility.tamu.edu/" style="color:#5dbcd2;"> Mobility Division </a> at Texas A&M Transportation Institute.
  
<p>I am a PhD student at ProrokLab in the Digital Technology Group (DTG) at the University of Cambridge under the supervision of <a href="https://www.proroklab.org/"
 style="color:#5dbcd2;">Dr Amanda Prorok</a>. During my PhD, I focus on <b>communication-aware motion planning</b> for multi-robot coordination. I am investigating <b>Graph Neural Networks (GNN)</b> to build communication channels for multi-agent and multi-robot systems so that they can learn how to communicate between each other explicitly. 
 My research can be applied to mobility-on-demand systems, automated warehouses, and smart cities.</p> 


<p>Prior to joining Cambridge, I was working in <a href="https://www.imperial.ac.uk/hamlyn-centre/" style="color:#5dbcd2;">the Hamlyn Centre</a> at Imperial College London, founded by <a href="https://ieeexplore.ieee.org/author/37276270800" style="color:#5dbcd2;">Prof Guang-Zhong Yang</a> and <a href="https://www.imperial.ac.uk/people/a.darzi" style="color:#5dbcd2;">the Lord Ara Darzi</a>,  in the field of medical robotics and healthcare to earn my MRes in Medical Robotics and Image-Guided Intervention. I was supervised by <a href="https://www.imperial.ac.uk/people/daniel.elson" style="color:#5dbcd2;">Prof Daniel Elson</a> for an eight-month research project about oxygen saturation (StO2) estimation, and graduated with a distinction. I also hold an MEng degree in Mechanical Engineering from the University of Edinburgh.</p> 

<p>I have published papers in the medical imaging area (IJCARS) and the robotics field (IEEE IROS, IEEE Humanoids, and AAMAS). I have served as a reviewer for IEEE IROS, IEEE ICRA, IEEE RA-L, IEEE T-RO, and AAMAS.</p> 

<p><b>I am open to collaboration opportunities</b>. Feel free to contact by Email (ql295[AT]cam.ac.uk). Details of my CV can be found in <a href="../files/CV_QingbiaoLi.pdf" style="color:#5dbcd2;">PDF</a>.</p>


<p><b>News:</b> From July 2021 to Oct 2021, I am working on <a href="https://www.microsoft.com/en-us/research/project/project-silica/" style="color:#5dbcd2;">Project Silica</a> during my internship at Microsoft Research Cambridge. I am exploring explainable RL-based approaches to scheduling in the Silica glass library, towards a scheduler for production deployment.</p>

</div>


<!-- </div> -->

<!-- My research interests include:</p>
<ul>
<li>Traffic Operation, Intelligent Transportation System, Artifical Intelligence in Transportation, Transportation Resilience.</li>
</ul>
<p> -->

<!-- 
<p>I am a PhD student at ProrokLab, the Digital Technology Group (DTG) at the University of Cambridge under the supervision of <a href="https://www.proroklab.org/"
 style="color:#5dbcd2;">Dr Amanda Prorok</a>. During my PhD, I focus on <b>communication-aware motion planning</b> for multi-robot coordination. 
I am effectively investigating <b>Graph Neural Networks (GNN)</b> to build communication channels for multi-agent and multi-robot systems so that agents/robots can learn how to communicate between each other explicitly. 
My research can be applied in mobility-on-demand, automated warehouse and smart cities.</p> 


<p>Prior to joining Cambridge,  I joined <a href="https://www.imperial.ac.uk/hamlyn-centre/" style="color:#5dbcd2;">Hamlyn Centre</a> at Imperial College London, found by <a href="https://ieeexplore.ieee.org/author/37276270800" style="color:#5dbcd2;">Prof Guang-Zhong Yang</a> and <a href="https://www.imperial.ac.uk/people/a.darzi" style="color:#5dbcd2;">Prof the Lord Ara Darzi</a>  in the field of medical robots and healthcare for  the MRes in Medical Robotics and Image-Guided Intervention. I was supervised by <a href="https://www.imperial.ac.uk/people/daniel.elson" style="color:#5dbcd2;">Prof Daniel Elson</a> for eight-month research project about oxygen saturation (StO2) estimation, and graduated with Distinction for MRes degree. I also held a MEng degree in Mechanical Engineering at  University of Edinburgh.</p> 

<p>I have published papers in medical imaging area (IJCARS) and robotics field (IEEE IROS, IEEE Humanoids and AAMAS). I have served as a reviewer for IEEE IROS, IEEE ICRA, IEEE RA-L, IEEE T-RO and AAMAS.</p>

<p><b>I am open to collaboration opportunities</b> (anytime & anywhere) and <b>research internships</b> (open for Summer 2021). Feel free to contact by Email (ql295[AT]cam.ac.uk). Details of my CV can be found at <a href="../files/CV_QingbiaoLi.pdf" style="color:#5dbcd2;">PDF</a>.</p>
 --> 



<hr color="#FFFFFF" />

Research Interest
======
<ul>
<li>Robot Learning</li>
<li>Multi-robot Path Planning</li>
<li>Graph Neural Networks (GNNs)</li>
<li>Imitation Learning </li>
<li>Reinforcement Learning</li>
<li>Computer Vision (Medical Imaging) </li>
</ul>

<hr color="#FFFFFF" />

Publications
======
<!--   <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
 -->

## <i>Journal</i>
  <ul>{% for post in site.journal reversed %}
    {% include archive-single-publications.html %}
  {% endfor %}</ul>

## <i>Conference</i>
  <ul>{% for post in site.conference reversed %}
    {% include archive-single-publications.html %}
  {% endfor %}</ul>
**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
