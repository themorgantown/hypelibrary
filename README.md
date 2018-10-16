<img style="float:right" src="https://raw.githubusercontent.com/themorgantown/hypelibrary/master/readme-hypelogo.png" width="150">

# Tumult Hype Library CDN

This readme explains how to use the jsDelvr CDN to load the Hype runtime. This repository also contains files required to create your own content delivery network for <a href="https://tumult.com/hype/pro">Tumult Hype's</a> runtime. 

Why? An external runtime URL is useful for delivering high performance advertisements and for leveraging browser cache to speed up your documents. To learn more about the advanced export and external runtime feature in Tumult Hype, [visit this page](http://tumult.com/hype/documentation/3.0/#external-runtime-hosting). View [examples of ads & web banners](https://tumult.com/hype/gallery/#Ads%20&%20Web%20Banners) created in Tumult Hype.

## Use this (Unofficial) CDN:

To use this repository as your own external runtime host, use the URL below when selecting `File > Advanced Export` in Tumult Hype Professional:

**Recommended:**

`https://cdn.jsdelivr.net/gh/themorgantown/hypelibrary/`

uses [JSdelivr](https://jsdelivr.net) 

[![](https://data.jsdelivr.com/v1/package/gh/themorgantown/hypelibrary/badge)](https://www.jsdelivr.com/package/gh/themorgantown/hypelibrary)**!**

Download <a href="https://raw.githubusercontent.com/themorgantown/hypelibrary/master/Hype_CDN_prepared.hype.zip">this Hype document</a> to get started quickly. 

Your Advanced Export pane should look like this: 

<img src="https://raw.githubusercontent.com/themorgantown/hypelibrary/master/readme-advanced-export-image.png" width="520">


<hr>

### Alternative:

`https://gitcdn.xyz/repo/themorgantown/hypelibrary/master/` uses Gitcdn. 


## When should you use this? 

Some advertising networks have low file size limits for your uploaded creatives: this runtime URL might help you stay under that limit. Also, if your site loads multiple Hype documents, the Hype Library might be downloading each time a new Hype Document is loaded. Using this CDN will ensure the file is downloaded only a single time.

## Stay Updated

[Learn more, ask questions, and subscribe to updates here](https://forums.tumult.com/t/unofficial-tumult-hype-cdn/12912). No warranties are provided for this free service. 

To setup your own CDN, [use the files in this repository](https://github.com/themorgantown/hypelibrary), which will be kept up to date with new Hype releases.  

The best way to be notified when a new Tumult Hype version is updated is by [joining the mailing list](http://tumult.com/hype/#social-signups) or using Hype (which will notify you when a new Hype version is available). 
   
