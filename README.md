dpastecli 
==========
<tt>dpastecli</tt> is a shell script to paste content from <tt>stdin</tt> to http://dpaste.com

Features
--------
  - small
  - reads from standard input
  - deletion of content possible
  - dpaste syntax supported (case sensitive!)
    - Python
    - PythonConsole
    - Sql
    - DjangoTemplate
    - JScript
    - Css
    - Xml
    - Diff
    - Ruby
    - Rhtml
    - Haskell
    - Apache
    - Bash


Prerequisites
-------------
  - curl (http://curl.haxx.se/)

Installation
------------
  - put dpastecli to <tt>/usr/local/bin</tt>
  - <tt>chmod +x /usr/local/bin/dpastecli</tt>

AUR Package: https://aur.archlinux.org/packages/dpastecli-git/

How to use it
--------------

Syntax template for Bash <br/>
<tt>$ cat shellscript.sh | dpastecli -s Bash</tt>

Omit saving the cookie <br/>
<tt>$ echo "Hello World" | dpastecli -o</tt>
    
Delete pasted content <br/>
<tt>$ dpastecli -d http://dpaste.com/id</tt>

License and Copyright
=======
Licensed under the GNU General Public License 3.

(C) Jens Nazarenus, 2012-2013
