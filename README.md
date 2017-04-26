# Yarn-Command-Compare-NPM
Compare command between NPM and YARN

<table>
  <thead>
    <tr>
      <th>npm</th>
      <th>Yarn</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">npm install</code></td>
      <td><code class="highlighter-rouge">yarn install</code></td>
    </tr>
    <tr>
      <td><strong><em>(N/A)</em></strong></td>
      <td><code class="highlighter-rouge">yarn install --flat</code></td>
    </tr>
    <tr>
      <td><strong><em>(N/A)</em></strong></td>
      <td><code class="highlighter-rouge">yarn install --har</code></td>
    </tr>
    <tr>
      <td><strong><em>(N/A)</em></strong></td>
      <td><code class="highlighter-rouge">yarn install --no-lockfile</code></td>
    </tr>
    <tr>
      <td><strong><em>(N/A)</em></strong></td>
      <td><code class="highlighter-rouge">yarn install --pure-lockfile</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm install [package]</code></td>
      <td><strong><em>(N/A)</em></strong></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm install --save [package]</code></td>
      <td><code class="highlighter-rouge">yarn add [package]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm install --save-dev [package]</code></td>
      <td><code class="highlighter-rouge">yarn add [package] [--dev/-D]</code></td>
    </tr>
    <tr>
      <td><strong><em>(N/A)</em></strong></td>
      <td><code class="highlighter-rouge">yarn add [package] [--peer/-P]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm install --save-optional [package]</code></td>
      <td><code class="highlighter-rouge">yarn add [package] [--optional/-O]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm install --save-exact [package]</code></td>
      <td><code class="highlighter-rouge">yarn add [package] [--exact/-E]</code></td>
    </tr>
    <tr>
      <td><strong><em>(N/A)</em></strong></td>
      <td><code class="highlighter-rouge">yarn add [package] [--tilde/-T]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm install --global [package]</code></td>
      <td><code class="highlighter-rouge">yarn global add [package]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm rebuild</code></td>
      <td><code class="highlighter-rouge">yarn install --force</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm uninstall [package]</code></td>
      <td><strong><em>(N/A)</em></strong></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm uninstall --save [package]</code></td>
      <td><code class="highlighter-rouge">yarn remove [package]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm uninstall --save-dev [package]</code></td>
      <td><code class="highlighter-rouge">yarn remove [package]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm uninstall --save-optional [package]</code></td>
      <td><code class="highlighter-rouge">yarn remove [package]</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">npm cache clean</code></td>
      <td><code class="highlighter-rouge">yarn cache clean</code></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">rm -rf node_modules &amp;&amp; npm install</code></td>
      <td><code class="highlighter-rouge">yarn upgrade</code></td>
    </tr>
  </tbody>
  
</table>

Ref : https://yarnpkg.com/lang/en/docs/migrating-from-npm/
