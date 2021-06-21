# Ping coming soon

![Project img!](/myPortfolio/img/PIngComingSoon.png)

## The challenge

 Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Submit their email address using an `input` field
- Receive an error message when the `form` is submitted if:
- The `input` field is empty. The message for this error should say *"Whoops! It looks like you forgot to add your email"*
- The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Please provide a valid email address"*

### Links

- [Live](https://brymmobaggins.github.io/Ping-Coming-Soon)

## Built with

- Semantic HTML mark up
- Flexbox
- Grid
- CSS grid
- Vanilla JavaScript

## What I learned

 ```HTML
 <input placeholder="enter your email">
 ```

>>learnt how to import [Google font](Googlefont.com) into CSS file.


```CSS
@import url("https://fonts.googleapis.com/css2?family=Libre+Franklin:wght@300;400&display=swap");
```

 ```JavaScript
function isValidEmail(email) {
    const re = /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
    return re.test(String(email).toLowerCase());
};
```

### Useful resources

- [Stackoverflow](stackoverflow.com) - This helps me understanding the Regular expression(Regex) function to check valid email in an input field.
- [Google-font](Googlefont.com) -  This assists me in getting the accurate font (libre frankin) for the project challenge.
- [fontawesome](fontawesome.com) -  fontawesome library was cool, it also assist me adding nice social media icons and styles.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Brymmobaggins](www.twitter.com/brymmobaggins).

## Acknowledgments

I will like to give a shoutout to Florin pop, Grace snow, and the frontend mentor community for the inspiration and ideas given whilst on the challenge.
