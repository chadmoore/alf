Alf - Out of this World Zsh
===========================

Alf is an out of this world super fast and configurable framework for [zsh][4]; it's modeled after [Prezto][1] and [Antigen][2]. The framework is currently utilizing [Oh My Zsh][3] (framework, plugins and themes) and optionally [Prezto's][1] plugins under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

Why another framework?
----------------------

At my work I needed to support a similar shell environment across OS X, Windows, and Parallels (running a virtual machine with an OS X host). Originally I was able to get Cygwin running with [Oh My Zsh][3], but I wasn't really happy with the performance. So I started scripting and hacking around and learning Bash and [Zsh][4].


Installation
------------

Alf will work with any recent release of Zsh, but the minimum recommended version is 4.3.11.

### OS X ###

This method will setup everything you need:

    ```shell
    \curl -sSL https://raw.githubusercontent.com/psyrendust/alf/develop/bootstrap/baseline.zsh | zsh
    ```

Or you can pass an optional argument to load a specific branch:

    ```shell
    \curl -sSL https://raw.githubusercontent.com/psyrendust/alf/develop/bootstrap/baseline.zsh | zsh -s develop
    ```



Customization
-------------

The project is managed via [Git][6]. It is highly recommended that you fork this project; so, that you can commit your changes and push them to [GitHub][7] to not lose them. If you do not know how to use Git, follow this [tutorial][8] and bookmark this [reference][9].

Resources
---------

The [Zsh Reference Card][10] and the [zsh-lovers][11] man page are indispensable.

Author
------

Larry Gordon


License
-------

[The MIT License (MIT)](http://psyrendust.mit-license.org/2014/license.html)

[1]: https://github.com/sorin-ionescu/prezto
[2]: https://github.com/zsh-users/antigen
[3]: https://github.com/robbyrussell/oh-my-zsh
[4]: http://www.zsh.org
[5]: https://www.gnu.org/software/bash/bash.html
[6]: http://git-scm.com
[7]: https://github.com
[8]: http://gitimmersion.com
[9]: http://gitref.org
[10]: http://www.bash2zsh.com/zsh_refcard/refcard.pdf
[11]: http://grml.org/zsh/zsh-lovers.html
[12]: http://i.imgur.com/nBEEZ.png "sorin theme"
