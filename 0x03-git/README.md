<div class="hidden-xs navigation sidebar">
<h1 class="gap">0x03. Git</h1>
</div>
<main>
<article class="">
<div class="project row">
<div class="col-xs-12 col-md-10 col-lg-8 contains-images">
<ul id="project-metadata" class="list-group metadata"></ul>
<h2>Concepts</h2>
<div class="panel panel-default">
<div class="panel-body">
<p><em>For this project, students are expected to look at these concepts:</em></p>
<ul>
<li><a href="https://intranet.hbtn.io/concepts/22">Source code management</a></li>
<li><a href="https://intranet.hbtn.io/concepts/57">Git and Github cheat sheet - Everything in less than 30 seconds</a></li>
<li><a href="https://intranet.hbtn.io/concepts/75">The Framework</a></li>
<li><a href="https://intranet.hbtn.io/concepts/350">Approaching a Project</a></li>
</ul>
</div>
</div>
<div id="project-description" class="well clean">
<h2>Resources</h2>
<p><strong>Read or watch:</strong></p>
<ul>
<li><a title="Resources to learn Git" href="https://intranet.hbtn.io/rltoken/rOOPwBFp4ezRunQ0G0YHYQ" target="_blank" rel="noopener">Resources to learn Git</a></li>
<li><a title="About READMEs" href="https://intranet.hbtn.io/rltoken/4CwCa3MmQvJfXu5poTRVQw" target="_blank" rel="noopener">About READMEs</a></li>
<li><a title="How to write a Git commit message" href="https://intranet.hbtn.io/rltoken/zkdCE4WEr9H91WlOpfNlGA" target="_blank" rel="noopener">How to write a Git commit message</a></li>
</ul>
<p><strong>Resources for advanced tasks</strong>&nbsp;(Read only after finishing the mandatory tasks):</p>
<ul>
<li><a title="Learning branching" href="https://intranet.hbtn.io/rltoken/514Jj2WL9uL6wOyOYWejdA" target="_blank" rel="noopener">Learning branching</a></li>
<li><a title="Effective pull requests and other good practices for teams using GitHub" href="https://intranet.hbtn.io/rltoken/ZUE0eoAWDKadJd4QCQkzQg" target="_blank" rel="noopener">Effective pull requests and other good practices for teams using GitHub</a></li>
</ul>
<h2>Learning Objectives</h2>
<p>At the end of this project, you are expected to be able to&nbsp;<a title="explain to anyone" href="https://intranet.hbtn.io/rltoken/9nDe1J66MhvFwTm9pj88WQ" target="_blank" rel="noopener">explain to anyone</a>,&nbsp;<strong>without the help of Google</strong>:</p>
<h3>General</h3>
<ul>
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
<li>How to pull updates</li>
<li>How to create a branch</li>
<li>How to merge branches</li>
<li>How to work as collaborators on a project</li>
<li>Which files should and which files should not appear in your repo</li>
</ul>
<h2>Requirements</h2>
<h3>General</h3>
<ul>
<li>A&nbsp;<code>README.md</code>&nbsp;file at the root of the repo, containing a description of the repository</li>
<li>A&nbsp;<code>README.md</code>&nbsp;file, at the root of the folder of&nbsp;<em>this</em>&nbsp;project (i.e.&nbsp;<code>0x03-git</code>), describing what this project is about</li>
<li><strong>Do not use GitHub&rsquo;s web UI</strong>, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won&rsquo;t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.</li>
<li>Your answer files should only contain the command, and nothing else</li>
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
</div>
<h2 id="project-quiz-questions-title" class="gap">Quiz questions</h2>
<div class="panel panel-default">
<div class="panel-body">
<section class="quiz_questions_show_container">
<div class="quiz_question_item_container" data-role="quiz_question860" data-position="1">
<div id="quiz_question-860" class=" clearfix">
<h4 class="quiz_question">Question #0</h4>
<p>You have the following files in your project directory:</p>
<pre><code>julien@ubuntu:/tmp/git_project$ ls
0-test  0-test~ #0-test# file1  file2
</code></pre>
<p>You&rsquo;ve edited&nbsp;<code>0-test</code>&nbsp;and you want to add it to your GitHub repo. What is the correct command to add&nbsp;<strong>only</strong>&nbsp;<code>0-test</code>?</p>
<ul class="quiz_question_answers" data-question-id="860">
<li class=""><input id="quiz-answer-1557524492696" disabled="disabled" name="quiz-answer-1557524492696" type="checkbox" data-quiz-question-id="860" data-quiz-answer-id="1557524492696" />
<p><code>git add .</code></p>
</li>
<li class=""><input id="quiz-answer-1557524494319" disabled="disabled" name="quiz-answer-1557524494319" type="checkbox" data-quiz-question-id="860" data-quiz-answer-id="1557524494319" />
<p><code>git add -N 0-test</code></p>
</li>
<li class=""><input id="quiz-answer-1557524496546" checked="checked" disabled="disabled" name="quiz-answer-1557524496546" type="checkbox" data-quiz-question-id="860" data-quiz-answer-id="1557524496546" />
<p><code>git add 0-test</code></p>
</li>
</ul>
<div class="alert alert-info">
<h4>Tips:</h4>
<p>You should learn what each of these commands would actually do if you were to execute them!</p>
</div>
</div>
</div>
<div class="quiz_question_item_container" data-role="quiz_question861" data-position="2">
<div id="quiz_question-861" class=" clearfix">
<h4 class="quiz_question">Question #1</h4>
<p>What command can you use to see what changes have been staged, which haven&rsquo;t, and which files aren&rsquo;t being tracked by Git?</p>
<ul class="quiz_question_answers" data-question-id="861">
<li class=""><input id="quiz-answer-1557524815058" disabled="disabled" name="quiz-answer-1557524815058" type="checkbox" data-quiz-question-id="861" data-quiz-answer-id="1557524815058" />
<p><code>git init</code></p>
</li>
<li class=""><input id="quiz-answer-1557524821355" checked="checked" disabled="disabled" name="quiz-answer-1557524821355" type="checkbox" data-quiz-question-id="861" data-quiz-answer-id="1557524821355" />
<p><code>git status</code></p>
</li>
<li class=""><input id="quiz-answer-1557524822655" disabled="disabled" name="quiz-answer-1557524822655" type="checkbox" data-quiz-question-id="861" data-quiz-answer-id="1557524822655" />
<p><code>git checkout</code></p>
</li>
</ul>
</div>
</div>
</section>
</div>
</div>
<h2 class="gap">Tasks</h2>
<div id="task-num-0" data-role="task9720" data-position="1">
<div id="task-9720" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">0. Create and setup your Git and GitHub account</h3>
<div><span class="label label-info">mandatory</span></div>
</div>
<div class="panel-body"><span id="user_id" data-id="4543"></span>
<div class="task_progress_score_bar" data-task-id="9720" data-correction-id="293886">
<div class="task_progress_bar">
<div class="task_score_bar">&nbsp;</div>
</div>
<div class="task_progress_score_text">Score:&nbsp;<span class="task_score_value">100.00%</span>&nbsp;(<span class="task_progress_value">Checks completed: 100.00%</span>)</div>
</div>
<p>You will need Git for this project, you might have to&nbsp;<a title="install it" href="https://intranet.hbtn.io/rltoken/n2SJyaVuu1tuhVgHSKw5Sg" target="_blank" rel="noopener">install it</a>&nbsp;on your computer if it&rsquo;s not done yet.</p>
<ul>
<li>Configure your basic info (name, email) on your local machine &ndash; they will be part of your commits.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/WCZwvMlDTWNwo7D2h5RXiw" target="_blank" rel="noopener">Tips</a></li>
</ul>
<p>On&nbsp;<a title="GitHub.com" href="https://intranet.hbtn.io/rltoken/YNvmlBzyEYR4EcwFclIbwQ" target="_blank" rel="noopener">GitHub.com</a>:</p>
<ul>
<li>Using the graphic interface on the website, create the repository (if it&rsquo;s not done yet)
<ul>
<li>Name:&nbsp;<code>zero_day</code></li>
<li>Description:&nbsp;<code>This is my first repository as a full-stack engineer</code></li>
<li>Public repo</li>
<li>No&nbsp;<code>README</code>,&nbsp;<code>.gitignore</code>, or license</li>
</ul>
</li>
</ul>
<p>Update your Intranet profile by adding your Github username&nbsp;<a title="here" href="https://intranet.hbtn.io/rltoken/18IAhpoWtIm4rxdhYLU3kg" target="_blank" rel="noopener">here</a>&nbsp;- if it&rsquo;s not done,&nbsp;<strong>the Checker won&rsquo;t be able to correct your work</strong></p>
<p>On your computer, open a terminal and do the following:</p>
<ul>
<li>Navigate to your home directory.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/nSl91LBC_er1QmayRs60Rg" target="_blank" rel="noopener">Tips</a></li>
<li>Create a directory&nbsp;<code>zero_day</code>.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/qE0DHC3e86f7eZF6mlqFyQ" target="_blank" rel="noopener">Tips</a></li>
<li>Navigate to this new directory.&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/hgr3egDWXiBW_PIDqBAWDA" target="_blank" rel="noopener">Tips</a></li>
<li>Initialize git and add the remote origin</li>
<li>Create a file&nbsp;<code>README.md</code>&nbsp;with Emacs or Vi (or other command line editors) and write a small&nbsp;<a title="Markdown" href="https://intranet.hbtn.io/rltoken/Na_yqM9Y5nNNXtvjVAxZKA" target="_blank" rel="noopener">Markdown</a>&nbsp;text to present this project.&nbsp;<strong>This file is mandatory in all School projects</strong></li>
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
<div id="task-num-1" data-role="task3903" data-position="2">
<div id="task-3903" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">1. Repo-session</h3>
</div>
<div class="panel-body">
<p>Create a new directory called&nbsp;<code>0x03-git</code>&nbsp;in your&nbsp;<code>zero_day</code>&nbsp;repo.</p>
<p>Make sure you include a not empty&nbsp;<code>README.md</code>&nbsp;in your directory:</p>
<ul>
<li>at the root of your repository&nbsp;<code>zero_day</code></li>
<li>AND in the directory&nbsp;<code>0x03-git</code></li>
</ul>
<p>And important part:&nbsp;<strong>Make sure your commit and push your code to Github - otherwise the Checker will always fail.</strong></p>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
</ul>
</div>
</div>
</div>
</div>
<div id="task-num-2" data-role="task742" data-position="3">
<div id="task-742" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">2. Coding fury road</h3>
</div>
<div class="panel-body">
<p>For the moment we have an empty project directory containing only a&nbsp;<code>README.md</code>. It&rsquo;s time to code!</p>
<ul>
<li>Create these directories at the root of your project:&nbsp;<code>bash</code>,&nbsp;<code>c</code>,&nbsp;<code>js</code></li>
<li>Create these empty files:
<ul>
<li><code>c/c_is_fun.c</code></li>
<li><code>js/main.js</code></li>
<li><code>js/index.js</code></li>
</ul>
</li>
<li>Create a file&nbsp;<code>bash/best</code>&nbsp;with these two lines inside:&nbsp;<code>#!/bin/bash</code>&nbsp;and&nbsp;<code>echo "Best"</code></li>
<li>Create a file&nbsp;<code>bash/school</code>&nbsp;with these two lines inside:&nbsp;<code>#!/bin/bash</code>&nbsp;and&nbsp;<code>echo "School"</code></li>
<li>Add all these new files to git</li>
<li>Commit your changes (message: &ldquo;Starting to code today, so cool&rdquo;) and push to the remote server</li>
</ul>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
<li>Directory:&nbsp;<code>0x03-git</code></li>
<li>File:&nbsp;<code>bash/best, bash/school, c/c_is_fun.c, js/main.js, js/index.js</code></li>
</ul>
</div>
</div>
</div>
</div>
<div id="task-num-3" data-role="task743" data-position="4">
<div id="task-743" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">3. Collaboration is the base of a company</h3>
</div>
<div class="panel-body">
<p>A branch is like a copy of your project. It&rsquo;s used mainly for:</p>
<ul>
<li>adding a feature in development</li>
<li>collaborating on the same project with other developers</li>
<li>not breaking your entire repository</li>
<li>not upsetting your co-workers</li>
</ul>
<p>The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers&rsquo; work.</p>
<p>For this project, create a branch&nbsp;<code>update_script</code>&nbsp;and in this branch:</p>
<ul>
<li>Create an empty file named&nbsp;<code>bash/98</code></li>
<li>Update&nbsp;<code>bash/best</code>&nbsp;by replacing&nbsp;<code>echo "Best"</code>&nbsp;with&nbsp;<code>echo "Best School"</code></li>
<li>Update&nbsp;<code>bash/school</code>&nbsp;by replacing&nbsp;<code>echo "School"</code>&nbsp;with&nbsp;<code>echo "The school is open!"</code></li>
<li>Add and commit these changes (message: &ldquo;My personal work&rdquo;)</li>
<li>Push this new branch&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/w-vaOsoyqzITnQQ2NoSf6g" target="_blank" rel="noopener">Tips</a></li>
</ul>
<p>Perfect! You did an amazing update in your project and it&rsquo;s isolated correctly from the&nbsp;<strong>main</strong>&nbsp;branch.</p>
<p>Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:</p>
<ul>
<li>Change branch to&nbsp;<code>main</code></li>
<li>Update the file&nbsp;<code>bash/best</code>&nbsp;by replacing&nbsp;<code>echo "Best"</code>&nbsp;with&nbsp;<code>echo "This School is so cool!"</code></li>
<li>Delete the directory&nbsp;<code>js</code></li>
<li>Commit your changes (message: &ldquo;Hot fix&rdquo;) and push to the origin</li>
</ul>
<p>Ouf, hot fix is done!</p>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
<li>Directory:&nbsp;<code>0x03-git</code></li>
<li>File:&nbsp;<code>bash/best, bash/school, bash/98</code></li>
</ul>
</div>
</div>
</div>
</div>
<div id="task-num-4" data-role="task744" data-position="5">
<div id="task-744" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">4. Collaboration: be up to date</h3>
</div>
<div class="panel-body">
<p>Of course, you can also work on the same branch as your co-workers and it&rsquo;s best if you keep up to date with their changes.</p>
<p>For this task &ndash;&nbsp;<strong>and only for this task</strong>&nbsp;&ndash; please update your file&nbsp;<code>README.md</code>&nbsp;in the main branch from GitHub.com. It&rsquo;s the&nbsp;<strong>only time</strong>&nbsp;you are allowed to update and commit from GitHub interface.</p>
<p>After you have done that, in your terminal:</p>
<ul>
<li>Get all changes of the main branch locally (i.e. your&nbsp;<code>README.md</code>&nbsp;file will be updated)</li>
<li>Create a new file&nbsp;<code>up_to_date</code>&nbsp;at the root of your directory and in it, write the git command line used</li>
<li>Add&nbsp;<code>up_to_date</code>&nbsp;to git, commit (message: &ldquo;How to be up to date in git&rdquo;), and push to the origin</li>
</ul>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
<li>Directory:&nbsp;<code>0x03-git</code></li>
<li>File:&nbsp;<code>README.md, up_to_date</code></li>
</ul>
</div>
</div>
</div>
</div>
<div id="task-num-5" data-role="task745" data-position="6">
<div id="task-745" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">5. HAAA what did you do???</h3>
</div>
<div class="panel-body">
<p>Collaboration is cool, but not really when you update the same file at the same time&hellip;</p>
<p>To illustrate that, please merge the branch&nbsp;<code>update_script</code>&nbsp;to&nbsp;<code>main</code>: &ldquo;Cool, all my changes will be now part of the main branch, ready to be deployed!&rdquo;</p>
<p><strong>HHHHHHHAAAAAAAA</strong></p>
<pre><code>CONFLICT (content): Merge conflict in bash/best
</code></pre>
<p>As you can see, you have conflicts between two branches on the same file.</p>
<p>Your goal now is to resolve conflicts by using the version of the branch&nbsp;<code>update_script</code>, and push the result to the origin.</p>
<p>At the end, you should have all your work from the branch&nbsp;<code>update_script</code>&nbsp;(new file and two updated files) and all latest&nbsp;<code>main</code>&nbsp;commits (new files, delete folder, etc.),&nbsp;<em>without</em>&nbsp;conflicts.</p>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
<li>Directory:&nbsp;<code>0x03-git</code></li>
</ul>
</div>
</div>
</div>
</div>
<div id="task-num-6" data-role="task746" data-position="10">
<div id="task-746" class="panel panel-default task-card "><span id="user_id" data-id="4543"></span>
<div class="panel-heading panel-heading-actions">
<h3 class="panel-title">6. Never push too much</h3>
</div>
<div class="panel-body">
<p>Create a&nbsp;<code>.gitignore</code>&nbsp;file and define a rule to never push&nbsp;<code>~</code>&nbsp;files (generated by Emacs).&nbsp;<a title="Tips" href="https://intranet.hbtn.io/rltoken/0ANsyvhObT_TYAToY8-lbA" target="_blank" rel="noopener">Tips</a></p>
</div>
<div class="list-group">
<div class="list-group-item">
<p><strong>Repo:</strong></p>
<ul>
<li>GitHub repository:&nbsp;<code>zero_day</code></li>
<li>Directory:&nbsp;<code>0x03-git</code></li>
<li>File:&nbsp;<code>.gitignore</code></li>
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
