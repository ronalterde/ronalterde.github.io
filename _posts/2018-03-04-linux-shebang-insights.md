---
layout: post
---
In Linux, you can execute an interpreted script file in exactly the same way as you would execute a compiled binary: by setting the 'executable' attribute and just run it. A special sequence of characters at the beginning of the script makes this possible. In this article we will explore how this -- pretty elegant -- way of script execution works and which components of the Linux system are involved.

Consider the following Python script. It's introduced by two special characters and also contains the path to the python interpreter.

<!--more-->

This post has moved to my new blog: [deardevices.com](https://deardevices.com{{ page.url }})!
[![Dear Devices]({{ "/assets/deardevices.png" | absolute_url }})](https://deardevices.com{{ page.url }})
