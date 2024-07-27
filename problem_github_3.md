# Problem & Solution #3::

## Problem::
```bash
Windows Git, Warning::"LF will be replaced by CRLF the next time Git touches it"
```
## Solution::
Depending on the editor you are using, a text file with LF wouldn't necessary be saved with CRLF: recent editors can preserve eol style. But that git config setting insists on changing those...

Simply make sure that (as I recommend here):

```bash
git config --global core.autocrlf false
```