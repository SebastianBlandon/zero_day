<div class="hidden-xs navigation sidebar">
<p>&nbsp;</p>
<div title="" data-container="body" data-placement="right" data-toggle="tooltip" data-original-title="Slack">&nbsp;</div>
<div title="" data-container="body" data-placement="right" data-toggle="tooltip" data-original-title="My Profile">&nbsp;</div>
</div>
<main>
<div id="layout-bars"></div>
<article class="">
<div class="project row">
<div class="col-xs-12 col-md-10 col-lg-8 contains-images">
<h1 class="gap">[Optional] Vagrant</h1>
<ul id="project-metadata" class="list-group metadata"></ul>
<h2>Concepts</h2>
<div class="panel panel-default">
<div class="panel-body">
<p><em>For this project, students are expected to look at these concepts:</em></p>
<ul>
<li><a href="https://intranet.hbtn.io/concepts/22">Source code management</a></li>
<li><a href="https://intranet.hbtn.io/concepts/57">Git and Github cheat sheet - Everything in less than 30 seconds</a></li>
<li><a href="https://intranet.hbtn.io/concepts/75">The Framework</a></li>
<li><a href="https://intranet.hbtn.io/concepts/81">Using Vagrant on your personal computer</a></li>
<li><a href="https://intranet.hbtn.io/concepts/350">Approaching a Project</a></li>
</ul>
</div>
</div>
<div id="project-description" class="well clean">
<h2>Resources</h2>
<p><strong>Read or watch</strong>:</p>
<ul>
<li><a title="Zero day" href="https://intranet.hbtn.io/rltoken/NcuS4-7zF9-edjbo157uQQ" target="_blank" rel="noopener">Zero day</a></li>
<li><a title="Virtual machine" href="https://intranet.hbtn.io/rltoken/v2RbeSrU14w3KTwbGYH3Fw" target="_blank" rel="noopener">Virtual machine</a></li>
<li><a title="man uname" href="https://intranet.hbtn.io/rltoken/3AHxDiZwhZwPM_GiHox0gQ" target="_blank" rel="noopener">man uname</a></li>
<li><a title="Resources to learn Git" href="https://intranet.hbtn.io/rltoken/i2CtlPhs4zaAbtEUdY2l3A" target="_blank" rel="noopener">Resources to learn Git</a></li>
<li><a title="About READMEs" href="https://intranet.hbtn.io/rltoken/86HNyB59eoxAhtIahOXKGQ" target="_blank" rel="noopener">About READMEs</a></li>
<li><a title="How to write a Git commit message" href="https://intranet.hbtn.io/rltoken/4szBlqEXwOgr1YON9bxhPQ" target="_blank" rel="noopener">How to write a Git commit message</a></li>
</ul>
<h2>Learning Objectives</h2>
<p>At the end of this project, you are expected to be able to&nbsp;<a title="explain to anyone" href="https://intranet.hbtn.io/rltoken/9E9csOc85_TcgG0jeF8Oxw" target="_blank" rel="noopener">explain to anyone</a>,&nbsp;<strong>without the help of Google</strong>:</p>
<h3>General</h3>
<ul>
<li>What is a zero-day</li>
<li>What is a virtual machine</li>
<li>What is Vagrant</li>
<li>Who wrote Vagrant</li>
<li>What is Ubuntu</li>
<li>What does &ldquo;Ubuntu&rdquo; mean</li>
<li>How to use VMs with Vagrant</li>
<li>What does the command&nbsp;<code>uname</code>&nbsp;do</li>
<li>What is source code management</li>
<li>What is Git</li>
<li>What is GitHub</li>
<li>What is the difference between Git and GitHub</li>
<li>How to create a repository</li>
<li>What is a README</li>
<li>How to write good READMEs</li>
<li>How to commit</li>
<li>How to write helpful commit messages</li>
<li>How to push code</li>
</ul>
<h2>Requirements</h2>
<h3>General</h3>
<ul>
<li>A&nbsp;<code>README.md</code>&nbsp;file at the root of the repo, containing a description of the repository</li>
<li>A&nbsp;<code>README.md</code>&nbsp;file, at the root of the folder of&nbsp;<em>this</em>&nbsp;project (i.e.&nbsp;<code>0x00-vagrant</code>), describing what this project is about</li>
</ul>
<h2>More Info</h2>
<h3>Install&nbsp;<code>git</code></h3>
<p>If&nbsp;<code>git</code>&nbsp;is not already installed on your terminal:</p>
<pre><code>$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
</code></pre>
<h3>Basic usage</h3>
<p>At the end of this project you should be able to reproduce and understand these command lines:</p>
<pre><code>$ git clone &lt;repo&gt;
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
</code></pre>
<h3>Warning</h3>
<p>This project&nbsp;<strong>can&rsquo;t be done in Sandboxes</strong>&nbsp;- it can be done only in your local computer. Please refer to our concept pages for your operating system.</p>
</div>
<h2 id="project-quiz-questions-title" class="gap">Quiz questions</h2>
<div class="panel panel-default">
<div class="panel-body">
<p id="quiz_questions_collapse_toggle">Show</p>
</div>
</div>
<h2 class="gap">Tasks</h2>
<div id="task-num-0" data-role="task3902" data-position="1">
<div id="task-3902" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">0. Create and setup your Git and GitHub account</h3>
</div>
<div class="panel-body">
<p>You will need Git for this project, you might have to&nbsp;<a title="install it" href="https://intranet.hbtn.io/rltoken/TJrA7MIEl9LxnkGNH_ddmw" target="_blank" rel="noopener">install it</a>&nbsp;on your computer if it&rsquo;s not done yet.</p>
<ul>
<li>Configure your basic info (name, email) on your local machine &ndash; they will be part of your commits.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/72jmwYpf2OeuoOn9XM3vQg" target="_blank" rel="noopener">Tips</a></li>
</ul>
<p>On&nbsp;<a title="GitHub.com" href="https://intranet.hbtn.io/rltoken/m27bKy8K40cIkyHWQ36i2w" target="_blank" rel="noopener">GitHub.com</a>:</p>
<ul>
<li>Using the graphic interface on the website, create the repository (if it&rsquo;s not done yet)
<ul>
<li>Description:&nbsp;<code>This is my first repository as a full-stack engineer</code></li>
<li>Public repo:&nbsp;<code>zero_day</code></li>
<li>No&nbsp;<code>README</code>,&nbsp;<code>.gitignore</code>, or license</li>
</ul>
</li>
</ul>
<p>On your computer, open a terminal and do the following:</p>
<ul>
<li>Navigate to your home directory.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/-odz94uVNOsPV1ovYZLuyw" target="_blank" rel="noopener">Tips</a></li>
<li>Create a directory&nbsp;<code>zero_day</code>.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/AHYBfU0itf9qEiwLdiaVJw" target="_blank" rel="noopener">Tips</a></li>
<li>Navigate to this new directory.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/9g9c-qBPHWSGcpxbs69ASw" target="_blank" rel="noopener">Tips</a></li>
<li>Initialize git and add the remote origin</li>
<li>Create a file&nbsp;<code>README.md</code>&nbsp;with Emacs (or other command line editors) and write a small&nbsp;<a title="Markdown" href="https://intranet.hbtn.io/rltoken/Ru3ANLuzGs4g0v2qsN3efA" target="_blank" rel="noopener">Markdown</a>&nbsp;text to present this project.&nbsp;<strong>This file is mandatory in projects</strong></li>
<li>Add this new file to git, commit the change with this message &ldquo;My first commit&rdquo; and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)</li>
</ul>
<p>Good job!</p>
<p>You pushed your first file in your&nbsp;<strong>first repository</strong>&nbsp;of the&nbsp;<strong>first task</strong>&nbsp;of your&nbsp;<strong>first School project</strong>.</p>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
<li>File:&nbsp;<code>README.md</code></li>
</ul>
</div>
</div>
</div>
</div>
<div id="task-num-1" data-role="task808" data-position="2">
<div id="task-808" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">1. Hello Ubuntu</h3>
</div>
<div class="panel-body">
<p>Inside the&nbsp;<code>zero_day</code>&nbsp;repo, create a new directory called&nbsp;<code>0x00-vagrant</code>. Add a&nbsp;<code>README.md</code>&nbsp;file to this directory.</p>
<p><code>ssh</code>&nbsp;into your Ubuntu VM. What does the command&nbsp;<code>uname</code>&nbsp;print when you run it without any option?</p>
<p>Type your answer into a file in the&nbsp;<code>0x00-vagrant</code>&nbsp;directory and push it to GitHub. Name your file accordingly as shown below.</p>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
<li>Directory:&nbsp;<code>0x00-vagrant</code></li>
<li>File:&nbsp;<code>0-hello_ubuntu</code></li>
</ul>
</div>
</div>
</div>
</div>
</div>
</div>
</article>
<div class="copyright">Copyright &copy; 2022 Holberton Inc, All rights reserved.</div>
</main>
