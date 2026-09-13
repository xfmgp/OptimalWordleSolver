<ol>
  <li style="margin-bottom: 15px;">
    Fork your own copy of <a href="https://github.com/nkoppel/OptimalWordleSolver">nkoppel/OptimalWordleSolver</a>
  </li>
  <br>
  <li>
    Upload your own custom list of guess and solution words to <code>/words</code>, if any
    <ul>
      <li style="list-style-type: circle;">Under <code>/src</code>, edit the txt paths in <code>words.rs</code> accordingly</li>
    </ul>
  </li>
  <li>
    Return to (root) and select <strong>Code &gt; Codespaces &gt; Create codespace on main</strong>
  </li>
  <li>
    Once you're redirected to the codespace, run the following commands:
    <pre><code>curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh</code></pre>
    <p>Enter <code>1</code> when prompted</p>
    <pre><code>source "$HOME/.cargo/env"</code></pre>
    <pre><code>rustup default nightly</code></pre>
    <pre><code>cargo run</code></pre>
  </li>
  <li>
    Download the output <code>solution.txt</code> under the Explorer view and upload it to <a href="https://ylarp.github.io/OptimalWordleSolver">ylarp.github.io/OptimalWordleSolver</a>
  </li>
</ol>
