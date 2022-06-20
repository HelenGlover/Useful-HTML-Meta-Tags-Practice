# Useful Meta Tags for HTML

**Context: Zipa's Pizzeria**🍕
<h3>Language</h3>
<p>Present at the top of every html file. Specifies the language - in this case english in the U.S. </p>

```
<!DOCTYPE html> 
<html lang="en-US"> 
```

<h3>Universal character set</h3> 
<p>Used for character encoding. Important to keep at top to prevent the browser from having to go back and reparse the file</p>

```
<meta charset = "UTF-8"/>
```

<h3>Responsive web design</h3>

- `<p> content`ensures that the viewport width is set to the device's width</p>
- `<p> scale` ensures there is no zooming, it is set to default or 100%</p>
- <p> There are more attributes which can be found on <a href="https://css-tricks.com/snippets/html/responsive-meta-tag/">CSS-Tricks</a></p>

```
<meta name="viewport" content="width=device-width, initial-scale=1.0"/> 
```
<h3> Author/designer of the html page </h3>

```
<meta name="author" content="Helen"/>
```

<h3>Last date of being updated</h3>

```
<meta name = "revised" content = "Zipapizzera, 4/17/2022" />
```
<h3>Turn website into graph objects</h3>

- <p> Can be used for other features like music and videos</p>
- <p> Developed and used by Facebook to control its appearance. Use <a href= "https://developers.facebook.com/tools/debug/">Facebook Sharing Debugger</a> to preview how your <br>content will look when it's shared to Facebook</p>

- `<p> og:title` Title of object</p>
- `<p>og:type` Type of object. In this case, it's a website</p>
- `<p> og:image` Image url for the object</p>
- `<p> og:url` URl for redirecting users</p>

```
<meta property="og:title" content="Zipa's Pizzeria" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://www.zipapizzeria.com/en/"/>
<meta property="og:image" content="https://www.imdb.com/title/cheese-pizza/"/>
```

<h3>Theme Color</h3>
<p>Color of the bar above web browser - only supported on mobile devices</p>

```
<meta name="theme-color" content="#a6d698"/>
```

<h3>Content Policy</h3>

- <p>Defines a <a href = "https://content-security-policy.com/">content policy</a> that enhance the security of the website</p>
- `<p> default-src 'self'`is the default policy for fetching resources</p>

```
<meta http-equiv="Content-Security-Policy" content="default-src 'self'">
```

<h3>Redirect from your current site to new </h3>
<p>Best to specify to the users that there will be redirecting to prevent confusion</p>

```
<meta http-equiv="refresh" content="30" url="http://www.zipapizzeriamenu.com"/>
```

<h3>Automatically refresh</h3>
<p> Specify the duration until the website is refreshed in seconds</p>

```
<meta http-equiv="refresh" content="30"/>
```

<h3>Storing cookies</h3> 

- <p> Cookies is used by the Web Server for tracking vistors</p>
- <p> Setting a expiratation date is important. Else, the cookie becomes a "session cookie" (deletes when the user exits the browser)</p>
- <p> PHP uses <a href="https://www.php.net/manual/en/function.setcookie.php">setcookie()</a> which defines cookies </p>

```
<meta http-equiv = "cookie" content = "userid = abc; expires = Wednesday, 01-Aug-23 21:24:35 GMT" />
```


<h3>Keywords for search engines</h3>

```
<meta name="keywords" content="pizza, takeout, delivery, dinner, restaurant, family dinner, wings, sides, pasta"/> 
```

<h3>Website description in the search</h3>

```
<meta name="description" content="Zipa's Pizzeria, serving wood fired pizzas & traditional Italian-American fare since 1995"/>
```


