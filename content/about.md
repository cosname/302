---
title: "About"
date: "2017-04-06T13:19:25+08:00"
---

This is not a particularly interesting website. For now, it is used to redirect a few links to CDN resources (primarily [BootCDN](http://www.bootcdn.cn)). For example, `https://302.cosx.org/mathjax/2.7.0/MathJax.js` is redirected to `https://cdn.bootcss.com/mathjax/2.7.0/MathJax.js`. The `latest` versions are updated manually, and there is no guarantee that they always represent the actual latest versions. Please send us a pull request [on Github](https://github.com/cosname/302/blob/master/static/_redirects) when you find certain latest versions are no longer the latest, or certain CDN resources are broken. Below are two examples showing how the redirection works:

| Name | From | To |
|------|------|----|
| MathJax | `/mathjax/latest/*` | `https://cdn.bootcss.com/mathjax/2.7.0/*` |
|  | `/mathjax/*` | `https://cdn.bootcss.com/mathjax/*` |
| highlight.js | `/highlight.js/latest/*` | `https://cdn.bootcss.com/highlight.js/9.10.0/*` |
|  | `/highlight.js/*` | `https://cdn.bootcss.com/highlight.js/:splat` |

Currently supported libraries include: MathJax, highlight.js, font-awesome.
