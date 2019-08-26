# alfred-snippets
Collection of snippets for use in Alfred 3

## Git Commands
Snippet collection of the Git commands I most frequently use. Note: does not use prefix.

Includes:

| Keyword | Snippet |
| ------- | ------- |
gstat | `git status`
gadd | `git add .`
gcheck | `git checkout`
gmerge | `git merge`
gpush | `git push`
gpull | `git pull`
gcommit | `git commit -m "{cursor}"`


---

## HTML Snippets
Just a few HTML-related shortcuts. All keywords prefixed with `!`.

| Keyword | Snippet |
| ------- | ------- |
!h5 | Skeleton HTML document structure
!icon | Snippet for Font Awesome icon 
!docready | Wrapper function for document ready


### !h5
```<!doctype html>
<html class="no-js" lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <title></title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">

        <link rel="apple-touch-icon" href="apple-touch-icon.png">
        <!-- Place favicon.ico in the root directory -->

    </head>
    <body>

        <p>Hello world! This is HTML5 Boilerplate.</p>
  
    </body>
</html>
``` 
### !icon
`<span class="fa " aria-hidden="true"></span> `

### !docready
```$( document ).ready(function() {
    console.log( "ready!" );
});
```


---
&copy; by Tim White, 2019

Testing commit
