Software and installation
-------------------------

Our main shell server includes a plethora of Linux software, some of which can be used graphically over a VNC session.

If something is missing that you'd like to use, we may be able to install it for you.  The usual constraints are that it should be available in `Ubuntu's repositories <https://packages.ubuntu.com>`_, and suitable for a multi-user environment.

As we run LTS releases of Ubuntu, you may find that the versions we have installed are rather outdated -- typically patched by Ubuntu with security fixes but without new features.

Port binding
~~~~~~~~~~~~

When running programs that bind to ports, please ensure you only bind to ``localhost`` so they're not publicly accessible, and choose a random high-numbered port to try and avoid conflicts with other users.