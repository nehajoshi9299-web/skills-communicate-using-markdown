<h1>#Daily Learning</h1>

<h2>##Morning Planning</h2>

<ul>
  <li>
    <input type="checkbox">
    Check out the <a href="https://github.blog/">GitHub Blog</a> for topic ideas.
  </li>
  <li>
    <input type="checkbox">
    Learn about <a href="https://skills.github.com/#first-day-on-github">GitHub Pages</a>.
  </li>
  <li>
    <input type="checkbox">
    Convert my first blog post into an actual webpage.
  </li>
</ul>

<h2>##Review</h2>
<h2>### Awesome Code Snippet</h2>
<p>
  Convert an image or video from dark mode to light mode using
  <a href="https://www.ffmpeg.org">ffmpeg</a>.
</p>

<pre><code class="language-bash">
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
</code></pre>
