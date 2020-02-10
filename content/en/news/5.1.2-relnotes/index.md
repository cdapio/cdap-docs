
---
date: 2019-10-13
title: "CDAP 5.1.2: Storage APIs, Portable Runtime and Pipeline enhancements"
description: "Storage APIs, Portable Runtime and Pipeline enhancements"
categories: ["Releases"]
images:
- images/blog/hugo-bug-poster.png

---

This release introduces a number of new features, improvements, and bug fixes to CDAP. Some of the main highlights of the release are:

* **Storage SPIs**
  * Storage SPIs provide abstraction for all system storage used by CDAP so that CDAP is more portable across runtime enviroments - Hadoop or Hadoop-free environments.
* **Portable Runtime**
  * Provide a runtime architecture for CDAP to support both Hadoop and Hadoopless environments, such as Kubernetes, in a distributed and secure fashion.
* **Pipeline Enhancements**
  * Improve experience of building pipelines with the help of features such as copy & paste and minimap of the pipeline. Add support for more data types.	

This is a bug-fix release with a couple of important fixes.

* hugofs: Fix mount with hole regression [b78576fd](https://github.com/gohugoio/hugo/commit/b78576fd38a76bbdaab5ad21228c8e5a559090b1) [@bep](https://github.com/bep) [#6854](https://github.com/gohugoio/hugo/issues/6854)
* Fix bundle resource ordering regression [18888e09](https://github.com/gohugoio/hugo/commit/18888e09bbb5325bdd63f2cd93116ff490dd37ab) [@bep](https://github.com/bep) [#6851](https://github.com/gohugoio/hugo/issues/6851)
* CONTRIBUTING: Fix note about CGO [7f0ebd4a](https://github.com/gohugoio/hugo/commit/7f0ebd4a3c9e016afddc2cf5e7dfe6a820aa099a) [@moorereason](https://github.com/moorereason) 
* Update Go version requirement [23ea4318](https://github.com/gohugoio/hugo/commit/23ea43180b84e35d99e88083a83e7ca1916b3b36) [@bep](https://github.com/bep) [#6853](https://github.com/gohugoio/hugo/issues/6853)



