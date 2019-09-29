# C++ Completions

## About
This Sublime Text (2 or 3) package gives method completion suggestions for C++.

## Screenshot
![C++ Completion preview](preview.gif)


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `C++ Completions` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## How to Use

### Methods and other completions

Just type the words and the completion suggestions should show up. Press `ENTER` or `TAB` for completion.

#### Including header files
Type **i-**`header name` then Press `ENTER` or `TAB` for completion. e.g.

> i-vector to get:

```c
  #include <vector>
```

> **Note:** For best result, you can disable `Qt Completions for C++` **(if installed)** so that only the normal C++ methods would show up in the completion lists.


## Contributing

All contributions are welcome. Just fork it on [Github](https://github.com/tushortz/CPP-Completions) and create a pull request.

## License

© 2015 Taiwo Kareem | taiwo.kareem36@gmail.com.

**Read license.txt**
