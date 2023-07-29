# adampaulukanis.github.io

My webpage should have/be:

- about page, I would like to have there my signature Adam Paulukanis done in
  SVG which would like hand written and animated.
- some good contact information
- a list of my projects
- etc.

## Using Github Pages for public API

I created a test file, *test.json*, for this purpose.

```
var url = 'https://adampaulukanis.github.io/test.json';

fetch(url)
    .then(response => {
        return response.json();
    })
    .then(resJson => {
        console.log(resJson);
    });
// The answer
Udało sie
{name: 'to jest test', data: '2023-07-29T17:09'}
```
