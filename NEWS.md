





<!DOCTYPE html>
<html class="gl-light ui-neutral with-header with-top-bar " lang="zh-CN">
<head prefix="og: http://ogp.me/ns#">
<meta charset="utf-8">
<meta content="IE=edge" http-equiv="X-UA-Compatible">
<meta content="width=device-width, initial-scale=1" name="viewport">
<title>NEWS.md · master · Yaroslav Pronin / libretorrent · GitLab</title>
<script nonce="7ce30JQ07oQkz1J3bMC4mQ==">
//<![CDATA[
window.gon={};gon.api_version="v4";gon.default_avatar_url="https://gitlab.com/assets/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png";gon.max_file_size=100;gon.asset_host=null;gon.webpack_public_path="/assets/webpack/";gon.relative_url_root="";gon.user_color_scheme="white";gon.markdown_surround_selection=null;gon.markdown_automatic_lists=null;gon.math_rendering_limits_enabled=true;gon.analytics_url="https://collector.prd-278964.gl-product-analytics.com";gon.analytics_id="715db59f-f350-4bfd-aef8-e7a7f0c023f0";gon.sentry_dsn="https://f5573e26de8f4293b285e556c35dfd6e@new-sentry.gitlab.net/4";gon.sentry_environment="gprd";gon.sentry_clientside_traces_sample_rate=0.05;gon.recaptcha_api_server_url="https://www.recaptcha.net/recaptcha/api.js";gon.recaptcha_sitekey="6LfAERQTAAAAAL4GYSiAMGLbcLyUIBSfPrDNJgeC";gon.gitlab_url="https://gitlab.com";gon.organization_http_header_name="HTTP_GITLAB_ORGANIZATION_ID";gon.revision="428f5148383";gon.feature_category="source_code_management";gon.gitlab_logo="/assets/gitlab_logo-2957169c8ef64c58616a1ac3f4fc626e8a35ce4eb3ed31bb0d873712f2a041a0.png";gon.secure=true;gon.sprite_icons="/assets/icons-0b41337f52be73f7bbf9d59b841eb98a6e790dfa1a844644f120a80ce3cc18ba.svg";gon.sprite_file_icons="/assets/file_icons/file_icons-7cd3d6c3b29a6d972895f36472978a4b5adb4b37f9b5d0716a380e82389f7e0e.svg";gon.emoji_sprites_css_path="/assets/emoji_sprites-d746ae2450a3e9c626d338d77a101b84ff33a47c0c281b676d75c4a6ed2948a4.css";gon.gridstack_css_path="/assets/lazy_bundles/gridstack-5fcfd4ffbea1db04eaf7f16521bcab19ae3af042c8b4afe8d16781eda5a70799.css";gon.test_env=false;gon.disable_animations=null;gon.suggested_label_colors={"#cc338b":"Magenta-pink","#dc143c":"Crimson","#c21e56":"Rose red","#cd5b45":"Dark coral","#ed9121":"Carrot orange","#eee600":"Titanium yellow","#009966":"Green-cyan","#8fbc8f":"Dark sea green","#6699cc":"Blue-gray","#e6e6fa":"Lavender","#9400d3":"Dark violet","#330066":"Deep violet","#36454f":"Charcoal grey","#808080":"Gray"};gon.first_day_of_week=0;gon.time_display_relative=true;gon.time_display_format=0;gon.ee=true;gon.jh=false;gon.dot_com=true;gon.uf_error_prefix="UF";gon.pat_prefix="glpat-";gon.keyboard_shortcuts_enabled=true;gon.diagramsnet_url="https://embed.diagrams.net";gon.features={"sourceEditorToolbar":false,"vscodeWebIde":true,"uiForOrganizations":false,"organizationSwitching":false,"removeMonitorMetrics":true,"keyContactsManagementV2":false,"explainCodeChat":false};gon.roadmap_epics_limit=1000;gon.subscriptions_url="https://customers.gitlab.com";gon.subscriptions_legacy_sign_in_url="https://customers.gitlab.com/customers/sign_in?legacy=true";gon.billing_accounts_url="https://customers.gitlab.com/billing_accounts";gon.payment_form_url="https://customers.gitlab.com/payment_forms/cc_validation";gon.payment_validation_form_id="payment_method_validation";gon.licensed_features={"fileLocks":true,"remoteDevelopment":true};
//]]>
</script>

<script nonce="7ce30JQ07oQkz1J3bMC4mQ==">
//<![CDATA[
var gl = window.gl || {};
gl.startup_calls = {"/proninyaroslav/libretorrent/-/blob/master/NEWS.md?format=json\u0026viewer=rich":{},"":{}};
gl.startup_graphql_calls = [{"query":"query getBlobInfo(\n  $projectPath: ID!\n  $filePath: String!\n  $ref: String!\n  $refType: RefType\n  $shouldFetchRawText: Boolean!\n) {\n  project(fullPath: $projectPath) {\n    __typename\n    id\n    repository {\n      __typename\n      empty\n      blobs(paths: [$filePath], ref: $ref, refType: $refType) {\n        __typename\n        nodes {\n          __typename\n          id\n          webPath\n          name\n          size\n          rawSize\n          rawTextBlob @include(if: $shouldFetchRawText)\n          fileType\n          language\n          path\n          blamePath\n          editBlobPath\n          gitpodBlobUrl\n          ideEditPath\n          forkAndEditPath\n          ideForkAndEditPath\n          codeNavigationPath\n          projectBlobPathRoot\n          forkAndViewPath\n          environmentFormattedExternalUrl\n          environmentExternalUrlForRouteMap\n          canModifyBlob\n          canCurrentUserPushToBranch\n          archived\n          storedExternally\n          externalStorage\n          externalStorageUrl\n          rawPath\n          replacePath\n          pipelineEditorPath\n          simpleViewer {\n            fileType\n            tooLarge\n            type\n            renderError\n          }\n          richViewer {\n            fileType\n            tooLarge\n            type\n            renderError\n          }\n        }\n      }\n    }\n  }\n}\n","variables":{"projectPath":"proninyaroslav/libretorrent","ref":"master","refType":"","filePath":"NEWS.md","shouldFetchRawText":false}}];

if (gl.startup_calls && window.fetch) {
  Object.keys(gl.startup_calls).forEach(apiCall => {
   gl.startup_calls[apiCall] = {
      fetchCall: fetch(apiCall, {
        // Emulate XHR for Rails AJAX request checks
        headers: {
          'X-Requested-With': 'XMLHttpRequest'
        },
        // fetch won’t send cookies in older browsers, unless you set the credentials init option.
        // We set to `same-origin` which is default value in modern browsers.
        // See https://github.com/whatwg/fetch/pull/585 for more information.
        credentials: 'same-origin'
      })
    };
  });
}
if (gl.startup_graphql_calls && window.fetch) {
  const headers = {"X-CSRF-Token":"gNrKwr-ZpdOBQSlydiJ_0UTSXSHyOYt-67sebRPr6qLG64TyXVei7zMddFwBDTqP2JQmkVA3xCTz2xUV2V-RUg","x-gitlab-feature-category":"source_code_management"};
  const url = `https://gitlab.com/api/graphql`

  const opts = {
    method: "POST",
    headers: {
      "Content-Type": "application/json",
      ...headers,
    }
  };

  gl.startup_graphql_calls = gl.startup_graphql_calls.map(call => ({
    ...call,
    fetchCall: fetch(url, {
      ...opts,
      credentials: 'same-origin',
      body: JSON.stringify(call)
    })
  }))
}


//]]>
</script>

<link rel="prefetch" href="/assets/webpack/monaco.4536784b.chunk.js">

<link rel="stylesheet" href="/assets/application-f129dce4bc8474ddc1536c596971637ddd834d35fdd6ab8413c7fe761817d6ac.css" media="all" />
<link rel="stylesheet" href="/assets/page_bundles/tree-4d25647d03722854e14fe89644330ef783d9e6e79f75ae79c5755c11825ddfc8.css" media="all" /><link rel="stylesheet" href="/assets/page_bundles/projects-97864a07bdb44dc7694b22d96267284ba18244aa259b388fb339eebb2e4d7d07.css" media="all" /><link rel="stylesheet" href="/assets/page_bundles/commit_description-b1dab9b10010cbb9c3738689b18ce46a4f58b98a8d483226fdff8a776a45caf0.css" media="all" />
<link rel="stylesheet" href="/assets/application_utilities-4ce46b0d1744a75b5e0b7104e935413dc41b09b34002dc2832a687dd8e7f0569.css" media="all" />
<link rel="stylesheet" href="/assets/tailwind-b8efda5613f9f69fb03e25fc7c7c57b241a861c4bd4cd709570b419f4fd1006f.css" media="all" />


<link rel="stylesheet" href="/assets/fonts-fae5d3f79948bd85f18b6513a025f863b19636e85b09a1492907eb4b1bb0557b.css" media="all" />
<link rel="stylesheet" href="/assets/highlight/themes/white-e08c45a78f4446ec6c4226adb581d4482911bd7c85b47b7e7c003112b0c26274.css" media="all" />

<script src="/assets/webpack/runtime.dd1068dd.bundle.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/main.306b6f8d.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/tracker.9d61d80c.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/analytics.0104e296.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script nonce="7ce30JQ07oQkz1J3bMC4mQ==">
//<![CDATA[
window.snowplowOptions = {"namespace":"gl","hostname":"snowplow.trx.gitlab.net","cookieDomain":".gitlab.com","appId":"gitlab","formTracking":true,"linkClickTracking":true}

gl = window.gl || {};
gl.snowplowStandardContext = {"schema":"iglu:com.gitlab/gitlab_standard/jsonschema/1-0-10","data":{"environment":"production","source":"gitlab-rails","plan":"free","extra":{},"user_id":null,"is_gitlab_team_member":null,"namespace_id":673086,"project_id":6790003,"feature_enabled_by_namespace_ids":null,"context_generated_at":"2024-05-09T06:10:38.889Z"}}
gl.snowplowPseudonymizedPageUrl = "https://gitlab.com/namespace673086/project6790003/-/blob/:repository_path";


//]]>
</script>
<link rel="preload" href="/assets/application_utilities-4ce46b0d1744a75b5e0b7104e935413dc41b09b34002dc2832a687dd8e7f0569.css" as="style" type="text/css" nonce="7xzmIB4X9TqCL+tOHithLw==">
<link rel="preload" href="/assets/application-f129dce4bc8474ddc1536c596971637ddd834d35fdd6ab8413c7fe761817d6ac.css" as="style" type="text/css" nonce="7xzmIB4X9TqCL+tOHithLw==">
<link rel="preload" href="/assets/highlight/themes/white-e08c45a78f4446ec6c4226adb581d4482911bd7c85b47b7e7c003112b0c26274.css" as="style" type="text/css" nonce="7xzmIB4X9TqCL+tOHithLw==">
<link crossorigin="" href="https://snowplow.trx.gitlab.net" rel="preconnect">
<link as="font" crossorigin="" href="/assets/gitlab-sans/GitLabSans-1e0a5107ea3bbd4be93e8ad2c503467e43166cd37e4293570b490e0812ede98b.woff2" rel="preload">
<link as="font" crossorigin="" href="/assets/gitlab-sans/GitLabSans-Italic-38eaf1a569a54ab28c58b92a4a8de3afb96b6ebc250cf372003a7b38151848cc.woff2" rel="preload">
<link as="font" crossorigin="" href="/assets/gitlab-mono/GitLabMono-08d2c5e8ff8fd3d2d6ec55bc7713380f8981c35f9d2df14e12b835464d6e8f23.woff2" rel="preload">
<link as="font" crossorigin="" href="/assets/gitlab-mono/GitLabMono-Italic-38e58d8df29485a20c550da1d0111e2c2169f6dcbcf894f2cd3afbdd97bcc588.woff2" rel="preload">
<link rel="preload" href="/assets/fonts-fae5d3f79948bd85f18b6513a025f863b19636e85b09a1492907eb4b1bb0557b.css" as="style" type="text/css" nonce="7xzmIB4X9TqCL+tOHithLw==">

<script src="/assets/locale/zh_CN/app-d8d66075de123d0541aeff500b8c7897d0c8c8c49e65076ca9a79ce33809b982.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>

<script src="/assets/webpack/sentry.5f922f51.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>


<script src="/assets/webpack/commons-pages.groups.analytics.dashboards-pages.groups.analytics.dashboards.value_streams_dashboard--efdd0d8d.a673a47f.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.groups.new-pages.import.gitlab_projects.new-pages.import.manifest.new-pages.projects.n-44c6c18e.198bdb4b.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.search.show-super_sidebar.0e2b9b15.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/super_sidebar.eb5bcbd7.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.projects-pages.projects.activity-pages.projects.alert_management.details-pages.project-9747309d.8cf06596.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.admin.runners.show-pages.clusters.agents.dashboard-pages.explore.catalog-pages.explore-48ba6f8c.65d4090f.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.groups.security.policies.edit-pages.groups.security.policies.new-pages.projects.blob.s-c8e0a3ae.e67ca9b7.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/111.d5d76553.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.projects.artifacts.file-pages.projects.blob.show-pages.projects.show-pages.projects.sn-83d6e33b.eceef54b.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.projects.blob.show-pages.projects.show-pages.projects.snippets.show-pages.projects.tre-c684fcf6.8bac298b.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/136.95774f40.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.projects.blob.show-pages.projects.show-pages.projects.tree.show.5a1e7372.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/commons-pages.projects.blob.show-pages.projects.commits.show-pages.projects.compare.show.2b37eecc.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<script src="/assets/webpack/pages.projects.blob.show.a5992485.chunk.js" defer="defer" nonce="7ce30JQ07oQkz1J3bMC4mQ=="></script>
<meta content="object" property="og:type">
<meta content="GitLab" property="og:site_name">
<meta content="NEWS.md · master · Yaroslav Pronin / libretorrent · GitLab" property="og:title">
<meta content="Free and Open Source, full-featured torrent client for Android. Mirror: https://github.com/proninyaroslav/libretorrent" property="og:description">
<meta content="https://gitlab.com/uploads/-/system/project/avatar/6790003/ic_launcher.png" property="og:image">
<meta content="64" property="og:image:width">
<meta content="64" property="og:image:height">
<meta content="https://gitlab.com/proninyaroslav/libretorrent/-/blob/master/NEWS.md" property="og:url">
<meta content="summary" property="twitter:card">
<meta content="NEWS.md · master · Yaroslav Pronin / libretorrent · GitLab" property="twitter:title">
<meta content="Free and Open Source, full-featured torrent client for Android. Mirror: https://github.com/proninyaroslav/libretorrent" property="twitter:description">
<meta content="https://gitlab.com/uploads/-/system/project/avatar/6790003/ic_launcher.png" property="twitter:image">

<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="Ilx15V4F3KQYyBPUegLy8-iw0dOVxP2sAglDN8rdCutkbTvVvMvbmKqUTvoNLbetdPaqYzfKsvYaaUhPAGlxGw" />
<meta name="csp-nonce" content="7ce30JQ07oQkz1J3bMC4mQ==" />
<meta name="action-cable-url" content="/-/cable" />
<link href="/-/manifest.json" rel="manifest">
<link rel="icon" type="image/png" href="/assets/favicon-72a2cad5025aa931d6ea56c3201d1f18e68a8cd39788c7c80d5b2b82aa5143ef.png" id="favicon" data-original-href="/assets/favicon-72a2cad5025aa931d6ea56c3201d1f18e68a8cd39788c7c80d5b2b82aa5143ef.png" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/apple-touch-icon-b049d4bc0dd9626f31db825d61880737befc7835982586d015bded10b4435460.png" />
<link href="/search/opensearch.xml" rel="search" title="Search GitLab" type="application/opensearchdescription+xml">




<meta content="Free and Open Source, full-featured torrent client for Android. Mirror: https://github.com/proninyaroslav/libretorrent" name="description">
<meta content="#ececef" name="theme-color">
</head>

<body class="tab-width-8 gl-browser-edge gl-platform-windows " data-find-file="/proninyaroslav/libretorrent/-/find_file/master" data-namespace-id="673086" data-page="projects:blob:show" data-page-type-id="master/NEWS.md" data-project="libretorrent" data-project-full-path="proninyaroslav/libretorrent" data-project-id="6790003">

<script nonce="7ce30JQ07oQkz1J3bMC4mQ==">
//<![CDATA[
gl = window.gl || {};
gl.client = {"isEdge":true,"isWindows":true};


//]]>
</script>


<header class="header-logged-out" data-testid="navbar">
<a class="gl-sr-only gl-accessibility" href="#content-body">Skip to content</a>
<div class="container-fluid">
<nav aria-label="浏览 GitLab" class="header-logged-out-nav gl-display-flex gl-gap-3 gl-justify-content-space-between">
<div class="gl-display-flex gl-align-items-center gl-gap-1">
<span class="gl-sr-only">GitLab</span>
<a title="主页" id="logo" class="header-logged-out-logo has-tooltip" aria-label="主页" data-track-label="main_navigation" data-track-action="click_gitlab_logo_link" data-track-property="navigation_top" href="/"><svg aria-hidden="true" role="img" class="tanuki-logo" width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path class="tanuki-shape tanuki" d="m24.507 9.5-.034-.09L21.082.562a.896.896 0 0 0-1.694.091l-2.29 7.01H7.825L5.535.653a.898.898 0 0 0-1.694-.09L.451 9.411.416 9.5a6.297 6.297 0 0 0 2.09 7.278l.012.01.03.022 5.16 3.867 2.56 1.935 1.554 1.176a1.051 1.051 0 0 0 1.268 0l1.555-1.176 2.56-1.935 5.197-3.89.014-.01A6.297 6.297 0 0 0 24.507 9.5Z"
        fill="#E24329"/>
  <path class="tanuki-shape right-cheek" d="m24.507 9.5-.034-.09a11.44 11.44 0 0 0-4.56 2.051l-7.447 5.632 4.742 3.584 5.197-3.89.014-.01A6.297 6.297 0 0 0 24.507 9.5Z"
        fill="#FC6D26"/>
  <path class="tanuki-shape chin" d="m7.707 20.677 2.56 1.935 1.555 1.176a1.051 1.051 0 0 0 1.268 0l1.555-1.176 2.56-1.935-4.743-3.584-4.755 3.584Z"
        fill="#FCA326"/>
  <path class="tanuki-shape left-cheek" d="M5.01 11.461a11.43 11.43 0 0 0-4.56-2.05L.416 9.5a6.297 6.297 0 0 0 2.09 7.278l.012.01.03.022 5.16 3.867 4.745-3.584-7.444-5.632Z"
        fill="#FC6D26"/>
</svg>

</a></div>
<ul class="gl-list-none gl-p-0 gl-m-0 gl-display-flex gl-gap-3 gl-align-items-center gl-flex-grow-1">
<li class="header-logged-out-nav-item header-logged-out-dropdown gl-md-display-none">
<button class="header-logged-out-toggle" data-toggle="dropdown" type="button">
<span class="gl-sr-only">
菜单
</span>
<svg class="s16" data-testid="hamburger-icon"><use href="/assets/icons-0b41337f52be73f7bbf9d59b841eb98a6e790dfa1a844644f120a80ce3cc18ba.svg#hamburger"></use></svg>
</button>
<div class="dropdown-menu">
<ul>
<li>
<a href="https://about.gitlab.com/why-gitlab">为什么选择 GitLab
</a></li>
<li>
<a href="https://about.gitlab.com/pricing">定价
</a></li>
<li>
<a href="https://about.gitlab.com/sales">联系销售
</a></li>
<li>
<a href="/explore">探索</a>
</li>
</ul>
</div>
</li>
<li class="header-logged-out-nav-item gl-display-none gl-md-display-inline-block">
<a href="https://about.gitlab.com/why-gitlab">为什么选择 GitLab
</a></li>
<li class="header-logged-out-nav-item gl-display-none gl-md-display-inline-block">
<a href="https://about.gitlab.com/pricing">定价
</a></li>
<li class="header-logged-out-nav-item gl-display-none gl-md-display-inline-block">
<a href="https://about.gitlab.com/sales">联系销售
</a></li>
<li class="header-logged-out-nav-item gl-display-none gl-md-display-inline-block">
<a class="" href="/explore">探索</a>
</li>
</ul>
<ul class="gl-list-none gl-p-0 gl-m-0 gl-display-flex gl-gap-3 gl-align-items-center gl-justify-content-end">
<li class="header-logged-out-nav-item">
<a href="/users/sign_in?redirect_to_referer=yes">登录</a>
</li>
<li class="header-logged-out-nav-item">
<a class="gl-button btn btn-md btn-confirm " href="/users/sign_up"><span class="gl-button-text">
获取免费试用

</span>

</a></li>
</ul>
</nav>
</div>
</header>

<div class="layout-page page-with-super-sidebar">
<aside class="js-super-sidebar super-sidebar super-sidebar-loading" data-command-palette="{&quot;project_files_url&quot;:&quot;/proninyaroslav/libretorrent/-/files/master?format=json&quot;,&quot;project_blob_url&quot;:&quot;/proninyaroslav/libretorrent/-/blob/master&quot;}" data-force-desktop-expanded-sidebar="" data-root-path="/" data-sidebar="{&quot;is_logged_in&quot;:false,&quot;context_switcher_links&quot;:[{&quot;title&quot;:&quot;探索&quot;,&quot;link&quot;:&quot;/explore&quot;,&quot;icon&quot;:&quot;compass&quot;}],&quot;current_menu_items&quot;:[{&quot;id&quot;:&quot;project_overview&quot;,&quot;title&quot;:&quot;libretorrent&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:&quot;/uploads/-/system/project/avatar/6790003/ic_launcher.png&quot;,&quot;entity_id&quot;:6790003,&quot;link&quot;:&quot;/proninyaroslav/libretorrent&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-project&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;manage_menu&quot;,&quot;title&quot;:&quot;管理&quot;,&quot;icon&quot;:&quot;users&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/activity&quot;,&quot;is_active&quot;:false,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;activity&quot;,&quot;title&quot;:&quot;动态&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/activity&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-project-activity&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;members&quot;,&quot;title&quot;:&quot;成员&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/project_members&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;labels&quot;,&quot;title&quot;:&quot;标记&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/labels&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false}],&quot;separated&quot;:false},{&quot;id&quot;:&quot;plan_menu&quot;,&quot;title&quot;:&quot;计划&quot;,&quot;icon&quot;:&quot;planning&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/issues&quot;,&quot;is_active&quot;:false,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;project_issue_list&quot;,&quot;title&quot;:&quot;议题&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/issues&quot;,&quot;pill_count&quot;:&quot;134&quot;,&quot;link_classes&quot;:&quot;shortcuts-issues has-sub-items&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;boards&quot;,&quot;title&quot;:&quot;议题看板&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/boards&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-issue-boards&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;milestones&quot;,&quot;title&quot;:&quot;里程碑&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/milestones&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;project_wiki&quot;,&quot;title&quot;:&quot;Wiki&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/wikis/home&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-wiki&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;requirements&quot;,&quot;title&quot;:&quot;需求&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/requirements_management/requirements&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false}],&quot;separated&quot;:false},{&quot;id&quot;:&quot;code_menu&quot;,&quot;title&quot;:&quot;代码&quot;,&quot;icon&quot;:&quot;code&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/merge_requests&quot;,&quot;is_active&quot;:true,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;project_merge_request_list&quot;,&quot;title&quot;:&quot;合并请求&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/merge_requests&quot;,&quot;pill_count&quot;:&quot;2&quot;,&quot;link_classes&quot;:&quot;shortcuts-merge_requests&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;files&quot;,&quot;title&quot;:&quot;仓库&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/tree/master&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-tree&quot;,&quot;is_active&quot;:true},{&quot;id&quot;:&quot;branches&quot;,&quot;title&quot;:&quot;分支&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/branches&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;commits&quot;,&quot;title&quot;:&quot;提交&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/commits/master?ref_type=heads&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-commits&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;tags&quot;,&quot;title&quot;:&quot;标签&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/tags&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;graphs&quot;,&quot;title&quot;:&quot;仓库图&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/network/master?ref_type=heads&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-network&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;compare&quot;,&quot;title&quot;:&quot;比较修订版本&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/compare?from=master\u0026to=master&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;project_snippets&quot;,&quot;title&quot;:&quot;代码片段&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/snippets&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-snippets&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;file_locks&quot;,&quot;title&quot;:&quot;锁定的文件&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/path_locks&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false}],&quot;separated&quot;:false},{&quot;id&quot;:&quot;build_menu&quot;,&quot;title&quot;:&quot;构建&quot;,&quot;icon&quot;:&quot;rocket&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/pipelines&quot;,&quot;is_active&quot;:false,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;pipelines&quot;,&quot;title&quot;:&quot;流水线&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/pipelines&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-pipelines&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;jobs&quot;,&quot;title&quot;:&quot;作业&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/jobs&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-builds&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;pipeline_schedules&quot;,&quot;title&quot;:&quot;流水线计划&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/pipeline_schedules&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-builds&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;test_cases&quot;,&quot;title&quot;:&quot;测试用例&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/quality/test_cases&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-test-cases&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;artifacts&quot;,&quot;title&quot;:&quot;产物&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/artifacts&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-builds&quot;,&quot;is_active&quot;:false}],&quot;separated&quot;:false},{&quot;id&quot;:&quot;deploy_menu&quot;,&quot;title&quot;:&quot;部署&quot;,&quot;icon&quot;:&quot;deployments&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/releases&quot;,&quot;is_active&quot;:false,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;releases&quot;,&quot;title&quot;:&quot;发布&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/releases&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-deployments-releases&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;container_registry&quot;,&quot;title&quot;:&quot;容器镜像库&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/container_registry&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;model_registry&quot;,&quot;title&quot;:&quot;模型注册表&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/ml/models&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false}],&quot;separated&quot;:false},{&quot;id&quot;:&quot;operations_menu&quot;,&quot;title&quot;:&quot;运维&quot;,&quot;icon&quot;:&quot;cloud-pod&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/environments&quot;,&quot;is_active&quot;:false,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;environments&quot;,&quot;title&quot;:&quot;环境&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/environments&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-environments&quot;,&quot;is_active&quot;:false}],&quot;separated&quot;:false},{&quot;id&quot;:&quot;monitor_menu&quot;,&quot;title&quot;:&quot;监控&quot;,&quot;icon&quot;:&quot;monitor&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/incidents&quot;,&quot;is_active&quot;:false,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;incidents&quot;,&quot;title&quot;:&quot;事件&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/incidents&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;service_desk&quot;,&quot;title&quot;:&quot;服务台&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/issues/service_desk&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false}],&quot;separated&quot;:false},{&quot;id&quot;:&quot;analyze_menu&quot;,&quot;title&quot;:&quot;分析&quot;,&quot;icon&quot;:&quot;chart&quot;,&quot;avatar&quot;:null,&quot;avatar_shape&quot;:&quot;rect&quot;,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/value_stream_analytics&quot;,&quot;is_active&quot;:false,&quot;pill_count&quot;:null,&quot;items&quot;:[{&quot;id&quot;:&quot;cycle_analytics&quot;,&quot;title&quot;:&quot;价值流分析&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/value_stream_analytics&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-project-cycle-analytics&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;contributors&quot;,&quot;title&quot;:&quot;贡献者分析&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/graphs/master?ref_type=heads&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;ci_cd_analytics&quot;,&quot;title&quot;:&quot;CI/CD 分析&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/pipelines/charts&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;repository_analytics&quot;,&quot;title&quot;:&quot;仓库分析&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/graphs/master/charts&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-repository-charts&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;code_review&quot;,&quot;title&quot;:&quot;代码评审分析&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/analytics/code_reviews&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;issues&quot;,&quot;title&quot;:&quot;议题分析&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/analytics/issues_analytics&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;insights&quot;,&quot;title&quot;:&quot;洞察&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/insights/&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:&quot;shortcuts-project-insights&quot;,&quot;is_active&quot;:false},{&quot;id&quot;:&quot;model_experiments&quot;,&quot;title&quot;:&quot;模型实验&quot;,&quot;icon&quot;:null,&quot;avatar&quot;:null,&quot;entity_id&quot;:null,&quot;link&quot;:&quot;/proninyaroslav/libretorrent/-/ml/experiments&quot;,&quot;pill_count&quot;:null,&quot;link_classes&quot;:null,&quot;is_active&quot;:false}],&quot;separated&quot;:false}],&quot;current_context_header&quot;:&quot;项目&quot;,&quot;support_path&quot;:&quot;https://about.gitlab.com/get-help/&quot;,&quot;docs_path&quot;:&quot;/help/docs&quot;,&quot;display_whats_new&quot;:true,&quot;whats_new_most_recent_release_items_count&quot;:8,&quot;whats_new_version_digest&quot;:&quot;8a1a6ad5cc3804f1e3aae3a2213f0525839dc46c71313fc2ee7a3fedbee820d3&quot;,&quot;show_version_check&quot;:null,&quot;gitlab_version&quot;:{&quot;major&quot;:17,&quot;minor&quot;:0,&quot;patch&quot;:0,&quot;suffix_s&quot;:&quot;&quot;},&quot;gitlab_version_check&quot;:null,&quot;search&quot;:{&quot;search_path&quot;:&quot;/search&quot;,&quot;issues_path&quot;:&quot;/dashboard/issues&quot;,&quot;mr_path&quot;:&quot;/dashboard/merge_requests&quot;,&quot;autocomplete_path&quot;:&quot;/search/autocomplete&quot;,&quot;search_context&quot;:{&quot;project&quot;:{&quot;id&quot;:6790003,&quot;name&quot;:&quot;libretorrent&quot;},&quot;project_metadata&quot;:{&quot;mr_path&quot;:&quot;/proninyaroslav/libretorrent/-/merge_requests&quot;,&quot;issues_path&quot;:&quot;/proninyaroslav/libretorrent/-/issues&quot;},&quot;code_search&quot;:true,&quot;ref&quot;:&quot;master&quot;,&quot;scope&quot;:null,&quot;for_snippets&quot;:null}},&quot;panel_type&quot;:&quot;project&quot;,&quot;shortcut_links&quot;:[{&quot;title&quot;:&quot;代码片段&quot;,&quot;href&quot;:&quot;/explore/snippets&quot;,&quot;css_class&quot;:&quot;dashboard-shortcuts-snippets&quot;},{&quot;title&quot;:&quot;群组&quot;,&quot;href&quot;:&quot;/explore/groups&quot;,&quot;css_class&quot;:&quot;dashboard-shortcuts-groups&quot;},{&quot;title&quot;:&quot;项目&quot;,&quot;href&quot;:&quot;/explore/projects&quot;,&quot;css_class&quot;:&quot;dashboard-shortcuts-projects&quot;}]}"></aside>

<div class="content-wrapper">
<div class="mobile-overlay"></div>

<div class="alert-wrapper gl-force-block-formatting-context">




























<div class="top-bar-fixed container-fluid" data-testid="top-bar">
<div class="top-bar-container gl-display-flex gl-align-items-center gl-gap-2">
<button class="gl-button btn btn-icon btn-md btn-default btn-default-tertiary js-super-sidebar-toggle-expand super-sidebar-toggle gl-ml-n3" aria-controls="super-sidebar" aria-expanded="false" aria-label="主导航侧边栏" type="button"><svg class="s16 gl-icon gl-button-icon " data-testid="sidebar-icon"><use href="/assets/icons-0b41337f52be73f7bbf9d59b841eb98a6e790dfa1a844644f120a80ce3cc18ba.svg#sidebar"></use></svg>

</button>
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"BreadcrumbList","itemListElement":[{"@type":"ListItem","position":1,"name":"Yaroslav Pronin","item":"https://gitlab.com/proninyaroslav"},{"@type":"ListItem","position":2,"name":"libretorrent","item":"https://gitlab.com/proninyaroslav/libretorrent"},{"@type":"ListItem","position":3,"name":"仓库","item":"https://gitlab.com/proninyaroslav/libretorrent/-/blob/master/NEWS.md"}]}


</script>
<nav aria-label="面包屑导航" class="breadcrumbs gl-breadcrumbs tmp-breadcrumbs-fix" data-testid="breadcrumb-links">
<ul class="breadcrumb gl-breadcrumb-list js-breadcrumbs-list gl-flex-grow-1">
<li class="gl-breadcrumb-item gl-display-inline-flex"><a href="/proninyaroslav">Yaroslav Pronin</a></li> <li class="gl-breadcrumb-item gl-display-inline-flex"><a class="gl-display-inline-flex!" href="/proninyaroslav/libretorrent"><img srcset="/uploads/-/system/project/avatar/6790003/ic_launcher.png?width=16 1x, /uploads/-/system/project/avatar/6790003/ic_launcher.png?width=32 2x" alt="libretorrent" class="gl-avatar gl-avatar-s16 avatar-tile gl-rounded-base!" height="16" width="16" loading="lazy" src="/uploads/-/system/project/avatar/6790003/ic_launcher.png?width=16" />
<span class="js-breadcrumb-item-text">libretorrent</span></a></li>

<li class="gl-breadcrumb-item" data-testid="breadcrumb-current-link">
<a href="/proninyaroslav/libretorrent/-/blob/master/NEWS.md">仓库</a>
</li>
</ul>
</nav>



</div>
</div>

</div>
<div class="container-fluid container-limited project-highlight-puc">
<main class="content" id="content-body" itemscope itemtype="http://schema.org/SoftwareSourceCode">
<div class="flash-container flash-container-page sticky" data-testid="flash-container">
<div id="js-global-alerts"></div>
</div>





<div class="js-signature-container" data-signatures-path="/proninyaroslav/libretorrent/-/commits/b0f908e4e970f8e96a4c57ffe51006c244c0d6ee/signatures?limit=1"></div>

<div class="tree-holder gl-pt-4" id="tree-holder">
<div class="nav-block">
<div class="tree-ref-container">
<div class="tree-ref-holder gl-max-w-26">
<div data-project-id="6790003" data-project-root-path="/proninyaroslav/libretorrent" data-ref="master" data-ref-type="" id="js-tree-ref-switcher"></div>
</div>
<ul class="breadcrumb repo-breadcrumb">
<li class="breadcrumb-item">
<a href="/proninyaroslav/libretorrent/-/tree/master">libretorrent
</a></li>
<li class="breadcrumb-item">
<a href="/proninyaroslav/libretorrent/-/blob/master/NEWS.md"><strong>NEWS.md</strong>
</a></li>
</ul>
</div>
<div class="tree-controls gl-display-flex gl-flex-wrap gl-sm-flex-nowrap gl-align-items-baseline gl-gap-3">
<button class="gl-button btn btn-md btn-default has-tooltip shortcuts-find-file" title="Go to file, press &lt;kbd class=&#39;flat ml-1&#39; aria-hidden=true&gt;/~&lt;/kbd&gt; or &lt;kbd class=&#39;flat ml-1&#39; aria-hidden=true&gt;t&lt;/kbd&gt;" aria-keyshortcuts="/+~ t" data-html="true" type="button"><span class="gl-button-text">
查找文件

</span>

</button>
<a data-event-tracking="click_blame_control_on_blob_page" class="gl-button btn btn-md btn-default js-blob-blame-link" href="/proninyaroslav/libretorrent/-/blame/master/NEWS.md"><span class="gl-button-text">
Blame
</span>

</a>
<a data-event-tracking="click_history_control_on_blob_page" class="gl-button btn btn-md btn-default " href="/proninyaroslav/libretorrent/-/commits/master/NEWS.md"><span class="gl-button-text">
历史
</span>

</a>
<a aria-keyshortcuts="y" class="gl-button btn btn-md btn-default has-tooltip js-data-file-blob-permalink-url" data-html="true" title="转到永久链接 &lt;kbd class=&#39;flat ml-1&#39; aria-hidden=true&gt;y&lt;/kbd&gt;" href="/proninyaroslav/libretorrent/-/blob/521c9ab4fb2515e05ee9fe1050ed9402550cc4dc/NEWS.md"><span class="gl-button-text">
永久链接
</span>

</a>
</div>
</div>

<div class="info-well d-none d-sm-block">
<div class="well-segment">
<ul class="blob-commit-info">
<li class="commit flex-row js-toggle-container" id="commit-b0f908e4">
<div class="avatar-cell d-none d-sm-block">
<a href="/proninyaroslav"><img alt="Yaroslav Pronin&#39;s avatar" src="/uploads/-/system/user/avatar/567708/avatar.png?width=80" class="avatar s40 gl-display-none gl-sm-display-inline-block" title="Yaroslav Pronin"></a>
</div>
<div class="commit-detail flex-list gl-display-flex gl-justify-content-space-between gl-align-items-center gl-flex-grow-1 gl-min-w-0">
<div class="commit-content" data-testid="commit-content">
<a class="commit-row-message item-title js-onboarding-commit-item " href="/proninyaroslav/libretorrent/-/commit/b0f908e4e970f8e96a4c57ffe51006c244c0d6ee">Version 3.4</a>
<span class="commit-row-message d-inline d-sm-none">
&middot;
b0f908e4
</span>
<div class="committer">
由 <a class="commit-author-link js-user-link" data-user-id="567708" href="/proninyaroslav">Yaroslav Pronin</a> 创作于 <time class="js-timeago" title="1月 30, 2022 9:57上午" datetime="2022-01-30T09:57:09Z" data-toggle="tooltip" data-placement="bottom" data-container="body">1月 30, 2022</time>
</div>

</div>
<div class="commit-actions flex-row">
<a class="js-loading-signature-badge" data-commit-sha="b0f908e4e970f8e96a4c57ffe51006c244c0d6ee" data-placement="top" data-title="GPG签名(加载中...)" data-toggle="tooltip" role="button" tabindex="0"></a>

<a class="gl-badge badge badge-pill badge-success md ci-icon ci-icon-variant-success gl-p-2 gl-ml-3" data-container="body" data-placement="left" data-testid="ci-icon" data-toggle="tooltip" href="/proninyaroslav/libretorrent/-/commit/b0f908e4e970f8e96a4c57ffe51006c244c0d6ee/pipelines?ref=master" title="流水线: 已通过"><span class="js-ci-status-badge-legacy ci-icon-gl-icon-wrapper"><svg class="s24 gl-icon" data-testid="status_success_borderless-icon"><use href="/assets/icons-0b41337f52be73f7bbf9d59b841eb98a6e790dfa1a844644f120a80ce3cc18ba.svg#status_success_borderless"></use></svg></span></a>
<div class="js-commit-pipeline-status" data-endpoint="/proninyaroslav/libretorrent/-/commit/b0f908e4e970f8e96a4c57ffe51006c244c0d6ee/pipelines?ref=master"></div>
<div class="commit-sha-group btn-group d-none d-sm-flex">
<div class="label label-monospace monospace">
b0f908e4
</div>
<button class="gl-button btn btn-icon btn-md btn-default " title="复制提交SHA" aria-label="复制提交SHA" aria-live="polite" data-toggle="tooltip" data-placement="bottom" data-container="body" data-html="true" data-category="primary" data-size="medium" data-clipboard-text="b0f908e4e970f8e96a4c57ffe51006c244c0d6ee" type="button"><svg class="s16 gl-icon gl-button-icon " data-testid="copy-to-clipboard-icon"><use href="/assets/icons-0b41337f52be73f7bbf9d59b841eb98a6e790dfa1a844644f120a80ce3cc18ba.svg#copy-to-clipboard"></use></svg>

</button>

</div>
</div>
</div>
</li>

</ul>
</div>
<div data-blob-path="NEWS.md" data-branch="master" data-branch-rules-path="/proninyaroslav/libretorrent/-/settings/repository#js-branch-rules" data-project-path="proninyaroslav/libretorrent" id="js-code-owners"></div>
<div class="well-segment blob-auxiliary-viewer">
<div class="blob-viewer" data-path="NEWS.md" data-type="auxiliary">
<svg class="s16 gl-mr-1 gl-vertical-align-text-bottom" data-testid="history-icon"><use href="/assets/icons-0b41337f52be73f7bbf9d59b841eb98a6e790dfa1a844644f120a80ce3cc18ba.svg#history"></use></svg>
要在任何这些版本中查找此项目存储库的状态，请检查 <a href='/proninyaroslav/libretorrent/-/tags'>标签</a>。.

</div>

</div>

</div>
<div class="blob-content-holder js-per-page" data-blame-per-page="1000" id="blob-content-holder">
<div data-blob-path="NEWS.md" data-explain-code-available="false" data-new-workspace-path="/-/remote_development/workspaces/new" data-original-branch="master" data-project-path="proninyaroslav/libretorrent" data-ref-type="" data-resource-id="gid://gitlab/Project/6790003" data-target-branch="master" data-user-id="" id="js-view-blob-app">
<div class="gl-spinner-container" role="status"><span aria-label="加载中" class="gl-spinner gl-spinner-md gl-spinner-dark gl-vertical-align-text-bottom!"></span></div>
</div>
</div>

</div>
<script nonce="7ce30JQ07oQkz1J3bMC4mQ==">
//<![CDATA[
  window.gl = window.gl || {};
  window.gl.webIDEPath = '/-/ide/project/proninyaroslav/libretorrent/edit/master/-/NEWS.md'


//]]>
</script>
<div data-ambiguous="false" data-ref="master" id="js-ambiguous-ref-modal"></div>

</main>
</div>


</div>
</div>


<script nonce="7ce30JQ07oQkz1J3bMC4mQ==">
//<![CDATA[
if ('loading' in HTMLImageElement.prototype) {
  document.querySelectorAll('img.lazy').forEach(img => {
    img.loading = 'lazy';
    let imgUrl = img.dataset.src;
    // Only adding width + height for avatars for now
    if (imgUrl.indexOf('/avatar/') > -1 && imgUrl.indexOf('?') === -1) {
      const targetWidth = img.getAttribute('width') || img.width;
      imgUrl += `?width=${targetWidth}`;
    }
    img.src = imgUrl;
    img.removeAttribute('data-src');
    img.classList.remove('lazy');
    img.classList.add('js-lazy-loaded');
    img.dataset.testid = 'js-lazy-loaded-content';
  });
}

//]]>
</script>
<script nonce="7ce30JQ07oQkz1J3bMC4mQ==">
//<![CDATA[
gl = window.gl || {};
gl.experiments = {};


//]]>
</script>

</body>
</html>

