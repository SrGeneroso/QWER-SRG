<!-- auto-generated by QWER -->
<script lang="ts">
  /* eslint-disable @typescript-eslint/ban-ts-comment */
  // @ts-nocheck
  import Post from '$lib/layouts/post.svelte';
  import ImgZoom from '$lib/components/image_zoom.svelte';
  import Video from '$lib/components/video.svelte';
  import CodeCopy from '$lib/components/code_copy.svelte';
  import InfoBox from '$lib/components/info_box.svelte';
</script>

<Post>
  <article slot="post_content">
    <h2 id="intro"><a href="#intro">✨ Intro</a></h2>
    <p>
      <a href="https://www.github.com/kwchang0831/svelte-QWER">QWER</a>
      is simply an Awesoem blog starter / static site generator. Built using
      <a href="https://kit.svelte.dev/">SvelteKit</a>
       with ❤.
    </p>
    <h2 id="try-out-qwer"><a href="#try-out-qwer">🎉 Try out QWER</a></h2>
    <p>
      Create a QWER blog named <code class="inline-code-block">my-blog</code>
      .
    </p>
    <div class="code-block  ">
      <CodeCopy>
        <pre><code
            class="language-sh">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">npx degit kwchang0831/svelte-QWER my-blog</div></div>`}</code></pre>
      </CodeCopy>
    </div>
    <h2 id="to-dev"><a href="#to-dev">⚡️ To Dev</a></h2>
    <ol>
      <li>
        <p>Install all the dependencies.</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> i</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>Start local dev server.</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> dev</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>Sever is running. Open browser to see the result.</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">VITE v3.0.8  ready <span class="token keyword">in</span> <span class="token number">1080</span> ms</div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"></div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Local:   http://localhost:5173/</div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Network: use <span class="token parameter variable">--host</span> to expose</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
    </ol>
    <h2 id="to-build"><a href="#to-build">🔧 To Build</a></h2>
    <ol>
      <li>
        <p>Create production version of your blog.</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> build</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>Preview the build.</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> preview</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>Preview server is running. Open browser to see the result.</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Local:   http://localhost:4173/</div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Network: use <span class="token parameter variable">--host</span> to expose</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
    </ol>
    <h2 id="to-deploy"><a href="#to-deploy">🚀 To Deploy</a></h2>
    <p>
      Create a <a href="https://vercel.com/">Vercel</a>
      or
      <a href="https://www.netlify.com/">Netlify</a>
      <strong>free account</strong>
       to deploy.
    </p>
    <h2 id="more"><a href="#more">🙋 More</a></h2>
    <p>
      For more detail information, please check <a href="/intro-to-QWER">Intro to QWER</a>
      .
    </p>
    <h2 id="end"><a href="#end">👍 END</a></h2>
  </article>
</Post>
