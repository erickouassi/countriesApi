# A Collection of countries data
country name, name of holiday, date of holiday, and more.

A web service for developers.

I am primarily maintaining this repository for my own use cases. 

# USAGE
### Endpoint
This API does not require any form of Authentication or token.
The API has one endpoint to assist developers. Note that the endpoint return JSON and are available over `https`. This API takes no inputs.<br />
## <> Available resources
      "country": ✅ Ok,
      "emoji_flag": ⌛ coming soon,
      "name_of_holiday": ✅ Ok,
      "date_of_holiday": ✅ Ok,
      "independence_from": ✅ Ok,
      "top-level_domain": ⌛ coming soon,
      "currency": ⌛ coming soon,
      "capital": ⌛ coming soon,
      "anthem_title": ⌛ coming soon,
      "anthem_audio": ⌛ coming soon

-`Get` CountriesApi [./countriesApi.json](https://raw.githubusercontent.com/erickouassi/countriesApi/main/countriesApi.json)

### Use in your own language

I prefered javascript(Fetch) but you can use PHP, Python, Java, etc

``` 
var requestOptions = {
    method: 'GET',
    redirect: 'follow'
  };

  fetch("https://raw.githubusercontent.com/erickouassi/countriesApi/main/countriesApi.json", requestOptions)
    .then(result => console.log(result))
    .catch(error => console.log('error', error));
```

## How to
 *(A fork is a copy of a repository)*.
1. Fork the repository in your account [Click here](https://github.com/erickouassi/countriesApi/fork)
2. Clone your repository to make a local copy
3. Use your own data (`.json`, `.jpg`, `.png`, and `.mp3`)
   
Note:  Your URL will be `https://your-username.github.io/countriesApi`

Direct link of the file with extension `.json`, `.jpg`, `.png`, and `.mp3`

`https://github.com/your-username/your-repo/blob/main/your-file-name?raw=true`

or 

`https://raw.githubusercontent.com/your-username/your-repo/main/your-file-name`


## Bugs and feature requests
Any problem? Please report it: all bugs, feature requests, pull requests, feedback, etc., are welcome!

First search for [existing and closed issues](https://github.com/erickouassi/countriesApi/issues?utf8=%E2%9C%93&q=is%3Aissue). <br />
If your problem or idea is not addressed yet, please [open a new issue](https://github.com/erickouassi/countriesApi/issues/new/choose).

**If you have questions:**  [erickouassi.com/contact](https://erickouassi.com/contact.html)


If you want any help setting your rosary web app for yourself, group or church, I’d love to help! [contact me here](https://erickouassi.com/contact.html).


##### Buy me a coffee 🥤¶
If this project help you reduce time to develop, please consider [buying me a coffee](https://github.com/sponsors/erickouassi) :)


Note: I am occasionally updating the code.

Happy Coding