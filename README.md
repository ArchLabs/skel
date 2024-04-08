# Skeleton Configuration Files

Skeleton configurations for ArchLabs user home directory creation


The `base/` directory contains generic application configuration
used across all installs, while the `*-home/` directories contain
environment specific configuration. These directories' contents __must__
be able to be copied over one another into `/etc/skel/`
__without__ overlapping files.
