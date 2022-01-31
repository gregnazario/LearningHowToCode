# Git Tutorial

## What is Git?

Git is version control software.  It's meant to keep track of changes in files by keeping track of `commits`.  A `commit` is a somewhat of a savepoint for a file.  It keeps track of the change log or `diff` between the current commit, and the previous `commit`.  In the example below, I'll try to illustrate what the `diff` is from a file, with two consecutive commits `A` and `B`.

Total state at commit A:
```
abc
```

Total state at commit B:
```
abcde
```

Diff of commit A to commit B:
```
-abc
+abcde
```

As you can see here, it keeps a log of changes in lines.  The diff is that the line is no longer `abc` -> `-abc` and it is now `abcde` -> `+abcde`.

