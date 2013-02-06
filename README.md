dpastecli 
==========
<tt>dpastecli</tt> is a shell script to paste content from stdin to http://dpaste.com

Features
--------
  - small
  - reads from stdin
  - dpaste syntax supported
  - deletion of content possible

Prerequisites
-------------
  - curl (http://curl.haxx.se/)

Installation
------------
  - put dpastecli to <tt>/usr/local/bin</tt>
  - <tt>chmod +x /usr/local/bin/dpastecli</tt>

How to use it
--------------

(Syntax template for Bash)
<tt>cat shellscript.sh | dpastecli -s Bash</tt>

(Omit saving the cookie)
<tt>echo "Hello World" | dpastecli -o</tt>
    
(Delete pasted content)
<tt>dpastecli -d http://dpaste.com/<id>/</tt>
    
