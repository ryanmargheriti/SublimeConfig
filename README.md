## Sublime Text 3 configuration ##
Settings, themes and snippets for Sublime Text 3

### Usage ###
* Install package manager by entering the following command into the Sublime console (ctrl + `) then hitting enter:
```python
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```
* Copy contents to `~/Library/Application Support/Sublime Text 3` (OSX) or `%APPDATA%/Sublime Text 3/` (Windows)
