---
output: hugodown::md_document
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Test post"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-06-16
lastmod: 2020-06-16
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
rmd_hash: c06ea2d3c4575807

---

Hello, this is a test post.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'><a href='https://rdrr.io/r/base/print.html'>print</a></span>(<span class='s'>"This is an R chunk"</span>)
<span class='c'>#&gt; [1] "This is an R chunk"</span>
<span class='nf'><a href='https://rdrr.io/r/base/c.html'>c</a></span>(<span class='m'>1</span>, <span class='m'>2</span>, <span class='m'>3</span>, <span class='m'>4</span>)
<span class='c'>#&gt; [1] 1 2 3 4</span></code></pre>

</div>

The below recreates the above R chunk, but with a Python list instead of an R vector. We can see that the input for the list appears as `NA` in the markdown file, although the output is unaffected.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'><span class='nf'><a href='https://rdrr.io/r/base/print.html'>print</a></span>(<span class='s'>"This is a python chunk"</span>)
<span class='c'>#&gt; This is a python chunk</span>
NA
<span class='c'>#&gt; [1, 2, 3, 4]</span></code></pre>

</div>

The below contains a single line of bash: `echo 'This is a bash chunk'`. Again, the input is `NA`, but the output is unaffected.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'>NA

<span class='c'>#&gt; This is a bash chunk</span></code></pre>

</div>

Let's try scala now. The below line of code is `(1 to 4).foreach(println(_))`, which prints the integers each on a new line.

<div class="highlight">

<pre class='chroma'><code class='language-r' data-lang='r'>NA

<span class='c'>#&gt; 1</span>
<span class='c'>#&gt; 2</span>
<span class='c'>#&gt; 3</span>
<span class='c'>#&gt; 4</span></code></pre>

</div>

