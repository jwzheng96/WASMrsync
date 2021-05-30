# WASMrsync

Javascript Implementation of WebAsssembly-based delta sync with optimizations.

*Notice: 

1. As a demo, we replace ECS API with local File API so that you can run locally.
2. Use pure javascript version of server side so you don't need to compile c++ code (which is same as Linux Rsync).

## Get started
> environment: node.js v6.9.0
>> \>\> git clone this repository
>> 
>> \>\> install npm
>> 
>> \>\> cd to the path of this project
>> 
>> \>\> npm install
>> 
>> \>\> node bin/www
>> 
>> \>\> Now ,visit localhost:8080 on your browser

## Document
> Javascript Implementation of rsync algorithm: public/js/bit-sync.js
> 
> WASMrsync Client: public/js/sync-client.js
> 
> WASMrsync Server: app.js
