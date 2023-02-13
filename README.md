# wackpack-webring
im going to host stuff for a wackpack web ring here. currently uses onionring.js: https://garlic.garden/onionring/, but planning to rework the whole repo to resemble https://tildegit.org/khuxkm/molniya

## wtf is a webring

old school way of browsing the net, basically people's sites served as nodes in a circular graph and they would show it in a widget in their site. the widget would then link to adjacent nodes, and also offer a random option as well. webrings could be between friend groups, communities, or entire groups of interest like fandoms and industries. since search engines keep getting shittier, webrings are being revived as part of a greater oldnet revival movement. also it is fun. 

## joining the webring

add ur website's full url to the list of urls in the variables file. then to embed the widget, add this where you want it to appear:
```
<div id='wackpack-webring'>
<script type="text/javascript" src="https://raw.githubusercontent.com/Wack-Pack/wackpack-webring/main/onionring-variables.js"></script>
<script type="text/javascript" src="https://raw.githubusercontent.com/Wack-Pack/wackpack-webring/main/onionring-widget.js"></script>
</div>
```   
and unless you intend on styling your widget yourself (in which case you should look at onionring.css for reference code) add this to the head section:
```
<link rel="stylesheet" href="https://raw.githubusercontent.com/Wack-Pack/wackpack-webring/main/onionring.css">
```
update: it appears this only works if your site's host supports CORS. which free neocities does not. this whole repo will have to be reworked

## license 

if somebody manages to make an nft with this i will legally shit myself
