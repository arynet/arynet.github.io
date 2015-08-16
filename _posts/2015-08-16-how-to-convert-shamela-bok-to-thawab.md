---
layout: post
title: "How to convert shamela .bok to Thawab"
date: 2015-08-16 04:47:14
categories: linux
tags:
- linux
thumbnail: 
---

Some linux user may have probem thats we can’t convert .bok file from Shamela.ws to Thawab. The latest version of Thawab for my Xubuntu is 3.0.13-2. The developer said, they fixed the problem. But, here in Ubuntu repository are not update with current fix and I can’t convert the .bok files.

So how I fix the convert problem? The problem cause from few character that mdbtools can’t do his job.

I just do a simple way :

    #: sudo nautilus

Find the shamelaUtils.py in this folder /usr/share/thawab/Thawab and replace with [this version](https://github.com/ojuba-org/thawab/blob/master/Thawab/shamelaUtils.py).

Run Thawab and convert the .bok files, its should work.