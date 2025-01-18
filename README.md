
<!doctype html>
<html lang="en" dir="ltr" class="docs-wrapper plugin-docs plugin-id-default docs-version-current docs-doc-page docs-doc-id-intro" data-has-hydrated="false">
<head>
<meta charset="UTF-8">
<meta name="generator" content="Docusaurus v3.6.3">
<title data-rh="true">Introduction to Eliza | eliza</title><meta data-rh="true" name="viewport" content="width=device-width,initial-scale=1"><meta data-rh="true" name="twitter:card" content="summary_large_image"><meta data-rh="true" property="og:url" content="https://elizaos.github.io/eliza/docs/intro/"><meta data-rh="true" property="og:locale" content="en"><meta data-rh="true" name="docusaurus_locale" content="en"><meta data-rh="true" name="docsearch:language" content="en"><meta data-rh="true" name="docusaurus_version" content="current"><meta data-rh="true" name="docusaurus_tag" content="docs-default-current"><meta data-rh="true" name="docsearch:version" content="current"><meta data-rh="true" name="docsearch:docusaurus_tag" content="docs-default-current"><meta data-rh="true" property="og:title" content="Introduction to Eliza | eliza"><meta data-rh="true" name="description" content="As seen powering @DegenSpartanAI and @MarcAIndreessen"><meta data-rh="true" property="og:description" content="As seen powering @DegenSpartanAI and @MarcAIndreessen"><link data-rh="true" rel="icon" href="/eliza/img/favicon.ico"><link data-rh="true" rel="canonical" href="https://elizaos.github.io/eliza/docs/intro/"><link data-rh="true" rel="alternate" href="https://elizaos.github.io/eliza/docs/intro/" hreflang="en"><link data-rh="true" rel="alternate" href="https://elizaos.github.io/eliza/docs/intro/" hreflang="x-default"><link rel="stylesheet" href="/eliza/assets/css/styles.342a7926.css">
<script src="/eliza/assets/js/runtime~main.0e5ee345.js" defer="defer"></script>
<script src="/eliza/assets/js/main.9856e0dd.js" defer="defer"></script>
</head>
<body class="navigation-with-keyboard">
<script>!function(){function t(t){document.documentElement.setAttribute("data-theme",t)}var e=function(){try{return new URLSearchParams(window.location.search).get("docusaurus-theme")}catch(t){}}()||function(){try{return window.localStorage.getItem("theme")}catch(t){}}();null!==e?t(e):window.matchMedia("(prefers-color-scheme: dark)").matches?t("dark"):window.matchMedia("(prefers-color-scheme: light)").matches?t("light"):t("dark")}(),function(){try{const c=new URLSearchParams(window.location.search).entries();for(var[t,e]of c)if(t.startsWith("docusaurus-data-")){var a=t.replace("docusaurus-data-","data-");document.documentElement.setAttribute(a,e)}}catch(t){}}()</script><div id="__docusaurus"><div role="region" aria-label="Skip to main content"><a class="skipToContent_fXgn" href="#__docusaurus_skipToContent_fallback">Skip to main content</a></div><nav aria-label="Main" class="navbar navbar--fixed-top"><div class="navbar__inner"><div class="navbar__items"><button aria-label="Toggle navigation bar" aria-expanded="false" class="navbar__toggle clean-btn" type="button"><svg width="30" height="30" viewBox="0 0 30 30" aria-hidden="true"><path stroke="currentColor" stroke-linecap="round" stroke-miterlimit="10" stroke-width="2" d="M4 7h22M4 15h22M4 23h22"></path></svg></button><a class="navbar__brand" href="/eliza/"><div class="navbar__logo"><img src="/eliza/img/favicon.ico" alt="Eliza Logo" class="themedComponent_mlkZ themedComponent--light_NVdE"><img src="/eliza/img/favicon.ico" alt="Eliza Logo" class="themedComponent_mlkZ themedComponent--dark_xIcU"></div><b class="navbar__title text--truncate">eliza</b></a><a aria-current="page" class="navbar__item navbar__link navbar__link--active" href="/eliza/docs/intro/">Documentation</a><a class="navbar__item navbar__link" href="/eliza/api/">API</a><a class="navbar__item navbar__link" href="/eliza/community/">Community</a></div><div class="navbar__items navbar__items--right"><a href="https://github.com/elizaos/eliza" target="_blank" rel="noopener noreferrer" class="navbar__item navbar__link">GitHub<svg width="13.5" height="13.5" aria-hidden="true" viewBox="0 0 24 24" class="iconExternalLink_nPIU"><path fill="currentColor" d="M21 13v10h-21v-19h12v2h-10v15h17v-8h2zm3-12h-10.988l4.035 4-6.977 7.07 2.828 2.828 6.977-7.07 4.125 4.172v-11z"></path></svg></a><div class="toggle_vylO colorModeToggle_DEke"><button class="clean-btn toggleButton_gllP toggleButtonDisabled_aARS" type="button" disabled="" title="Switch between dark and light mode (currently dark mode)" aria-label="Switch between dark and light mode (currently dark mode)" aria-live="polite" aria-pressed="true"><svg viewBox="0 0 24 24" width="24" height="24" class="lightToggleIcon_pyhR"><path fill="currentColor" d="M12,9c1.65,0,3,1.35,3,3s-1.35,3-3,3s-3-1.35-3-3S10.35,9,12,9 M12,7c-2.76,0-5,2.24-5,5s2.24,5,5,5s5-2.24,5-5 S14.76,7,12,7L12,7z M2,13l2,0c0.55,0,1-0.45,1-1s-0.45-1-1-1l-2,0c-0.55,0-1,0.45-1,1S1.45,13,2,13z M20,13l2,0c0.55,0,1-0.45,1-1 s-0.45-1-1-1l-2,0c-0.55,0-1,0.45-1,1S19.45,13,20,13z M11,2v2c0,0.55,0.45,1,1,1s1-0.45,1-1V2c0-0.55-0.45-1-1-1S11,1.45,11,2z M11,20v2c0,0.55,0.45,1,1,1s1-0.45,1-1v-2c0-0.55-0.45-1-1-1C11.45,19,11,19.45,11,20z M5.99,4.58c-0.39-0.39-1.03-0.39-1.41,0 c-0.39,0.39-0.39,1.03,0,1.41l1.06,1.06c0.39,0.39,1.03,0.39,1.41,0s0.39-1.03,0-1.41L5.99,4.58z M18.36,16.95 c-0.39-0.39-1.03-0.39-1.41,0c-0.39,0.39-0.39,1.03,0,1.41l1.06,1.06c0.39,0.39,1.03,0.39,1.41,0c0.39-0.39,0.39-1.03,0-1.41 L18.36,16.95z M19.42,5.99c0.39-0.39,0.39-1.03,0-1.41c-0.39-0.39-1.03-0.39-1.41,0l-1.06,1.06c-0.39,0.39-0.39,1.03,0,1.41 s1.03,0.39,1.41,0L19.42,5.99z M7.05,18.36c0.39-0.39,0.39-1.03,0-1.41c-0.39-0.39-1.03-0.39-1.41,0l-1.06,1.06 c-0.39,0.39-0.39,1.03,0,1.41s1.03,0.39,1.41,0L7.05,18.36z"></path></svg><svg viewBox="0 0 24 24" width="24" height="24" class="darkToggleIcon_wfgR"><path fill="currentColor" d="M9.37,5.51C9.19,6.15,9.1,6.82,9.1,7.5c0,4.08,3.32,7.4,7.4,7.4c0.68,0,1.35-0.09,1.99-0.27C17.45,17.19,14.93,19,12,19 c-3.86,0-7-3.14-7-7C5,9.07,6.81,6.55,9.37,5.51z M12,3c-4.97,0-9,4.03-9,9s4.03,9,9,9s9-4.03,9-9c0-0.46-0.04-0.92-0.1-1.36 c-0.98,1.37-2.58,2.26-4.4,2.26c-2.98,0-5.4-2.42-5.4-5.4c0-1.81,0.89-3.42,2.26-4.4C12.92,3.04,12.46,3,12,3L12,3z"></path></svg></button></div><div class="navbarSearchContainer_Bca1"><div class="navbar__search"><span aria-label="expand searchbar" role="button" class="search-icon" tabindex="0"></span><input id="search_input_react" type="search" placeholder="Loading..." aria-label="Search" class="navbar__search-input search-bar" disabled=""></div></div></div></div><div role="presentation" class="navbar-sidebar__backdrop"></div></nav><div id="__docusaurus_skipToContent_fallback" class="main-wrapper mainWrapper_z2l0"><div class="docsWrapper_hBAB"><button aria-label="Scroll back to top" class="clean-btn theme-back-to-top-button backToTopButton_sjWU" type="button"></button><div class="docRoot_UBD9"><aside class="theme-doc-sidebar-container docSidebarContainer_YfHR"><div class="sidebarViewport_aRkj"><div class="sidebar_njMd"><nav aria-label="Docs sidebar" class="menu thin-scrollbar menu_SIkG"><ul class="theme-doc-sidebar-menu menu__list"><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-1 menu__list-item"><a class="menu__link menu__link--active" aria-current="page" href="/eliza/docs/intro/">🚀 Introduction</a></li><li class="theme-doc-sidebar-item-category theme-doc-sidebar-item-category-level-1 menu__list-item"><div class="menu__list-item-collapsible"><a class="menu__link menu__link--sublist menu__link--sublist-caret" role="button" aria-expanded="true" href="/eliza/docs/quickstart/">🏁 Getting Started</a></div><ul style="display:block;overflow:visible;height:auto" class="menu__list"><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/quickstart/">⭐ Quick Start</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/faq/">❓ FAQ</a></li></ul></li><li class="theme-doc-sidebar-item-category theme-doc-sidebar-item-category-level-1 menu__list-item"><div class="menu__list-item-collapsible"><a class="menu__link menu__link--sublist menu__link--sublist-caret" role="button" aria-expanded="true" href="/eliza/docs/core/characterfile/">🧠 Core Concepts</a></div><ul style="display:block;overflow:visible;height:auto" class="menu__list"><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/core/characterfile/">Character Files</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/core/agents/">Agents</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/core/providers/">Providers</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/core/actions/">Actions</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/core/evaluators/">Evaluators</a></li></ul></li><li class="theme-doc-sidebar-item-category theme-doc-sidebar-item-category-level-1 menu__list-item"><div class="menu__list-item-collapsible"><a class="menu__link menu__link--sublist menu__link--sublist-caret" role="button" aria-expanded="true" href="/eliza/docs/guides/configuration/">📘 Guides</a></div><ul style="display:block;overflow:visible;height:auto" class="menu__list"><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/guides/configuration/">Configuration</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/guides/advanced/">Advanced Usage</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/guides/secrets-management/">Secrets Management</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/guides/local-development/">Local Development</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/guides/wsl/">WSL Setup</a></li></ul></li><li class="theme-doc-sidebar-item-category theme-doc-sidebar-item-category-level-1 menu__list-item"><div class="menu__list-item-collapsible"><a class="menu__link menu__link--sublist menu__link--sublist-caret" role="button" aria-expanded="true" href="/eliza/docs/advanced/fine-tuning/">🎓 Advanced Topics</a></div><ul style="display:block;overflow:visible;height:auto" class="menu__list"><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/advanced/fine-tuning/">Fine-tuning</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/advanced/infrastructure/">Infrastructure</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/advanced/trust-engine/">Trust Engine</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/advanced/autonomous-trading/">Autonomous Trading</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/advanced/eliza-in-tee/">Eliza in TEE</a></li></ul></li><li class="theme-doc-sidebar-item-category theme-doc-sidebar-item-category-level-1 menu__list-item"><div class="menu__list-item-collapsible"><a class="menu__link menu__link--sublist menu__link--sublist-caret" role="button" aria-expanded="true" href="/eliza/docs/packages/">📦 Packages</a></div><ul style="display:block;overflow:visible;height:auto" class="menu__list"><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/packages/">Overview</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/packages/core/">Core Package</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/packages/adapters/">Database Adapters</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/packages/clients/">Client Packages</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/packages/agent/">Agent Package</a></li><li class="theme-doc-sidebar-item-link theme-doc-sidebar-item-link-level-2 menu__list-item"><a class="menu__link" tabindex="0" href="/eliza/docs/packages/plugins/">Plugin System</a></li></ul></li></ul></nav><button type="button" title="Collapse sidebar" aria-label="Collapse sidebar" class="button button--secondary button--outline collapseSidebarButton_PEFL"><svg width="20" height="20" aria-hidden="true" class="collapseSidebarButtonIcon_kv0_"><g fill="#7a7a7a"><path d="M9.992 10.023c0 .2-.062.399-.172.547l-4.996 7.492a.982.982 0 01-.828.454H1c-.55 0-1-.453-1-1 0-.2.059-.403.168-.551l4.629-6.942L.168 3.078A.939.939 0 010 2.528c0-.548.45-.997 1-.997h2.996c.352 0 .649.18.828.45L9.82 9.472c.11.148.172.347.172.55zm0 0"></path><path d="M19.98 10.023c0 .2-.058.399-.168.547l-4.996 7.492a.987.987 0 01-.828.454h-3c-.547 0-.996-.453-.996-1 0-.2.059-.403.168-.551l4.625-6.942-4.625-6.945a.939.939 0 01-.168-.55 1 1 0 01.996-.997h3c.348 0 .649.18.828.45l4.996 7.492c.11.148.168.347.168.55zm0 0"></path></g></svg></button></div></div></aside><main class="docMainContainer_TBSr"><div class="container padding-top--md padding-bottom--lg"><div class="row"><div class="col docItemCol_VOVn"><div class="docItemContainer_Djhp"><article><nav class="theme-doc-breadcrumbs breadcrumbsContainer_Z_bl" aria-label="Breadcrumbs"><ul class="breadcrumbs" itemscope="" itemtype="https://schema.org/BreadcrumbList"><li class="breadcrumbs__item"><a aria-label="Home page" class="breadcrumbs__link" href="/eliza/"><svg viewBox="0 0 24 24" class="breadcrumbHomeIcon_YNFT"><path d="M10 19v-5h4v5c0 .55.45 1 1 1h3c.55 0 1-.45 1-1v-7h1.7c.46 0 .68-.57.33-.87L12.67 3.6c-.38-.34-.96-.34-1.34 0l-8.36 7.53c-.34.3-.13.87.33.87H5v7c0 .55.45 1 1 1h3c.55 0 1-.45 1-1z" fill="currentColor"></path></svg></a></li><li itemscope="" itemprop="itemListElement" itemtype="https://schema.org/ListItem" class="breadcrumbs__item breadcrumbs__item--active"><span class="breadcrumbs__link" itemprop="name">🚀 Introduction</span><meta itemprop="position" content="1"></li></ul></nav><div class="tocCollapsible_ETCw theme-doc-toc-mobile tocMobile_ITEo"><button type="button" class="clean-btn tocCollapsibleButton_TO0P">On this page</button></div><div class="theme-doc-markdown markdown"><header><h1>Introduction to Eliza</h1></header>
<p><img decoding="async" loading="lazy" src="/eliza/assets/images/eliza_banner-ab8921c786c75d3716bd237159da3bdc.jpg" width="2043" height="492" class="img_ev3q"></p>
<p><em>As seen powering <a href="https://x.com/degenspartanai" target="_blank" rel="noopener noreferrer">@DegenSpartanAI</a> and <a href="https://x.com/pmairca" target="_blank" rel="noopener noreferrer">@MarcAIndreessen</a></em></p>
<h2 class="anchor anchorWithStickyNavbar_LWe7" id="what-is-eliza">What is Eliza?<a href="#what-is-eliza" class="hash-link" aria-label="Direct link to What is Eliza?" title="Direct link to What is Eliza?">​</a></h2>
<p>Eliza is a powerful multi-agent simulation framework designed to create, deploy, and manage autonomous AI agents. Built with TypeScript, it provides a flexible and extensible platform for developing intelligent agents that can interact across multiple platforms while maintaining consistent personalities and knowledge.</p>
<h2 class="anchor anchorWithStickyNavbar_LWe7" id="key-features">Key Features<a href="#key-features" class="hash-link" aria-label="Direct link to Key Features" title="Direct link to Key Features">​</a></h2>
<h3 class="anchor anchorWithStickyNavbar_LWe7" id="core-capabilities">Core Capabilities<a href="#core-capabilities" class="hash-link" aria-label="Direct link to Core Capabilities" title="Direct link to Core Capabilities">​</a></h3>
<ul>
<li><strong>Multi-Agent Architecture</strong>: Deploy and manage multiple unique AI personalities simultaneously</li>
<li><strong>Character System</strong>: Create diverse agents using the <a href="https://github.com/lalalune/characterfile/" target="_blank" rel="noopener noreferrer">characterfile</a> framework</li>
<li><strong>Memory Management</strong>: Advanced RAG (Retrieval Augmented Generation) system for long-term memory and context awareness</li>
<li><strong>Platform Integration</strong>: Seamless connectivity with Discord, Twitter, and other platforms</li>
</ul>
<h3 class="anchor anchorWithStickyNavbar_LWe7" id="communication--media">Communication &amp; Media<a href="#communication--media" class="hash-link" aria-label="Direct link to Communication &amp; Media" title="Direct link to Communication &amp; Media">​</a></h3>
<ul>
<li>
<p><strong>Multi-Platform Support</strong>:</p>
<ul>
<li>Full-featured Discord integration with voice channel support</li>
<li>Twitter/X bot capabilities</li>
<li>Telegram integration</li>
<li>Direct API access</li>
</ul>
</li>
<li>
<p><strong>Media Processing</strong>:</p>
<ul>
<li>PDF document reading and analysis</li>
<li>Link content extraction and summarization</li>
<li>Audio transcription</li>
<li>Video content processing</li>
<li>Image analysis and description</li>
<li>Conversation summarization</li>
</ul>
</li>
</ul>
<h3 class="anchor anchorWithStickyNavbar_LWe7" id="ai--technical-features">AI &amp; Technical Features<a href="#ai--technical-features" class="hash-link" aria-label="Direct link to AI &amp; Technical Features" title="Direct link to AI &amp; Technical Features">​</a></h3>
<ul>
<li>
<p><strong>Flexible Model Support</strong>:</p>
<ul>
<li>Local inference with open-source models</li>
<li>Cloud-based inference through OpenAI</li>
<li>Default configuration with Nous Hermes Llama 3.1B</li>
<li>Integration with Claude for complex queries</li>
</ul>
</li>
<li>
<p><strong>Technical Foundation</strong>:</p>
<ul>
<li>100% TypeScript implementation</li>
<li>Modular architecture</li>
<li>Extensible action system</li>
<li>Custom client support</li>
<li>Comprehensive API</li>
</ul>
</li>
</ul>
<h2 class="anchor anchorWithStickyNavbar_LWe7" id="use-cases">Use Cases<a href="#use-cases" class="hash-link" aria-label="Direct link to Use Cases" title="Direct link to Use Cases">​</a></h2>
<p>Eliza can be used to create:</p>
<ol>
<li>
<p><strong>AI Assistants</strong></p>
<ul>
<li>Customer support agents</li>
<li>Community moderators</li>
<li>Personal assistants</li>
</ul>
</li>
<li>
<p><strong>Social Media Personas</strong></p>
<ul>
<li>Automated content creators</li>
<li>Engagement bots</li>
<li>Brand representatives</li>
</ul>
</li>
<li>
<p><strong>Knowledge Workers</strong></p>
<ul>
<li>Research assistants</li>
<li>Content analysts</li>
<li>Document processors</li>
</ul>
</li>
<li>
<p><strong>Interactive Characters</strong></p>
<ul>
<li>Role-playing characters</li>
<li>Educational tutors</li>
<li>Entertainment bots</li>
</ul>
</li>
</ol>
<h2 class="anchor anchorWithStickyNavbar_LWe7" id="getting-started">Getting Started<a href="#getting-started" class="hash-link" aria-label="Direct link to Getting Started" title="Direct link to Getting Started">​</a></h2>
<p>Eliza is designed to be accessible while maintaining powerful capabilities:</p>
<ul>
<li><strong>Quick Start</strong>: Begin with basic configuration and default character</li>
<li><strong>Customization</strong>: Extend functionality through custom actions and clients</li>
<li><strong>Scaling</strong>: Deploy multiple agents with different personalities</li>
<li><strong>Integration</strong>: Connect to various platforms and services</li>
</ul>
<p>Check out our <a href="/eliza/docs/quickstart/">Quickstart Guide</a> to begin your journey with Eliza.</p>
<h2 class="anchor anchorWithStickyNavbar_LWe7" id="architecture-overview">Architecture Overview<a href="#architecture-overview" class="hash-link" aria-label="Direct link to Architecture Overview" title="Direct link to Architecture Overview">​</a></h2>
<!-- -->
<h2 class="anchor anchorWithStickyNavbar_LWe7" id="community-and-support">Community and Support<a href="#community-and-support" class="hash-link" aria-label="Direct link to Community and Support" title="Direct link to Community and Support">​</a></h2>
<p>Eliza is backed by an active community of developers and users:</p>
<ul>
<li><strong>Open Source</strong>: Contribute to the project on <a href="https://github.com/elizaos/eliza" target="_blank" rel="noopener noreferrer">GitHub</a></li>
<li><strong>Documentation</strong>: Comprehensive guides and API references</li>
<li><strong>Examples</strong>: Ready-to-use character templates and implementations</li>
<li><strong>Support</strong>: Active community for troubleshooting and discussion</li>
</ul>
<h2 class="anchor anchorWithStickyNavbar_LWe7" id="next-steps">Next Steps<a href="#next-steps" class="hash-link" aria-label="Direct link to Next Steps" title="Direct link to Next Steps">​</a></h2>
<ul>
<li><a href="/eliza/docs/quickstart/">Create Your First Agent</a></li>
<li><a href="/eliza/docs/core/agents/">Understand Core Concepts</a></li>
<li><a href="/eliza/docs/guides/advanced/">Explore Advanced Features</a></li>
</ul>
<p>Join us in building the future of autonomous AI agents with Eliza!</p></div><footer class="theme-doc-footer docusaurus-mt-lg"><div class="row margin-top--sm theme-doc-footer-edit-meta-row"><div class="col"><a href="https://github.com/elizaos/eliza/tree/main/docs/docs/intro.md" target="_blank" rel="noopener noreferrer" class="theme-edit-this-page"><svg fill="currentColor" height="20" width="20" viewBox="0 0 40 40" class="iconEdit_Z9Sw" aria-hidden="true"><g><path d="m34.5 11.7l-3 3.1-6.3-6.3 3.1-3q0.5-0.5 1.2-0.5t1.1 0.5l3.9 3.9q0.5 0.4 0.5 1.1t-0.5 1.2z m-29.5 17.1l18.4-18.5 6.3 6.3-18.4 18.4h-6.3v-6.2z"></path></g></svg>Edit this page</a></div><div class="col lastUpdated_JAkA"><span class="theme-last-updated">Last updated<!-- --> on <b><time datetime="2024-12-22T03:22:34.000Z" itemprop="dateModified">Dec 22, 2024</time></b> by <b>Shaw</b></span></div></div></footer></article><nav class="pagination-nav docusaurus-mt-lg" aria-label="Docs pages"><a class="pagination-nav__link pagination-nav__link--next" href="/eliza/docs/quickstart/"><div class="pagination-nav__sublabel">Next</div><div class="pagination-nav__label">⭐ Quick Start</div></a></nav></div></div><div class="col col--3"><div class="tableOfContents_bqdL thin-scrollbar theme-doc-toc-desktop"><ul class="table-of-contents table-of-contents__left-border"><li><a href="#what-is-eliza" class="table-of-contents__link toc-highlight">What is Eliza?</a></li><li><a href="#key-features" class="table-of-contents__link toc-highlight">Key Features</a><ul><li><a href="#core-capabilities" class="table-of-contents__link toc-highlight">Core Capabilities</a></li><li><a href="#communication--media" class="table-of-contents__link toc-highlight">Communication &amp; Media</a></li><li><a href="#ai--technical-features" class="table-of-contents__link toc-highlight">AI &amp; Technical Features</a></li></ul></li><li><a href="#use-cases" class="table-of-contents__link toc-highlight">Use Cases</a></li><li><a href="#getting-started" class="table-of-contents__link toc-highlight">Getting Started</a></li><li><a href="#architecture-overview" class="table-of-contents__link toc-highlight">Architecture Overview</a></li><li><a href="#community-and-support" class="table-of-contents__link toc-highlight">Community and Support</a></li><li><a href="#next-steps" class="table-of-contents__link toc-highlight">Next Steps</a></li></ul></div></div></div></div></main></div></div></div><footer class="footer footer--dark"><div class="container container-fluid"><div class="row footer__links"><div class="col footer__col"><div class="footer__title">Docs</div><ul class="footer__items clean-list"><li class="footer__item"><a class="footer__link-item" href="/eliza/docs/intro/">General</a></li></ul></div><div class="col footer__col"><div class="footer__title">Community</div><ul class="footer__items clean-list"><li class="footer__item"><a href="https://discord.gg/ai16z" target="_blank" rel="noopener noreferrer" class="footer__link-item">Discord<svg width="13.5" height="13.5" aria-hidden="true" viewBox="0 0 24 24" class="iconExternalLink_nPIU"><path fill="currentColor" d="M21 13v10h-21v-19h12v2h-10v15h17v-8h2zm3-12h-10.988l4.035 4-6.977 7.07 2.828 2.828 6.977-7.07 4.125 4.172v-11z"></path></svg></a></li><li class="footer__item"><a href="https://twitter.com/ai16zdao" target="_blank" rel="noopener noreferrer" class="footer__link-item">Twitter<svg width="13.5" height="13.5" aria-hidden="true" viewBox="0 0 24 24" class="iconExternalLink_nPIU"><path fill="currentColor" d="M21 13v10h-21v-19h12v2h-10v15h17v-8h2zm3-12h-10.988l4.035 4-6.977 7.07 2.828 2.828 6.977-7.07 4.125 4.172v-11z"></path></svg></a></li></ul></div><div class="col footer__col"><div class="footer__title">More</div><ul class="footer__items clean-list"><li class="footer__item"><a href="https://github.com/elizaos/eliza" target="_blank" rel="noopener noreferrer" class="footer__link-item">GitHub<svg width="13.5" height="13.5" aria-hidden="true" viewBox="0 0 24 24" class="iconExternalLink_nPIU"><path fill="currentColor" d="M21 13v10h-21v-19h12v2h-10v15h17v-8h2zm3-12h-10.988l4.035 4-6.977 7.07 2.828 2.828 6.977-7.07 4.125 4.172v-11z"></path></svg></a></li></ul></div></div></div></footer></div>
</body>
</html>
