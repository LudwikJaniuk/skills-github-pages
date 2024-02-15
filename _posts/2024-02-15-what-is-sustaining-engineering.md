---
title: "What is Sustaining Engineering? (draft)"
date: 2024-02-15
---
# Introduction and job description

I studied Computer Science because I thought I wanted to write code for a living. But perhaps a deeper drive was wanting to know how things work under the hood. In a way this is entitled - I cannot accept that _I_ should not be permitted to look behind the magician's curtain. If not for this drive I would not have tortured myself learning C++.

This summer will mark my third year in the Java Platform Group at Oracle. When hiring me for the positition of "JVM Sustaining Engineer," they told me I wouldn't be writing code, but keeping code running. "Won't I be bored?" I asked. 

The JVM runs everywhere. Some years ago the OpenJDK adopted a time-based release model acknowledging that there are "developers, who prefer rapid innovation, and enterprises, which prefer stability"[^1]. But I see now that stability is not the same as doing nothing[^2]. Cryptographic algorithms change under our feet, as do the operating systems we run on, and even the compilers we use to build. Previously unknown vulnerabilities and bugs are discovered regularly. We need to react to each such change just to deliver this stability that Java is so valued for[^3]. If the JVM doesn't perform as expected, there is a lot of real-world pain.

I haven't had a boring day yet.

[^1]: [https://mreinhold.org/blog/forward-faster](https://mreinhold.org/blog/forward-faster)
[^2]: [https://en.wikipedia.org/wiki/Red_Queen%27s_race](https://en.wikipedia.org/wiki/Red_Queen%27s_race) and [https://www.ascm.org/ascm-insights/the-red-queen-hypothesis/](https://www.ascm.org/ascm-insights/the-red-queen-hypothesis/)
[^3]: [https://www.oracle.com/security-alerts/](https://www.oracle.com/security-alerts/)
