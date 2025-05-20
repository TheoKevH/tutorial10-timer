# TUTORIAL 10 (TIMER)

**Name:** Theodore Kevin Himawan

**NPM:** 2306210973

**Class:** ADPRO A

## Reflection 1.2
>Take a look at what happened. Capture the result of your execution. Put it in your Readme.md,
with some explanation why the result is as such.

![execution](img/1.2.png)

<p align="justify">In the program, the new print command (Kevin's computer: hey hey) is executed first even though it is put below the first two lines (howdy! & done!). This is because the new print command is written outside of the async block, which means it does not have to be spawned and queued first. The first 2 lines are only ran when the program reaches <code>executor.run()</code>.</p>