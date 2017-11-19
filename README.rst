========================================
rimger - a simple image viewer
========================================

.. contents:: Table of Contents


Build
========================================

.. code-block:: sh

    git clone https://github.com/wdv4758h/rimger.git
    cd rimger/
    cargo build --release
    ./target/release/rimger --help



Usage
========================================

.. code-block:: sh

    rimger /path/to/image



Binary Size
========================================



Benchmarks
========================================



Changelog
========================================

Not Implemented Yet (Plan)
------------------------------

* CI support
* keyboard support
* display image's information
* different display mode (zoom in, zoom out, fit window, ...)
* allow display in every workspaces
* header-less mode
* window-less mode
* image slideshow mode
* RESTful API for current image
* QR code for current image



Notice
========================================



Developement
========================================

Making Release
------------------------------

1. update version in ``src/cli.yml``
2. update version in ``Cargo.toml``
3. update version in ``Cargo.lock``
4. add git tag



Special Thanks
========================================

* `Piston Developers <https://github.com/PistonDevelopers>`_
* `clap-rs <https://github.com/kbknapp/clap-rs>`_ for arguments parsing
* `Rust Team <https://www.rust-lang.org/team.html>`_
* and every project I've used



License
========================================

rimger is licensed under the AGPL License - see the ``LICENSE`` file for details
