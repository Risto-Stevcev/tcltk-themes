# tcltk-themes

Tcl Tk themes


## Example

### Awthemes

```tcl
#!/bin/tclsh
package require Tk
lappend auto_path "/home/risto/git/tcl-packages/awthemes-10.4.0"
package require awdark
ttk::style theme use awdark
grid [ttk::button .b -text "Hello World"]
```

```tcl
#!/bin/tclsh
package require Tk
source "/home/risto/git/js/tk/black.tcl"
ttk::style theme use black
grid [ttk::button .b -text "Hello World"]
```


## Links

### Colors list

https://tcl.tk/man/tcl8.6/TkCmd/contents.htm
https://tcl.tk/man/tcl8.6/TkCmd/colors.htm


### Really good tutorial on using Tk with tcl/python/ruby

https://tkdocs.com/tutorial/index.html


### Some notes/graphics on themes

http://wookie.tcl.tk/48689


### awthemes

https://packages.debian.org/sid/tcl-awthemes
https://sourceforge.net/projects/tcl-awthemes/
http://wookie.tcl.tk/55511
http://wookie.tcl.tk/55519


### black.tcl

http://wookie.tcl.tk/55370


