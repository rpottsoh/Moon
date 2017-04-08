---
layout: post
title: DUnitX Console Logger Quiet Mode Option
published: true
comments: true
tags: [Delphi, DUnitX, Exercism]
---

[DUnitX](https://github.com/VSoftTechnologies/DUnitX){:target="_blank"} is an excellent open source testing framework which I am utilizing with the Delphi track at [Exercism.io](http://www.exercism.io){:target="_blank"}.  DUnitX has a Console Logger that has an optional Quiet Mode.  Typically Quiet Mode is active with this statement in your project `.dpr` file:

```pascal
logger := TDUnitXConsoleLogger.Create(true);
```

If you like to see a more verbose output to your console screen simply change `true` to `false` or just omit it.  The default state is `false`. 


 
