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
    <h2 id="kai1-shi3"><a href="#kai1-shi3">✨ 開始</a></h2>
    <p>
      <a href="https://www.github.com/kwchang0831/svelte-QWER">QWER</a>
      是一個使用
      <a href="https://kit.svelte.dev/">SvelteKit</a>
       與 ❤ 打造的部落格生成器，簡單好用。
    </p>
    <p>沒錯。就是這個網站。</p>
    <h2 id="ma3-shang4-chang2-shi4-kan4-kan4-qwer">
      <a href="#ma3-shang4-chang2-shi4-kan4-kan4-qwer">🎉 馬上嘗試看看 QWER</a>
    </h2>
    <p>
      創建一個 QWER 部落格名字叫做 <code class="inline-code-block">my-blog</code>
      。
    </p>
    <div class="code-block  ">
      <CodeCopy>
        <pre><code
            class="language-sh">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">npx degit kwchang0831/svelte-QWER my-blog</div></div>`}</code></pre>
      </CodeCopy>
    </div>
    <h2 id="kai1-fa1"><a href="#kai1-fa1">⚡️ 開發</a></h2>
    <ol>
      <li>
        <p>
          安裝 <a href="https://github.com/pnpm/pnpm">pnpm</a>
           。
        </p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-bash">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">npm</span> i <span class="token parameter variable">-g</span> <span class="token function">pnpm</span></div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>安裝所有依賴套件。</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> i</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>啟動本地端測試伺服器。</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> dev</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>本地端測試伺服器已經在運行。打開瀏覽器看看成果。</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">VITE v3.0.8  ready <span class="token keyword">in</span> <span class="token number">1080</span> ms</div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"></div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Local:   http://localhost:5173/</div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Network: use <span class="token parameter variable">--host</span> to expose</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
    </ol>
    <h2 id="jian4-zhi4"><a href="#jian4-zhi4">🔧 建置</a></h2>
    <ol>
      <li>
        <p>建置一個 production 版本的部落格</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> build</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>在本地預覽已建置好的部落格</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content"><span class="token function">pnpm</span> preview</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
      <li>
        <p>本地預覽伺服器已經在運行。打開瀏覽器看看成果。</p>
        <div class="code-block  ">
          <CodeCopy>
            <pre><code
                class="language-shell">{@html String.raw`<div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Local:   http://localhost:4173/</div></div><div class="code-line"><div class="code-linenotation"><span class="no-line-number"></span><span class="no-line-diff"></span></div><div class="code-content">➜  Network: use <span class="token parameter variable">--host</span> to expose</div></div>`}</code></pre>
          </CodeCopy>
        </div>
      </li>
    </ol>
    <h2 id="bu4-shu3"><a href="#bu4-shu3">🚀 部署</a></h2>
    <p>
      創建 <a href="https://vercel.com/">Vercel</a>
      或
      <a href="https://www.netlify.com/">Netlify</a>
      的
      <strong>免費帳號</strong>
      來進行部署。
    </p>
    <h2 id="le-jie3-geng4-duo1"><a href="#le-jie3-geng4-duo1">🙋 了解更多</a></h2>
    <p>
      需要更多訊息? 請參考 <a href="/intro-to-QWER">Intro to QWER</a>
      。
    </p>
    <h2 id="wan2-jie2"><a href="#wan2-jie2">👍 完結</a></h2>
  </article>
</Post>
