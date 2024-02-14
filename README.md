# s7 - simple configuration language for s6

For philosophical reasons, the author of s6 would prefer to leave a configuration language
out of s6, and left as an exercise for the user.  Here is one such implementation based on
TOML, along with some extra goodies like automatic log pipeline creation.