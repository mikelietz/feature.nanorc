Installing this is easy. Put it somewhere nano can see it, and add it to the master nanorc.

For example, to install in ubuntu, copy the feature.nanorc file to /usr/share/nano. Add the following lines to /etc/nanorc:

```
## Gherkin feature files
include "/usr/share/nano/feature.nanorc"
```
