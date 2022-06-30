# LDAP - Docker mod for homeassistant

This mod adds ldapsearch to homeassistant, to be installed/updated during container start.

In homeassistant docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:homeassistant-ldap`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:homeassistant-ldap|linuxserver/mods:homeassistant-mod2`
