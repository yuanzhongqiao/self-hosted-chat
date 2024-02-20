<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-before-you-get-started" class="anchor" aria-hidden="true" tabindex="-1" href="#before-you-get-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始之前</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请</font></font><a href="https://developers.revolt.chat/faq/usage#guidelines-for-third-party-instances" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在运行您自己的服务器之前阅读常见问题解答</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并且您可能需要阅读有关</font></font><a href="https://developers.revolt.chat/faq/instances" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第三方实例的其他说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-errata-notice" class="anchor" aria-hidden="true" tabindex="-1" href="#errata-notice"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">勘误通知</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">amd64 版本目前仅适用于</font></font><code>backend</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>bonfire</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">镜像，未来还会有更多。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">❗</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要提示</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：如果您在</font></font><a href="https://github.com/minio/docs/issues/624#issuecomment-1296608406" data-hovercard-type="issue" data-hovercard-url="/minio/docs/issues/624/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2022 年 10 月 29 日</font></font></a><font style="vertical-align: inherit;"></font><code>minio</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">之前部署了 Revolt，并且配置为“fs”模式，
</font><font style="vertical-align: inherit;">则可能需要标记映像版本。</font></font><div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">image</span>: <span class="pl-s">minio/minio:RELEASE.2022-10-24T18-35-07Z</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="image: minio/minio:RELEASE.2022-10-24T18-35-07Z" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">❗</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要提示</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：如果您在</font></font><a href="https://github.com/revoltchat/backend/commit/32542a822e3de0fc8cc7b29af46c54a9284ee2de"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 4 月 21 日</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">之前部署了 Revolt ，则可能需要刷新 Redis 数据库。
</font></font><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> for stock Redis and older KeyDB images:</span>
docker-compose <span class="pl-c1">exec</span> redis redis-cli
<span class="pl-c"><span class="pl-c">#</span> ...or for newer KeyDB images:</span>
docker-compose <span class="pl-c1">exec</span> redis keydb-cli

<span class="pl-c"><span class="pl-c">#</span> then run:</span>
FLUSHDB</pre><div class="zeroclipboard-container">
    
  </div></div>
</li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-quick-start" class="anchor" aria-hidden="true" tabindex="-1" href="#quick-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库提供了合理的默认值，因此您可以立即在本地计算机上开始使用它。</font></font></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
不建议将其用于生产用途 - 请参阅下面的完整指南。</font></font></p>
</blockquote>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/revoltchat/self-hosted revolt
<span class="pl-c1">cd</span> revolt
cp .env.example .env
docker-compose up -d</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后只需访问</font></font><a href="http://local.revolt.chat" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://local.revolt.chat</font></font></a></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-setup" class="anchor" aria-hidden="true" tabindex="-1" href="#setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">继续之前的先决条件：</font></font></p>
<ul dir="auto">
<li><a href="https://www.docker.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人</font></font></a></li>
<li><a href="https://docs.docker.com/compose/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 组合</font></font></a></li>
<li><a href="https://git-scm.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">git</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆这个存储库。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/revoltchat/self-hosted revolt
<span class="pl-c1">cd</span> revolt</pre><div class="zeroclipboard-container">
     
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">复制</font></font><code>.env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件并根据您的需要进行编辑。</font></font></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：默认配置用于测试，仅适用于您的本地计算机。</font><font style="vertical-align: inherit;">如果要部署到远程服务器，则需要编辑文件中的 URL ，请参阅下面有关</font><a href="#custom-domain"><font style="vertical-align: inherit;">配置自定义域的</font></a></font><code>.env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">
如果您在尝试登录时遇到网络错误，</font><strong><font style="vertical-align: inherit;">请在提出问题之前仔细检查您的配置。</font></strong></font><a href="#custom-domain"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><br><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"></font></strong></p>
</blockquote>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>cp .env.example .env</pre><div class="zeroclipboard-container">
  
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后提出Revolt：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-compose up -d</pre><div class="zeroclipboard-container">
     
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-updating-revolt" class="anchor" aria-hidden="true" tabindex="-1" href="#updating-revolt"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新Revolt</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在更新 Revolt 之前，请检查顶部的勘误表以获取重要信息，并检查文件中现在是否存在任何新的必需环境变量</font></font><code>.env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要更新 Revolt，请首先提取此存储库的最新副本，以确保您拥有最新的标签：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git pull</pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后拉取所有最新的镜像：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-compose pull</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在您可以重新启动您的服务：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker-compose up -d</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker-compose up -d" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-additional-notes" class="anchor" aria-hidden="true" tabindex="-1" href="#additional-notes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">补充笔记</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-custom-domain" class="anchor" aria-hidden="true" tabindex="-1" href="#custom-domain"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义域</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要配置自定义域，您应该能够</font></font><code>local.revolt.chat</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font><code>.env</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件中进行搜索和替换，如下所示：</font></font></p>
<div class="highlight highlight-source-diff notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> .env</span>
<span class="pl-md"><span class="pl-md">-</span> REVOLT_APP_URL=http://local.revolt.chat</span>
<span class="pl-mi1"><span class="pl-mi1">+</span> REVOLT_APP_URL=http://my.domain</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# .env
- REVOLT_APP_URL=http://local.revolt.chat
+ REVOLT_APP_URL=http://my.domain" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还需要更改协议以启用 HTTPS：</font></font></p>
<div class="highlight highlight-source-diff notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> .env</span>
<span class="pl-md"><span class="pl-md">-</span> REVOLT_APP_URL=http://my.domain</span>
<span class="pl-mi1"><span class="pl-mi1">+</span> REVOLT_APP_URL=https://my.domain</span>

<span class="pl-md"><span class="pl-md">-</span> REVOLT_EXTERNAL_WS_URL=ws://my.domain/ws</span>
<span class="pl-mi1"><span class="pl-mi1">+</span> REVOLT_EXTERNAL_WS_URL=wss://my.domain/ws</span></pre><div class="zeroclipboard-container">
     
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 的情况下</font></font><code>HOSTNAME</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您必须去除协议前缀：</font></font></p>
<div class="highlight highlight-source-diff notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> .env</span>
<span class="pl-md"><span class="pl-md">-</span> HOSTNAME=https://my.domain</span>
<span class="pl-mi1"><span class="pl-mi1">+</span> HOSTNAME=my.domain</span></pre><div class="zeroclipboard-container">
   
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-putting-revolt-behind-another-reverse-proxy-or-on-a-non-standard-port" class="anchor" aria-hidden="true" tabindex="-1" href="#putting-revolt-behind-another-reverse-proxy-or-on-a-non-standard-port"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 Revolt 置于另一个反向代理后面（或非标准端口上）</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">覆盖 上的端口定义</font></font><code>caddy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> docker-compose.yml</span>
<span class="pl-ent">services</span>:
  <span class="pl-ent">caddy</span>:
    <span class="pl-ent">ports</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>1234:80<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    
  </div></div>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
Git 不会忽略此文件，使用覆盖文件可能就足够了，但不会删除端口 80 / 443 分配。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更新 Web 服务器使用的主机名：</font></font></p>
<div class="highlight highlight-source-diff notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> .env</span>
<span class="pl-md"><span class="pl-md">-</span> HOSTNAME=http://local.revolt.chat</span>
<span class="pl-mi1"><span class="pl-mi1">+</span> HOSTNAME=:80</span></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您现在可以反向代理到</font></font><a href="http://localhost:1234" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:1234</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-expose-database" class="anchor" aria-hidden="true" tabindex="-1" href="#expose-database"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公开数据库</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过添加端口定义来不安全地公开数据库：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> docker-compose.override.yml</span>
<span class="pl-ent">services</span>:
  <span class="pl-ent">database</span>:
    <span class="pl-ent">ports</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>27017:27017<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
  
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-mongo-compatibility" class="anchor" aria-hidden="true" tabindex="-1" href="#mongo-compatibility"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mongo兼容性</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">较旧的处理器可能不支持最新的 MongoDB 版本，您可以固定到 MongoDB 4.4，如下所示：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> docker-compose.override.yml</span>
<span class="pl-ent">services</span>:
  <span class="pl-ent">database</span>:
    <span class="pl-ent">image</span>: <span class="pl-s">mongo:4.4</span></pre><div class="zeroclipboard-container">
   
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-making-your-instance-invite-only" class="anchor" aria-hidden="true" tabindex="-1" href="#making-your-instance-invite-only"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使您的实例仅供受邀者使用</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过设置</font></font><code>REVOLT_INVITE_ONLY</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启用</font><font style="vertical-align: inherit;">仅限邀请模式</font></font><code>.env</code><font style="vertical-align: inherit;"></font><code>1</code></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建邀请：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> drop into mongo shell</span>
docker-compose <span class="pl-c1">exec</span> database mongosh

<span class="pl-c"><span class="pl-c">#</span> create the invite</span>
use revolt
db.invites.insertOne({ _id: <span class="pl-s"><span class="pl-pds">"</span>enter_an_invite_code_here<span class="pl-pds">"</span></span> })</pre><div class="zeroclipboard-container">
  
  </div></div>
</article></div>
