# Solutions to the Learn Basic Web Blocks and Styling

## Q1. HTML 1

**Solution :-**
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Add the Relevant HTML Tags</title>
    <style>
        .header {
            background-color: lightgray;
            padding: 10px;
        }

        .nav-link {
            margin: 0 10px;
            text-decoration: none;
            color: black;
        }

        .nav-link:hover {
            color: blue;
        }

        .main-content h2 {
            font-family: Arial, sans-serif;
        }

        .image {
            display: block;
            margin: 0 auto;
        }
    </style>
</head>

<body>
    <!-- Header Section -->
    <header class="header">
        <h1>Page Title</h1>
        <nav>
            <a href="#" class="nav-link">Home</a>
            <a href="#" class="nav-link">About</a>
            <a href="#" class="nav-link">Contact</a>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main class="main-content">
        <h2>This is main heading</h2>
        <p>This is a paragraph of text.</p>
        <img class="image" src="https://static.vecteezy.com/system/resources/previews/032/257/185/non_2x/wallpapers-for-the-beautiful-peacock-wallpaper-ai-generated-free-photo.jpg" alt="Nature Image" width="300px">
    </main>

    <!-- Footer Section -->
    <footer>
        <p>© 2024 Your Name</p>
    </footer>
</body>

</html>
```
## [Click Here for the output](https://onecompiler.com/html/432vz2zwn)


## Q2. HTML2 

**solution: -**

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fill in the Blanks</title>
    <style>
        .list-item {
            border: 1px solid black;
            padding: 5px;
            margin: 5px 0;
        }

        .button {
            background-color: blue;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }

        .button:hover {
            background-color: darkblue;
        }

        .title {
            color: black;
            font-size: 24px;
        }

        .description {
            color: gray;
            font-size: 16px;
        }

        .form-field {
            width: 100%;
            padding: 8px;
            border: 1px solid gray;
            margin-bottom: 10px;
        }
    </style>
</head>

<body>
    <!-- First Section with Heading -->
    <section>
        <h2 class="title">Section Heading</h2>
        <ul>
            <li class="list-item">Item 1</li>
            <li class="list-item">Item 2</li>
            <li class="list-item">Item 3</li>
        </ul>
    </section>

    <!-- Second Section with Description and Button -->
    <section>
        <p class="description">This is a description for the second section.</p>
        <button class="button">Click Me</button>
    </section>

    <!-- Third Section with Form -->
    <section>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" class="form-field">
            <label for="email">Email:</label>
            <input type="email" id="email" class="form-field">
            <button type="submit" class="button">Submit</button>
        </form>
    </section>
</body>

</html>
```
## [Click here for the HTML 2 solution](https://onecompiler.com/html/432vzsv2u)

## CSS1

**solution :-**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fill in the Blanks</title>
    <style>
        .list-item {
            border: 1px solid black;
            padding: 5px;
            margin: 5px 0;
        }
        .button {
            background-color: blue;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .button:hover {
            background-color: darkblue;
        }
        .title {
            color: black;
            font-size: 24px;
        }
        .description {
            color: gray;
            font-size: 16px;
        }
        .form-field {
            width: 100%;
            padding: 8px;
            border: 1px solid gray;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <!-- First Section -->
    <section>
        <h2 class="title">Section Heading</h2>
        <ul>
            <li class="list-item">Item 1</li>
            <li class="list-item">Item 2</li>
            <li class="list-item">Item 3</li>
        </ul>
    </section>

    <!-- Second Section -->
    <section>
        <p class="description">This is a description text section explaining key actions.</p>
        <button class="button">Click Me</button>
    </section>

    <!-- Third Section with Form -->
    <section>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" class="form-field">
            <label for="email">Email:</label>
            <input type="email" id="email" class="form-field">
            <button class="button" type="submit">Submit</button>
        </form>
    </section>
</body>
</html>
```

## [Click here for the solution](https://onecompiler.com/html/432w2w3fm)


## CSS2 

**Solution: -**
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Fill in the Blanks</title>
    <style>
         /* This is called as comment                   */
        /*  Need to write your answer between :  ;     */
       /*   Remove the _____ and write your answer    */
      /*    Example:  border: 1px solid teal;         */

.list-item {
  border: 1px solid teal;
  padding: 10px;
  margin: 5px;
}

#action-button {
  background-color: blue;
  color: white;
  padding: 10px 15px;
  border: none;
  cursor: pointer;
}

#action-button:hover {
  background-color: darkblue;
}

.title {
  color: black;
  font-size: 24px;
}

.description {
  color: gray;
  font-size: 16px;
}

.form-field {
  width: 100%;
  padding: 8px;
  border: 1px solid gray;
  margin-bottom: 10px;
}

    </style>
  </head>
  <body>
    <section>
      <h2 class="title">My List</h2>
      <ul>
        <li class="list-item">Item 1</li>
        <li class="list-item">Item 2</li>
        <li class="list-item">Item 3</li>
      </ul>
    </section>
    <section>
      <p class="description">Here is some text.</p>
      <button id="action-button">Click Me</button>
    </section>
    <section>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" class="form-field" />
        <label for="email">Email:</label>
        <input type="email" id="email" class="form-field" />
        <button type="submit" id="submit-button">Submit</button>
      </form>
    </section>
  </body>
</html>

```
## [Click here for solution](https://onecompiler.com/html/432w2g6ep)