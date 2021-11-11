# moc-lyrics
moc-lyrics is a simple bash script that fetches the lyrics of current song playing in [MOC] (music on console) music player.


### Dependencies :
- Perl - Perl (Practical Extraction and Reporting Language) originally developed by Larry Wall is a family of high-level, general-purpose, interpreted, dynamic programming languages. [Perl] is available in repositories of almost every Linux distribution under the sun. Use your distribution's package manager to install it. Perl Module [URI::Escape] is needed.
- Wget - [Wget] is a free software package for retrieving files using HTTP, HTTPS and FTP, the most widely-used Internet
protocols. Most Linux distributions have Wget in their package repositories so you can easily install Wget via the package manager of your distribution in case it is not installed on your system.


### Installation :
Very easy.

Obtain sudo privileges and download [moc-lyrics-master.zip],

```sh
sudo -s
wget --content-disposition https://github.com/hakerdefo/moc-lyrics/archive/master.zip
```

Extract it,

```sh
unzip moc-lyrics-master.zip
```

Make **moc-lyrics** executable and copy it to **/usr/local/bin/** directory,

 ```sh
chmod 755 moc-lyrics-master/moc-lyrics
cp moc-lyrics-master/moc-lyrics /usr/local/bin/
```

And finally clean up the leftovers and drop sudo privileges,

```sh
rm moc-lyrics-master.zip
rm -rf moc-lyrics-master/
exit
```


### Usage :
Run moc-lyrics and it will fetch and print lyrics of the song currently playing in MOC music player.


### Support :

If you like **moc-lyrics**, please consider supporting it, even the smallest contribution goes a long way. It is quick & easy via PayPal, Buy Me a Coffee or Liberapay:  

[![Support via PayPal](https://cdn.jsdelivr.net/gh/twolfson/paypal-github-button@1.0.0/dist/button.svg)](https://paypal.me/hakerdefo)  
[!["Buy Me A Coffee"](https://user-images.githubusercontent.com/1376749/120938564-50c59780-c6e1-11eb-814f-22a0399623c5.png)](https://www.buymeacoffee.com/hakerdefo)  
[![Support via Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/hakerdefo/donate)  


### Credits :
[Federico Builes] - moc-lyrics wouldn't have been possible without wonderful [makeitpersonal] created by Federico.


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">moc-lyrics</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/moc-lyrics)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[perl]:https://www.perl.org
[URI::Escape]:http://search.cpan.org/dist/URI/lib/URI/Escape.pm
[Wget]:https://www.gnu.org/software/wget/
[moc-lyrics-master.zip]:https://github.com/hakerdefo/moc-lyrics/archive/master.zip
[MOC]:http://moc.daper.net
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal
