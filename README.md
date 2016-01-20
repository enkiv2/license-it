# license-it

Create a COPYING file for a git or svn repository containing a personalized version of the 3-clause BSD license, and try to commit it.

In the future, I'd like to support multiple licenses and allow the mechanisms by which project name, date, and copyright owner can be overridden.

For now, the date is the system date, the project name is the directory name of the current checkout, and the owner is set to the 'fullname' field in /etc/password

The license-it script is written and tested against zsh. It doesn't use any really obscure features, but it may not work (or may work incorrectly) on shells like bash and dash.

