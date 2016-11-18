signTextJS
==========

Re-implements window.crypto.signText and exposes it to content

How-To
------
Install the Firefox Add-On SDK following the directions
[here](https://developer.mozilla.org/en-US/Add-ons/SDK/Tutorials/Installation).
Then, after checking out this repo, use `jpm run` to run Firefox with the
add-on installed or `jpm xpi` to package the addon. After the add-on has been
installed, content scripts that call `window.crypto.signText` should "just
work".

TODO
----
Add certificate filtering by CA name as in original signText implementation.
