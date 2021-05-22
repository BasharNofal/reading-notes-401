# Application State with Redux

## Review, Research, and Discussion

1. If you're using httpOnly and secure cookies, that means your cookies cannot be accessed using JavaScript. This means, even if an attacker can run JS on your site, they can't read your access token from the cookie.
It's automatically sent in every HTTP request to your server.

2. **Third-party cookies** are cookies that are set by a website other than the one you are currently on.

3. **Pixel tag** A tag (or often called pixel) is a short snippet of javascript (code) that does something on your website. In the context of marketing/advertising tags and pixels, they are often collecting some information about the visitor to a website and their behavior on the site.

### Terms

* **Cookies:** it's browser storage that is added when you visit a website, its size is 4kB and it's usually used for storing tokens.
* **Authorization:** allowing a user to access or to do something.
* **Access control:** setting the rules and permissions for users based on their role.
* **Conditional rendering:** rendering components based on a certain condition.

<hr>

## Preview

* **Redux** is another state management library that allows you to share states between nested components easier.

* Redux stores all states in one place called **store** which makes accessing these states easier by your app components.

* Changing a state in redux will trigger an action which apply the change that you want in the components.