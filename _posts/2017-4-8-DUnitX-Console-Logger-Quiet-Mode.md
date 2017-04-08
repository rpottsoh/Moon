---
layout: post
title: DUnitX Console Logger Quiet Mode Option
published: true
comments: true
tags: [Delphi, DUnitX, Exercism]
---

<a href="https://github.com/VSoftTechnologies/DUnitX" target='blank'>DUnitX</a> is an excellent open source testing framework that I am utilizing for the Delphi track at <a href="http://www.exercism.io/" target='blank'>Exercism.io</a>.  DUnitX has a Console Logger that has an optional Quiet Mode.  Typically Quiet Mode is active with this statement in your project `.dpr` file:

```pascal
logger := TDUnitXConsoleLogger.Create(true);
```

If you like to see a more verbose output to your console screen simply change `true` to `false` or just omit it.  The default state is `false`. 

 
