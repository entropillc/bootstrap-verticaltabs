Bootstrap Vertical Tabs
=======================

Modifies Bootstrap's Tabs to provide an alternative vertical styling.

Usage
-----

Simply drop the CSS onto any page:

``` html
<link rel="stylesheet" type="text/css" href="bootstrap.css"/>
<link rel="stylesheet" type="text/css" href="bootstrap-verticaltabs.css"/>
```

Then for tab click functionality, include the Bootstrap Tabs JavaScript with jQuery:

``` html
<script type="text/javascript" src="jquery-1.7.1.min.js"></script>
<script type="text/javascript" src="bootstrap-tabs.js"></script>
```

To align a set of tabs vertically, simply wrap the tabs and their content like this:

``` html
<div class="verticaltabs-container"> <!-- Wrap the Bootstrap Tabs/Pills in this container to position them vertically -->
  <ul class="tabs">
    <li class="active"><a href="#home">Home</a></li>
    <li><a href="#profile">Profile</a></li>
    <li><a href="#messages">Messages</a></li>
    <li><a href="#settings">Settings</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <div class="tab-content">
    <div class="tab-pane active" id="home">...</div>
    <div class="tab-pane" id="profile">...</div>
    <div class="tab-pane" id="messages">...</div>
    <div class="tab-pane" id="settings">...</div>
    <div class="tab-pane" id="contact">...</div>
  </div>
</div>
```

License
---------------------

Copyright 2011 Entropi Software, LLC.

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0