Architecture
************

Directory Hierarchy
===================

.. code-block:: text

    ~/.shell-utils
        |___ rc/        # source entry files, this directory is generated
        |___ skel/      # shell-utils manager
        |___ doc/       # documentation
        |___ bin/       # this path will add to the PATH variable
        |___ src/       # source code for libs and plugins
        |___ lib/       # library used by plugin manager and dependencies
        |___ opt/       # plugins would be here
        |___ var/       # data files
        |___ core/      # source this directory unconditionally
        |___ ext/       # extension utils
        |___ tool/      # tools used for generate docs, check codes, etc.
        |___ test/      # test suits
        |___ misc/      # misc
        |___ custom/    # customize script
        |___ .git/      # git directory
        |___ .gitignore # ignore the .git and custom directory
