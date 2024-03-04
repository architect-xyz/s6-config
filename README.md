# s7 - simple configuration language for s6

For philosophical reasons, the author of s6 would prefer to leave a configuration language
out of s6, and left as an exercise for the user.  Here is one such implementation based on
TOML, along with some extra goodies like automatic log pipeline creation.

NB: apparently a declarative language is coming, see https://skarnet.com/projects/service-manager.html

## Useful Resources

* https://danyspin97.org/blog/getting-started-with-execline-scriptingp/