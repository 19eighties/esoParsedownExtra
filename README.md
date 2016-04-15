esoParsedownExtra
=====================

Parsedown Markdown Extra plugin for esoTalk
It is working but was not tested with other plugins, feedback is welcome.

## Installation

### 1. First method, getting the master .zip file

1. Download the file https://github.com/19eighties/esoParsedownExtra/master.zip
2. Extract it to your [esoTalk instalation directory]/addons/plugins/
  * Then you should have the directory [your root install]/addons/plugins/esoParsedownExtra/
4. Go to 'administration' on the site, then to 'Plugins' and enable 'esoMarkdownExtra' plugin.
5. Then it should be working. Just create a post using Markdown syntax and test it.

### 2. Second method, cloning this repository to your plugins/ directory via command line

Via command line, commands are:

~~~bash
cd esoTalk/addons/plugins # go to plugins directory inside your esoTalk installation
git clone https://github.com/kassius/esoParsedownExtra # clone the repository
rm -r esoParsedownExtra/.git # delete git files for safety, unless you want to update it later via command line, then restrict access to this directory in your server's configuration
~~~

Then go to forum administration, and enable the plugin.

## Reference
* Parsedown
  * http://parsedown.org/
  * https://github.com/erusev/parsedown
  * https://github.com/erusev/parsedown-extra
* Markdown
  * http://daringfireball.net/projects/markdown/
  * http://en.wikipedia.org/wiki/Markdown
* Markdown Extra
  * https://michelf.ca/projects/php-markdown/extra/
  * https://github.com/michelf/php-markdown/
  * https://michelf.ca/projects/php-markdown/configuration/
* esoTalk Forum Software
  * http://esotalk.org/forum/
  * http://esotalk.org/
