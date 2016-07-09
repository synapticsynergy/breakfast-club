# Oh, I Didn't Know That... But Now I Do

Any interesting tidbits or observations that someone else will find useful:

E.g:

### Express
* Order matters in express when dealing with middleware

### Angular
* If you want your controller to work, you have to call it yourself

* Factories and services persist, controllers are destroyed every time

* Factories return an object

### React
* If nothing is showing on your react view, you probably didn't compile the
assets using babel

### Vagrant
* Noobs, use vagrant at your own peril

### Mongoose
If you're having trouble connecting to the default port:

```
mongoose.connect('mongodb://localhost/myapp');

```

You can try to use 127.0.0.1 instead of localhost:

```
mongoose.connect('mongodb://127.0.0.1:27017/myapp');

```
[Source](http://mongoosejs.com/docs/connections.html)