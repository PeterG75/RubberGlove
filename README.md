RubberGlove
===========

Blocks common browser fingerprint techniques to improve your privacy.

[Install the latest version from the Chrome web store.][1]

RubberGlove aims to reduce the ability of websites to globally fingerprint your browser.  The Electronic Frontier Foundation's website, [panopticlick.eff.org][2], and the associated study shows just how effective these techniques are for tracking you even without cookies.

Currently it wraps the window.navigator and window.clientInformation objects to cloak plugins and mime types similar to the way Firefox and IE do.

Planned future features:
* Reduction of detailed version information both in window.navigator and the http User-Agent header.
* Prevention of time skew and drift fingerprinting
* Prevention of canvas based fingerprinting

Sadly, Chrome does not make it possible to get configuration information early enough in the page load to be useful.  This may delay any features which need to be configured or selectively disabled.

Please note that until this plugin or others like it are widely used, Panopticlick will likely still report your browser as unique despite the reduction in bits of identifying information.

<a href="https://coinbase.com/checkouts/0ec4a16aa8227d3a43e4e200a79b55c5" target="_blank">
<img src="https://coinbase.com/assets/buttons/donation_large-6ec72b1a9eec516944e50a22aca7db35.png" alt="Donate Bitcoins">
</a>

  [1]: https://chrome.google.com/webstore/detail/rubberglove/koabfojebhfdjnligkcihoeekimoekpg?authuser=1
  [2]: https://panopticlick.eff.org
