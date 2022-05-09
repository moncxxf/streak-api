# Streak Streaming Link API

Streak API lets you add latest Movies & Tv Shows To your project for free
if you need any movie or tv show to be added be add me on discord : moncef#0580
[demo](https://my-json-server.typicode.com/moncxxf/streak-api/)

## How to use

if you're using javascript use this code
```
name = "The Walking Dead"; // Movie's name
fetch(`https://my-json-server.typicode.com/moncxxf/streak-api/series/${name}`)
      .then((res) => res.json())
      .then((data) => {
         link = data.link.s1e1; // get Season 1 Episode 1 of The Walking Dead
         console.log(link) // output : https://vidshar.org/embed-bb3ves72vip3.html
    })
    .catch(err => {
        console.error(err);
    });
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Alert

Education Purposes Only.
im not responsible for any issue because this is illegal
