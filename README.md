<!DOCTYPE html>
<html>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>

<body class="header-page">

  <div class="wrapper">
    <div class="unite-header">
      <div class="nav-wrap">
        <div class="container">
          <a class="hamburger" aria-label="Menu" href="#"><span></span></a>
          <div class="logo">{logo}</div>
          <div class="nav desktop-nav">{menu}</div>
          <div class="nav membership-cart">{membership}{minicart}</div>
        </div>
      </div>
    </div>

    <div class="banner-wrap">
      {{#header}}
          <div class="container">
            <div class="banner">{content}</div>
          </div>
      {{/header}}
    </div>

    <div class="main-wrap">
      {{#sections}}
          <div class="container">{content}</div>
      {{/sections}}
    </div>

    <div class="footer-wrap">
        <div class="footer">{footer}</div>
    </div>
  </div>

  <div class="nav mobile-nav">
    <a class="hamburger" aria-label="Menu" href="#"><span></span></a>
    {menu}
  </div>

  <script>
    (function(d) {
      var config = {
        kitId: 'nxe1ajf',
        scriptTimeout: 3000,
        async: true
      },
      h=d.documentElement,t=setTimeout(function(){h.className=h.className.replace(/\bwf-loading\b/g,"")+" wf-inactive";},config.scriptTimeout),tk=d.createElement("script"),f=false,s=d.getElementsByTagName("script")[0],a;h.className+=" wf-loading";tk.src='https://use.typekit.net/'+config.kitId+'.js';tk.async=true;tk.onload=tk.onreadystatechange=function(){a=this.readyState;if(f||a&&a!="complete"&&a!="loaded")return;f=true;clearTimeout(t);try{Typekit.load(config)}catch(e){}};s.parentNode.insertBefore(tk,s)
    })(document);
  </script>

	<script type="text/javascript" src="/files/theme/plugins.js"></script>
  <script type="text/javascript" src="/files/theme/custom.js"></script>
</body>

</html>
