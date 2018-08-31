<img style="float:right" src="https://raw.githubusercontent.com/themorgantown/hypelibrary/master/readme-hypelogo.png" width="150">

# Tumult Hype Library CDN

This repository contains files required to create your own content delivery network for Tumult Hype's runtime. An external runtime URL is useful for delivering high performance advertisements and for leveraging browser cache to speed up your documents. To learn more about the advanced export and external runtime feature in Tumult Hype, [visit this page](http://tumult.com/hype/documentation/3.0/#external-runtime-hosting). View [examples of ads & web banners](https://tumult.com/hype/gallery/#Ads%20&%20Web%20Banners) created in Tumult Hype.
## Use this Library

To use this repository as your own external runtime host, use either of the two URLs below in Tumult Hype's advanced export to load the library from either the [Rawgit](https://rawgit.com/), [GitCDN](https://github.com/schme16/gitcdn.xyz) or [Jsdelivr](https://www.jsdelivr.com/) services. These services will automatically update when this repository does: 

**New:**

`https://cdn.jsdelivr.net/gh/themorgantown/hypelibrary/` uses [JSdelivr](https://jsdelivr.net)
 
[![](https://data.jsdelivr.com/v1/package/gh/themorgantown/hypelibrary/badge)](https://www.jsdelivr.com/package/gh/themorgantown/hypelibrary)
 

`https://cdn.rawgit.com/themorgantown/hypelibrary/master/` uses [Rawgit's CDN](https://rawgit.com)
or
`https://gitcdn.xyz/repo/themorgantown/hypelibrary/master/` uses Gitcdn. 

Your Advanced Export pane should look like this: 

<img src="https://raw.githubusercontent.com/themorgantown/hypelibrary/master/readme-advanced-export-image.png" width="520">

Download <a href="https://raw.githubusercontent.com/themorgantown/hypelibrary/master/Hype_CDN_prepared.hype.zip">this file</a> to get started quickly. 

Or, you even have a third option, which is also backed by a CDN. The below option is fronted by Cloudflare, which pulls from Nearly Free Speech, with 1 year expires headers: 

`https://hypelibrary.rememberi.es`

## When should you use this? 

Some advertising networks have low file size limits for your uploaded creatives: this runtime URL might help you stay under that limit. Also, if your site loads multiple Hype documents, the Hype Library might be downloading each time a new Hype Document is loaded. Using this CDN will ensure the file is downloaded only a single time.

## Stay Updated

[Learn more, ask questions, and subscribe to updates here](https://forums.tumult.com/t/unofficial-tumult-hype-cdn/12912). No warranties are provided for this free service. 

To setup your own CDN, [use the files in this repository](https://github.com/themorgantown/hypelibrary), which will be kept up to date with new Hype releases.  

The best way to be notified when a new Tumult Hype version is updated is by [joining the mailing list](http://tumult.com/hype/#social-signups) or using Hype (which will notify you when a new Hype version is available). 
   
