# HTML
---

### FORMAT YOUR CODE :
- Use this Gitpod shortcut to quickly correct your HTML indentation :
  - On Windows : `Shift`+`Alt`+`F`
  - On MAC OS: `Shift`+`Option`+`F`
  - On Ubuntu : `Shift`+`Ctrl`+`I`
  
( If it asks you to set up a configuration, just choose 'prettier'. )

---

### HTML FILE STRUCTURE : 
- This is a code comment : `<!-- Hello : -->`
- Each major section of your project should be commented.
- Inside the `<body>`, there are three main elements, which you are expected to incorporate into your project (see below): `<header>`, `<main>`, `<footer>`

*( If your self-closing HTML tags end with an ```/>``` , eg: ```<meta />``` instead of ```<meta>``` this is put in place by **Prettier**. Please leave a comment in your README addressing this, as W3C will flag it with an **info** tag when you validate your files. The issue was raised in this [ticket](https://github.com/prettier/prettier/issues/5641), & closed by the dev as it was not considered to be an issue. )*

```
<body>
    <!-- This is the header : -->
    <header>
        <h1>Your page title here</h1>
        <nav>Navigation links here</nav>
    </header>

    <!-- This is the main : -->
    <main>
        <!-- Hero image : -->
        <section>
            <h2>Your page content here</h2>
        </section>

        <!-- About text : -->
        <section>
            <p>Add as many sections/divs as you need</p>
        </section>
    </main>

    <!-- This is the footer : -->
    <footer>
        <p>Social icons | address | disclaimer : here</p>
    </footer>
</body>
```
---

### FORM DUMP : 
- When adding a `<form>` to your project, upon submit, the user should receive feedback that their submission was successful.
- This will be achieved by adding an `action` to your opening form tag:
```
<form action="https://formdump.codeinstitute.net/">
```
- The link above will route your user to a C.I. created form-dump page, however you can always build your own! A simple HTML file that says **"Thank You!"** will suffice.
 - Should you decide to create your own form-dump page, a nice extra touch is to add this `<meta>` tag inside the head of that page, so that the page redirects back to the home page after a few seconds:
```
<meta http-equiv="refresh" content="10; url=index.html">
```
