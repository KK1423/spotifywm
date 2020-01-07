# spotifywm

Makes spotify more friendly to window managers by settings a class name before opening the window.
This allows WMs like i3 to correctly discover the window and fit it into a prepared layout.

Inspired by [steamwm](https://github.com/dscharrer/steamwm).

# Installation

This script installs the debian spotify package, and then replaces the default symlink that launches spotify with a bash script that launches spotify with the proper WM_CLASS.

Also modifies the dpkg listing for spotify-client so that the uninstall option appears in the crostini launcher.

```

$ ./spotifywm
```
