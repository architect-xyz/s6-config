# s7 - simple configuration language for s6

For philosophical reasons, the author of s6 would prefer to leave a configuration language
out of s6, and left as an exercise for the user.  Here is one such implementation based on
TOML, along with some extra goodies like automatic log pipeline creation.

[2024-03-04] alee: seems like it was forthcoming at one point, c.f. https://skarnet.com/projects/service-manager.html
but the author hasn't committed to the effort since 2022.

## Useful Resources

* https://danyspin97.org/blog/getting-started-with-execline-scriptingp/