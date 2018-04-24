# Hype Library CDN

This repo contains files required to roll your own content delivery network for Hype's runtime libraries. To learn more about this feature in Tumult Hype, [visit this page](http://tumult.com/hype/documentation/3.0/#external-runtime-hosting). 

# Use this CDN

Use this URL in Tumult Hype's advanced export to load the library from the excellent [Rawgit](https://rawgit.com/) service:

`https://cdn.rawgit.com/themorgantown/hypelibrary/master`

Your Advanced Export should look like this: 

![](https://raw.githubusercontent.com/themorgantown/hypelibrary/master/image.png)

## More info

This is essentially a CDN you can use with [Tumult Hype's](http://tumult.com/hype/pro) Advanced Export option. If your site loads multiple Hype documents, the Hype Library might be downloading each time a new Hype Document is loaded. Using this CDN will add the Hype Library to your browser cache and generally speed things up. This service is offered without warranty. [Learn more, ask questions, and subscribe to updates here](https://forums.tumult.com/t/latest-hype-lib-on-cloudflare-or-similiar-cdn/10997/2?u=daniel).

To setup your own CDN, [use the files in this repository](https://github.com/themorgantown/hypelibrary), which will be kept up to date with new Hype releases. 

Use this URL in Tumult Hype's advanced export to load from this site, which is fronted by Cloudflare with 1 year expires headers:

`https://hypelibrary.rememberi.es`

The best way to be notified when a new Tumult Hype version is updated is by opening [joining the mailing list](http://tumult.com/hype/#social-signups).
