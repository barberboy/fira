Fira
====
Quickly drop Mozilla’s [Fira Sans and Fira Mono][Fira Sans] into your project.


Usage
-----
You have several options for using this project:

### Clone with git

```sh
cd styles/fonts
git clone https://github.com/barberboy/Fira
```

```html
<link rel="stylesheet" href="/styles/fonts/Fira/fira.css">
```


### Download

Download and unpack the [.zip archive](https://github.com/barberboy/Fira/archive/master.zip):

```sh
cd styles/fonts
wget https://github.com/barberboy/Fira/archive/master.zip
unzip master.zip
mv Fira-master Fira
rm master.zip
```

```html
<link rel="stylesheet" href="/styles/fonts/Fira/fira.css">
```


### Bower

```sh
bower install barberboy/Fira
```

```html
<link rel="stylesheet" href="/bower_components/Fira/fira.css">
```

If you’d like bower to put it in a different directory, just create a
[`.bowerrc`](http://bower.io/docs/config/) file and specify the
[`directory`](http://bower.io/docs/config/#directory) location:

```json
{
  "directory": "app/public",
  "analytics": false
}
```

### CDN

Quickly test Fira Sans on your site by using the CDN hosted by [RawGit]. Feel
free to use it in production as well:

```html
<link rel="stylesheet" href="https://cdn.rawgit.com/barberboy/Fira/3.1.1/fira.css">
```


### Mozilla CDN

Not for you? Just use Mozilla’s CDN:

```html
<link rel="stylesheet" href="https://code.cdn.mozilla.net/fonts/fira.css">
```


Fonts and Weights
-----------------
This project includes Fira Sans normal and italic styles in
[**nine** different weights][Fira Sans], and Fira Mono in two. Pick and choose
what you’d need.

### Fira Sans

```css
body {
  font-family: 'Fira Sans';
  font-weight: 100;

  font-family: 'Fira Sans';
  font-weight: 200;

  font-family: 'Fira Sans';
  font-weight: 300;

  font-family: 'Fira Sans';
  font-weight: 400;

  font-family: 'Fira Sans';
  font-weight: 500;

  font-family: 'Fira Sans';
  font-weight: 600;

  font-family: 'Fira Sans';
  font-weight: 700;

  font-family: 'Fira Sans';
  font-weight: 800;

  font-family: 'Fira Sans';
  font-weight: 900;
}
```

### Fira Mono

```css
code, kbd, samp, pre, tt, var, textarea {
  font-family: 'Fira Mono';
  font-weight: 400;

  font-family: 'Fira Mono';
  font-weight: 600;
}
```

[RawGit]: https://rawgit.com/
[Fira Sans]: http://mozilla.github.io/Fira/