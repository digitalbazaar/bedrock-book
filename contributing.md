



<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>bedrock/CONTRIBUTING.md at master · digitalbazaar/bedrock · GitHub</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="digitalbazaar/bedrock" name="twitter:title" /><meta content="bedrock - Bedrock: A core foundation for rich Web applications." name="twitter:description" /><meta content="https://avatars0.githubusercontent.com/u/167436?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars0.githubusercontent.com/u/167436?v=3&amp;s=400" property="og:image" /><meta content="digitalbazaar/bedrock" property="og:title" /><meta content="https://github.com/digitalbazaar/bedrock" property="og:url" /><meta content="bedrock - Bedrock: A core foundation for rich Web applications." property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    
    <meta name="pjax-timeout" content="1000">
    

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="49988237:3E3F:55A4B1D:56A420F6" name="octolytics-dimension-request_id" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged Out">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

        <meta name="expected-hostname" content="github.com">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="93dd48f8b53d1bd678380d5b1b91082da1ea1cde" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-fefb561e0a804c2a181aed0adbaa8ba5aa475e09b7692a3f737cb8bb50ef1c27.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-b2d8d1fd984ff1b181275aaa1276c82bb266b4f58f08f3075941d786d5b432ec.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="f08e6513a91b7d33dce8dbaaa01f9efd">

      
  <meta name="description" content="bedrock - Bedrock: A core foundation for rich Web applications.">
  <meta name="go-import" content="github.com/digitalbazaar/bedrock git https://github.com/digitalbazaar/bedrock.git">

  <meta content="167436" name="octolytics-dimension-user_id" /><meta content="digitalbazaar" name="octolytics-dimension-user_login" /><meta content="27559729" name="octolytics-dimension-repository_id" /><meta content="digitalbazaar/bedrock" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="27559729" name="octolytics-dimension-repository_network_root_id" /><meta content="digitalbazaar/bedrock" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/digitalbazaar/bedrock/commits/master.atom" rel="alternate" title="Recent Commits to bedrock:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/digitalbazaar/bedrock/blob/master/CONTRIBUTING.md" data-pjax-transient>
  </head>


  <body class="logged_out   env-production  vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      
      <div class="header header-logged-out" role="banner">
  <div class="container clearfix">

    <a class="header-logo-wordmark" href="https://github.com/" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
      <span aria-hidden="true" class="mega-octicon octicon-logo-github"></span>
    </a>

    <div class="header-actions" role="navigation">
        <a class="btn btn-primary" href="/join?source=header" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
      <a class="btn" href="/login?return_to=%2Fdigitalbazaar%2Fbedrock%2Fblob%2Fmaster%2FCONTRIBUTING.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
    </div>

    <div class="site-search repo-scope js-site-search" role="search">
      <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/digitalbazaar/bedrock/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/digitalbazaar/bedrock/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
    </div>

      <ul class="header-nav left" role="navigation">
          <li class="header-nav-item">
            <a class="header-nav-link" href="/explore" data-ga-click="(Logged out) Header, go to explore, text:explore">Explore</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/features" data-ga-click="(Logged out) Header, go to features, text:features">Features</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://enterprise.github.com/" data-ga-click="(Logged out) Header, go to enterprise, text:enterprise">Enterprise</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/pricing" data-ga-click="(Logged out) Header, go to pricing, text:pricing">Pricing</a>
          </li>
      </ul>

  </div>
</div>



    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/WebPage">
    <div id="js-repo-pjax-container" class="context-loader-container js-repo-nav-next" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
      <a href="/login?return_to=%2Fdigitalbazaar%2Fbedrock"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <span aria-hidden="true" class="octicon octicon-eye"></span>
    Watch
  </a>
  <a class="social-count" href="/digitalbazaar/bedrock/watchers">
    15
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fdigitalbazaar%2Fbedrock"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <span aria-hidden="true" class="octicon octicon-star"></span>
    Star
  </a>

    <a class="social-count js-social-count" href="/digitalbazaar/bedrock/stargazers">
      12
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fdigitalbazaar%2Fbedrock"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <span aria-hidden="true" class="octicon octicon-repo-forked"></span>
        Fork
      </a>

    <a href="/digitalbazaar/bedrock/network" class="social-count">
      4
    </a>
  </li>
</ul>

    <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span aria-hidden="true" class="octicon octicon-repo"></span>
  <span class="author"><a href="/digitalbazaar" class="url fn" itemprop="url" rel="author"><span itemprop="title">digitalbazaar</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/digitalbazaar/bedrock" data-pjax="#js-repo-pjax-container">bedrock</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <a href="/digitalbazaar/bedrock" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /digitalbazaar/bedrock">
    <span aria-hidden="true" class="octicon octicon-code"></span>
    Code
</a>
    <a href="/digitalbazaar/bedrock/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /digitalbazaar/bedrock/issues">
      <span aria-hidden="true" class="octicon octicon-issue-opened"></span>
      Issues
      <span class="counter">1</span>
</a>
  <a href="/digitalbazaar/bedrock/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /digitalbazaar/bedrock/pulls">
    <span aria-hidden="true" class="octicon octicon-git-pull-request"></span>
    Pull requests
    <span class="counter">0</span>
</a>

  <a href="/digitalbazaar/bedrock/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /digitalbazaar/bedrock/pulse">
    <span aria-hidden="true" class="octicon octicon-pulse"></span>
    Pulse
</a>
  <a href="/digitalbazaar/bedrock/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /digitalbazaar/bedrock/graphs">
    <span aria-hidden="true" class="octicon octicon-graph"></span>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/digitalbazaar/bedrock/blob/30d5826aa09be0d1802e1fc597ff0c2a0a179a30/CONTRIBUTING.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:1288cd39fd3ca1f0cf6c53c6e842f7f6 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span aria-label="Close" class="octicon octicon-x js-menu-close" role="button"></span>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/digitalbazaar/bedrock/blob/0.2.x/CONTRIBUTING.md"
               data-name="0.2.x"
               data-skip-pjax="true"
               rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.x">
                0.2.x
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/digitalbazaar/bedrock/blob/0.3.x/CONTRIBUTING.md"
               data-name="0.3.x"
               data-skip-pjax="true"
               rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.3.x">
                0.3.x
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/digitalbazaar/bedrock/blob/master/CONTRIBUTING.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.9/CONTRIBUTING.md"
              data-name="1.0.9"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.9">
                1.0.9
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.8/CONTRIBUTING.md"
              data-name="1.0.8"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.8">
                1.0.8
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.7/CONTRIBUTING.md"
              data-name="1.0.7"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.7">
                1.0.7
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.6/CONTRIBUTING.md"
              data-name="1.0.6"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.6">
                1.0.6
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.5/CONTRIBUTING.md"
              data-name="1.0.5"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.5">
                1.0.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.4/CONTRIBUTING.md"
              data-name="1.0.4"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.4">
                1.0.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.3/CONTRIBUTING.md"
              data-name="1.0.3"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.3">
                1.0.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.2/CONTRIBUTING.md"
              data-name="1.0.2"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.2">
                1.0.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.1/CONTRIBUTING.md"
              data-name="1.0.1"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.1">
                1.0.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/1.0.0/CONTRIBUTING.md"
              data-name="1.0.0"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="1.0.0">
                1.0.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.3.2/CONTRIBUTING.md"
              data-name="0.3.2"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.3.2">
                0.3.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.3.1/CONTRIBUTING.md"
              data-name="0.3.1"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.3.1">
                0.3.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.3.0/CONTRIBUTING.md"
              data-name="0.3.0"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.3.0">
                0.3.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.9/CONTRIBUTING.md"
              data-name="0.2.0-rc.9"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.9">
                0.2.0-rc.9
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.8/CONTRIBUTING.md"
              data-name="0.2.0-rc.8"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.8">
                0.2.0-rc.8
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.7/CONTRIBUTING.md"
              data-name="0.2.0-rc.7"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.7">
                0.2.0-rc.7
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.6/CONTRIBUTING.md"
              data-name="0.2.0-rc.6"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.6">
                0.2.0-rc.6
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.5/CONTRIBUTING.md"
              data-name="0.2.0-rc.5"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.5">
                0.2.0-rc.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.4/CONTRIBUTING.md"
              data-name="0.2.0-rc.4"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.4">
                0.2.0-rc.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.3/CONTRIBUTING.md"
              data-name="0.2.0-rc.3"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.3">
                0.2.0-rc.3
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.2/CONTRIBUTING.md"
              data-name="0.2.0-rc.2"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.2">
                0.2.0-rc.2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.2.0-rc.1/CONTRIBUTING.md"
              data-name="0.2.0-rc.1"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.2.0-rc.1">
                0.2.0-rc.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.1.1/CONTRIBUTING.md"
              data-name="0.1.1"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.1.1">
                0.1.1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
              href="/digitalbazaar/bedrock/tree/0.1.0/CONTRIBUTING.md"
              data-name="0.1.0"
              data-skip-pjax="true"
              rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="0.1.0">
                0.1.0
              </span>
            </a>
        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/digitalbazaar/bedrock/find/master"
          class="js-show-file-finder btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/digitalbazaar/bedrock" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">bedrock</span></a></span></span><span class="separator">/</span><strong class="final-path">CONTRIBUTING.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/digitalbazaar/bedrock/commit/fc4291fda45fd18eba8179aa79da353de92688b8" data-pjax>
          fc4291f
        </a>
        <time datetime="2015-08-25T17:16:46Z" is="relative-time">Aug 25, 2015</time>
      </span>
      <div>
        <img alt="@dlongley" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/168137?v=3&amp;s=40" width="20" />
        <a href="/dlongley" class="user-mention" rel="contributor">dlongley</a>
          <a href="/digitalbazaar/bedrock/commit/fc4291fda45fd18eba8179aa79da353de92688b8" class="message" data-pjax="true" title="Add link to the Angular Style Guide.">Add link to the Angular Style Guide.</a>
      </div>

    <div class="commit-tease-contributors">
      <a class="muted-link contributors-toggle" href="#blob_contributors_box" rel="facebox">
        <strong>2</strong>
         contributors
      </a>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="dlongley" href="/digitalbazaar/bedrock/commits/master/CONTRIBUTING.md?author=dlongley"><img alt="@dlongley" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/168137?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="davidlehn" href="/digitalbazaar/bedrock/commits/master/CONTRIBUTING.md?author=davidlehn"><img alt="@davidlehn" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/109587?v=3&amp;s=40" width="20" /> </a>


    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@dlongley" height="24" src="https://avatars2.githubusercontent.com/u/168137?v=3&amp;s=48" width="24" />
            <a href="/dlongley">dlongley</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@davidlehn" height="24" src="https://avatars2.githubusercontent.com/u/109587?v=3&amp;s=48" width="24" />
            <a href="/davidlehn">davidlehn</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/digitalbazaar/bedrock/raw/master/CONTRIBUTING.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/digitalbazaar/bedrock/blame/master/CONTRIBUTING.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/digitalbazaar/bedrock/commits/master/CONTRIBUTING.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>


        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <span aria-hidden="true" class="octicon octicon-pencil"></span>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <span aria-hidden="true" class="octicon octicon-trashcan"></span>
        </button>
  </div>

  <div class="file-info">
      217 lines (166 sloc)
      <span class="file-info-divider"></span>
    7.91 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-contributing-to-bedrock" class="anchor" href="#contributing-to-bedrock" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Contributing to Bedrock</h1>

<p>Details for developers about contributing to the Bedrock code.</p>

<h2><a id="user-content-commit-messages" class="anchor" href="#commit-messages" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Commit Messages</h2>

<ul>
<li>Use present tense, so it's read as: If you applied this changeset, X will happen.</li>
<li>Start with a capital letter; use proper capitalization throughout, end with a period.</li>
<li>Keep the first message under 50 chars if possible, (certainly under 80). It should express a basic summary of the changeset. Be specific, don't just say "Fix the bug."</li>
<li>If you have more to express after the summary, leave an empty line after the opening summary and then express whatever you need in an extended description.</li>
<li>If you need to reference issues, then after the optional extended description, leave an empty line and then use <code>Addresses #issue-number</code> (for example).</li>
</ul>

<p>Example commit messages:</p>

<pre><code>Add infinite scroll to comment section.

- Replaces existing pagination mechanism with an infinite scroll feature.
- Future work includes CSS-animated fireworks when new comments arrive.

Addresses #123.
</code></pre>

<pre><code>Fix memory leak in animation runner.

When canceling an animation, a closure was created that had a reference
to a DOM element that caused it to be held indefinitely in jquery's cache.
The closure has been reworked to avoid the reference.

Addresses #124.
</code></pre>

<h2><a id="user-content-code-style" class="anchor" href="#code-style" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Code Style</h2>

<h3><a id="user-content-javascript" class="anchor" href="#javascript" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>JavaScript</h3>

<p>Follow these rules as strictly as possible; only stray if there's a Very Good
Reason To (TM).</p>

<ul>
<li>Two-space indentation, NO tabs.</li>
<li>Same-line curly brackets, keep else/elseif/catch/while on the same line
as a related opening bracket; put one space before opening brackets.</li>
<li>No extra spaces after if, while, etc. before the parenthetical.</li>
<li>Use semicolons.</li>
<li>Use camelCase for variables, method names, etc. Only use underscores as a
prefix for "private" functions or variables that really need to be
distinguished as such.</li>
<li>Return early and avoid else if possible.</li>
<li>Use continuation-passing-style (callbacks) when writing node.js code as
it is popular practice there. Use Promises in client-side code. If Promises
and other generator-related tech begin to become popular in node.js then
we will switch to that. We want our code to be as compatible as possible
with the community and idiomatic in the environments in which it is run.</li>
<li>Use async for callback management: <a href="/digitalbazaar/bedrock/blob/master">https://github.com/caolan/async</a></li>
<li>Prefer single quotes for strings. Only use double quotes when it would
result in fewer escape sequences. If there's any HTML that must be written
in a JS-string, it will be easier with single-quotes as you won't have
to escape any the HTML double quoting.</li>
<li>Prefer one variable declaration per line, no elaborate indentation, and
declare nearest to where variables are used. You may declare simple iterator
vars for loops multiple times in the same function, functional-scope
notwithstanding.</li>
<li>Do not use trailing commas (for example: [foo, bar,]).</li>
<li>Line break at 80 chars; if you must line break for function parameters, line
break at the opening parenthesis and move all parameters down, do not
break in the middle of the parameter list. The only exception to this is
if a parameter is an object with too many properties to fit on a single
line; you may break after the opening object bracket for this. Break before
periods for chaining function calls.</li>
<li>Avoid getters and setters.</li>
<li>Do not override built-in prototypes unless you're fixing IE.</li>
<li>If you find a need to use OOP, use PascalCase for classes. Avoid OOP unless
there's a really good justification for the added complexity. OOP is not a
panacea, it is a tool for a very specific problem set. If it is used for
a problem that is not in that set, there are only disadvantages. Examples
include, but are not limited to: unused layers of abstraction and overhead
that affect both runtime and development time, more indirection that must
be traced during debugging, decreased ratio of effectual code lines to lines
of code, and stacktrace horrors.</li>
<li>See: <a href="http://steve-yegge.blogspot.com/2006/03/execution-in-kingdom-of-nouns.html">http://steve-yegge.blogspot.com/2006/03/execution-in-kingdom-of-nouns.html</a></li>
</ul>

<p>A number of style and code rules can be checked with
<a href="http://jshint.com/">jshint</a> and <a href="https://github.com/jscs-dev/node-jscs">jscs</a>:</p>

<pre><code>$ grunt jshint
$ grunt jscs
</code></pre>

<h3><a id="user-content-angularjs" class="anchor" href="#angularjs" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>AngularJS</h3>

<p>Follow the <a href="https://github.com/johnpapa/angular-styleguide">Angular Style Guide</a>.</p>

<p>Organize files according to "components". Components are collections of
controllers, services, directives, filters, and templates that are all
part of the same submodule or feature:</p>

<pre><code>.
`-- app
    |-- components
    |   `-- fooBar
    |       |-- foo-bar.js
    |       |-- foo-bar-controller.js
    |       |-- foo-bar-service.js
    |       |-- foo-bar-directive.js
    |       |-- foo-bar-filter.js
    |       |-- foo-bar.html
    |       |-- foo-bar-modal-directive.js
    |       |-- foo-bar-modal.html
    |       |-- foo-bar-selector-directive.js
    |       `-- foo-bar-selector.html
    `-- components.js
</code></pre>

<p>Each JavaScript file will be an AMD file. The file "foo-bar.js" will be
responsible for loading all of the controllers, services, directives, and
filters modules. It will also have the angular.module('app.fooBar') definition
and will define each controller, service, directive, and filter on that
angular module.</p>

<p>The file "components.js" is an AMD module that will load all components
that are used by the app and register them as dependencies for an
'app.components' angular module.</p>

<p>Naming conventions:</p>

<p>All files use lowercase and hyphens as a word delimiter. Controllers,
services, and directives should be prefixed and use camelCase. Filters
are not prefixed and use camelCase.</p>

<p>Controllers:</p>

<ul>
<li>Name: prefixFooBarController (camelCase)</li>
<li>File: foo-bar-controller.js</li>
</ul>

<p>Services:</p>

<ul>
<li>Name: prefixFooBarService (CamelCase)</li>
<li>File: foo-bar-service.js</li>
</ul>

<p>Directives:</p>

<ul>
<li>Name: prefixFooBar (camelCase)</li>
<li>File: foo-bar-directive.js</li>
</ul>

<p>Filters:</p>

<ul>
<li>Name: fooBar (camelCase)</li>
<li>File: foo-bar-filter.js</li>
</ul>

<p>Templates:</p>

<ul>
<li>Name: foo-bar.html</li>
</ul>

<p>Modals:</p>

<ul>
<li>Name: prefixFooBarModal (camelCase)</li>
<li>File: foo-bar-modal-directive.js</li>
<li>Template: foo-bar-modal.html</li>
</ul>

<p>Selectors:</p>

<ul>
<li>Name: prefixFooBarSelector (camelCase)</li>
<li>File: foo-bar-selector-directive.js</li>
<li>Template: foo-bar-selector.html</li>
</ul>

<p>Best practices:</p>

<ul>
<li>Use "controller as" syntax wherever possible. Refer to controller as
'self' in controller code. Use "controller as model" in the common
case where the view is simple and only one controller is used. Use
'controllerAs' property in directive.</li>
<li>For complex directives, do not add variables directly to the scope,
as this may lead to unexpected behavior that results from
prototypical inheritance patterns. Instead, add them to single
property on the scope such as "model" or use this pattern in
your directive definitions, which will add variables to "ctrl" so
you can access them via "ctrl.foo" in a template:</li>
</ul>

<div class="highlight highlight-source-js"><pre>  {
    scope<span class="pl-k">:</span> {foo<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>=<span class="pl-pds">'</span></span>},
    <span class="pl-en">controller</span><span class="pl-k">:</span> <span class="pl-k">function</span>() {},
    controllerAs<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>ctrl<span class="pl-pds">'</span></span>,
    bindToController<span class="pl-k">:</span> <span class="pl-c1">true</span>
  }</pre></div>

<ul>
<li>Use 'link' not 'controller' for controller code in directives that
do not expose a controller API for reuse; only add "controller" in
these cases if using the above pattern for scope variables.</li>
<li>Use the annotation /* @ngInject */ before dependency-injected functions
to ensure the build tools can appropriately deal with minification.</li>
</ul>

<h2><a id="user-content-debugging" class="anchor" href="#debugging" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Debugging</h2>

<p>Similar to the NODE_DEBUG environment setting, there is a BEDROCK_DEBUG
environment setting. This is a comma separated list of modules to debug. The
current known options are:</p>

<ul>
<li>test: Debug the testing framework.</li>
</ul>

<p>To use, run commands like the following:</p>

<pre><code>$ BEDROCK_DEBUG=test npm run test
</code></pre>

<h2><a id="user-content-testing" class="anchor" href="#testing" aria-hidden="true"><span aria-hidden="true" class="octicon octicon-link"></span></a>Testing</h2>

<ul>
<li>Backend tests are located in <code>tests/backend/</code>.</li>
<li>Frontend tests are located in <code>tests/frontend/</code>. These tests use
protractor to test a web browser.</li>
<li>Use <code>BEDROCK_DEBUG=test</code> to show additional debug info.</li>
</ul>

<p>The following projects are used for creating tests:</p>

<ul>
<li><a href="https://github.com/admc/wd">https://github.com/admc/wd</a></li>
<li><a href="http://visionmedia.github.io/mocha/">http://visionmedia.github.io/mocha/</a></li>
<li><a href="http://chaijs.com/">http://chaijs.com/</a></li>
<li><a href="https://github.com/domenic/chai-as-promised">https://github.com/domenic/chai-as-promised</a></li>
</ul>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop"></div>
</div>

    </div>
  </div>

    </div>

        <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing">Pricing</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span aria-hidden="true" class="mega-octicon octicon-mark-github" title="GitHub "></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.03825s from github-fe129-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span aria-hidden="true" class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span aria-hidden="true" class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/compat-a0cee5d8d4fb535c0f41971d037b32e852a56ddca5bf67bb2124e426a2d813a5.js"></script>
      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-9ee55ceaf87fc34dc86334249fef6cbece88e815478e0fbe81642d57ed0fff89.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-1be19ad6629c8d2b52bb1b011c6b7ecf743db569054c1c0f36c8d9858ce3f640.js"></script>
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span aria-hidden="true" class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <span aria-hidden="true" class="octicon octicon-x"></span>
    </button>
  </div>
</div>

  </body>
</html>

