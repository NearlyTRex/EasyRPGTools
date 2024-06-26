# LcfTrans

LcfTrans is a small tool to extract strings out of RPG Maker 2000 and 2003
database (LDB), maptree (LMT) and map files (LMU). These strings are written
to a po translation file and can be translated using any tool supporting the
po format (e.g. Poedit).

The po files are processed by EasyRPG Player for multilanguage support.
Writing the translation back into the RPG Maker files is currently *NOT*
supported.

LcfTrans is part of the EasyRPG Project.
More information is available at the project website:

https://easyrpg.org/


## Documentation

Documentation is available at the documentation wiki:

https://easyrpg.org/wiki/


## Requirements

 * liblcf - https://github.com/EasyRPG/liblcf


## Daily builds

Up to date binaries for assorted platforms are available at:

https://ci.easyrpg.org/


## Source code

LcfTrans development is hosted by GitHub, project files are available in Git
repositories.

https://github.com/EasyRPG/Tools


## Building

### Autotools:

```shell
./bootstrap # (only needed if using a git checkout)
./configure
make
make install # (optionally)
```

You may tweak build parameters and environment variables, run
`./configure --help` for reference.

### CMake

```shell
cmake -B builddir
cmake --build builddir
cmake --install builddir # (optionally)
```


## License

LcfTrans is free software under the MIT license. See the file COPYING for
details.
