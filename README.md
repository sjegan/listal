# listal

```
npm install listal -g
```

Simple bot to download pictures from [listal](www.listal.com)

For example, if you want to download all images in listal from inception just type:

```bash
listal -u http://www.listal.com/movie/inception
```

If you want all the pictures from the director:

```bash
listal -u http://www.listal.com/christopher-nolan
```

Or if you are on the naughty side and want the pictures of diCaprio or Ellen Page try:

```bash
listal -u http://www.listal.com/leonardo-dicaprio
listal -u http://www.listal.com/ellen-page
```

All pictures are downloaded by default to `target/resource_name` but you can change this with the `-o` option.

I used to have 5 concurrent pages at a time, but OSX EMFILE was giving me problems, so I set it to two.

If by any weird reason someone starts using this, open issues to address all the stuff I didn't bother doing:
* Exposing timeout to quit
* Exposing number of concurrent pages
* Better handling of the `-u` option, for example accept bad urls
* Better code in some areas.

