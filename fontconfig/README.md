# fontconfig files for (URW)++ Core Font Set [Level 2]

These files contains the necessary configuration files for use with fontconfig:

https://www.freedesktop.org/wiki/Software/fontconfig/

Previously, this configuration was part of the fontconfig project itself, but
fontconfig upstream and Artifex company agreed to keep these configuration files
together with the font files themselves.

In case you see some bug/error in these configuration files, feel free to report
an issue, or (better) create a new pull-request on github.com:

https://github.com/ArtifexSoftware/urw-base35-fonts

### IMPORTANT NOTE
Previously, the configuration for these fonts had priority/ordering value of 30.
(The configuration was part of 30-metric-aliases.conf and 30-urw-aliases.conf in
 fontconfig upstream's default configuration files.)

Currently these files no longer contain the priority/ordering value as part of
their name. It is preferred that each distribution using fontconfig decides on
the priority/ordering value by themselves, depending on theirs internal politics,
processes, preferences, etc., and rename those files appropriately.

For more info on the priority of fontconfig configuration files, visit e.g.:

https://fedoraproject.org/wiki/Fontconfig_packaging_tips

In case you are still not sure what priority/ordering value you should use, you
could stick up with the previously used (default) value of 30.
