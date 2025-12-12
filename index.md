---
layout: none
---

<html>
<head>
<link rel="stylesheet" href="assets/css/style.css">
</head>

<body>

<div class="container">

<div class="sidebar">
    <img src="assets/profile.png" alt="Profile">

    <h2>Jibbran Ali</h2>
    <a href="https://github.com/JibbranAli" target="_blank">GitHub Profile</a>
    <a href="https://www.linkedin.com/in/jibbran-ali/" target="_blank">LinkedIn</a>

    <hr style="border-color:#333; margin:20px 0;">

    <h3>Documentation</h3>
    <a href="#basic">Basic Commands</a>
    <a href="#branching">Branching</a>
    <a href="#merging">Merging</a>
    <a href="#history">History Inspection</a>
    <a href="#undo">Undoing Work</a>
    <a href="#remote">Remote Work</a>
    <a href="#maintenance">Maintenance</a>
    <a href="#advanced">Advanced Git</a>
</div>

<div class="content">

<h1>Git Commands Documentation</h1>
<p>A complete, professionally structured Git command reference.</p>


<!-- BASIC -->
<h2 id="basic" class="section-title">Basic Commands</h2>

<h3>git init</h3>
<pre><code>git init</code></pre>

<h3>git add</h3>
<pre><code>git add .</code></pre>

<h3>git commit</h3>
<pre><code>git commit -m "Initial commit"</code></pre>

<h3>git status</h3>
<pre><code>git status</code></pre>



<!-- BRANCHING -->
<h2 id="branching" class="section-title">Branching</h2>

<h3>Create branch</h3>
<pre><code>git branch feature-login</code></pre>

<h3>Switch branch</h3>
<pre><code>git switch feature-login</code></pre>



<!-- MERGING -->
<h2 id="merging" class="section-title">Merging</h2>

<h3>Fast-forward merge</h3>
<pre><code>git merge feature</code></pre>

<h3>Squash merge</h3>
<pre><code>git merge --squash feature</code></pre>



<!-- HISTORY -->
<h2 id="history" class="section-title">History Inspection</h2>

<h3>git log</h3>
<pre><code>git log --oneline --graph --decorate --all</code></pre>

<h3>Show commit</h3>
<pre><code>git show &lt;commit&gt;</code></pre>



<!-- UNDO -->
<h2 id="undo" class="section-title">Undoing Work</h2>

<h3>Reset</h3>
<pre><code>git reset --hard HEAD~1</code></pre>

<h3>Revert</h3>
<pre><code>git revert &lt;commit&gt;</code></pre>



<!-- REMOTE -->
<h2 id="remote" class="section-title">Remote Work</h2>

<h3>Push</h3>
<pre><code>git push origin main</code></pre>

<h3>Fetch</h3>
<pre><code>git fetch</code></pre>



<!-- MAINTENANCE -->
<h2 id="maintenance" class="section-title">Maintenance</h2>

<h3>Garbage collection</h3>
<pre><code>git gc --aggressive</code></pre>



<!-- ADVANCED -->
<h2 id="advanced" class="section-title">Advanced Git</h2>

<h3>Rebase</h3>
<pre><code>git rebase main</code></pre>

<h3>Cherry-pick</h3>
<pre><code>git cherry-pick &lt;commit&gt;</code></pre>


</div>
</div>

</body>
</html>
