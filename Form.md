# 📝 Complete HTML Forms + Tables + Entities (All-in-One with Emojis)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms and Tables All-in-One</title>
</head>
<body>

    <!-- 👤 Username / 🔒 Password / 📞 Number / ⏰ Time / 🎨 Color -->
    <form action="/server">
        <label>
            Username 👤:
            <input type="text" placeholder="enter username" id="username" name="username">
        </label>
        <br>

        <label>
            Password 🔒:
            <input type="password" placeholder="enter password" id="password" name="password">
            <br>
        </label>

        <label>
            Number 📞:
            <input type="number" placeholder="enter number" name="num">
            <br>
        </label>

        <label>
            Time ⏰:
            <input type="time" placeholder="enter time" name="usertime">
            <br>
        </label>

        <label>
            Color 🎨:
            <input type="color" placeholder="enter color" name="favcolor">
        </label>
        <br>

        DIFFERENT TYPES OF BUTTON 🖲️
        <br>
        <button name="submitBtn" value="clicked">submit</button>
        <button type="button" name="helloBtn" value="hello">Hello</button> 
        <button type="reset" name="resetBtn" value="reset">reset</button>
        <br>
        <input type="button" value="click me" name="clickBtn">
        <input type="submit" name="submitBtn2">
    </form>

    <hr>

    <!-- 🔎 YouTube Search -->
    <form action="https://www.youtube.com/results" method="get">
        <input type="text" placeholder="search in youtube" name="search_query">
        <button type="submit" name="ytBtn" value="search">Search</button>
        <label for="age"> I am 18+ ✅ </label>
    </form>

    <hr>

    <!-- ✅ Checkbox + 🍎🥭🍇 Radio -->
    <form action="/server">
        <input type="checkbox" id="age" name="age" value="18+">
        <label for="age"> I am 18+ ✅ </label>
        <button>submit</button>
        <br>

        <input type="radio" name="fruit" id="apple" value="apple">
        <label for="apple">apple 🍎</label>

        <input type="radio" name="fruit" id="mango" value="mango">
        <label for="mango">mango 🥭</label>

        <input type="radio" name="fruit" id="grapes" value="grapes">
        <label for="grapes">grapes 🍇</label>
       
        <button>submit</button>
    </form>

    <hr>

    <!-- 💼 Profession + 🔊 Volume -->
    <form>
        Choose your profession 💼:
        <select name="profession" id="profession">
            <option value="stu">Student 👨‍🎓</option>
            <option value="dev">Developer 👨‍💻</option>
        </select>
        <br>

        <label for="vol">Select your volume level 🔊: </label>
        <input type="range" id="vol" min="0" max="100" name="vol">
    </form>

    <hr>

    <!-- 📏 HTML Entities Example -->
    <p>Example of spacing with HTML entity: Hello&nbsp;&nbsp;&nbsp;World 👋</p>

    <hr>

    <!-- 📊 Table Example -->
    <table border="1">
        <thead>
            <tr>
                <th>Fruit Name 🍎</th>
                <th>Price 💰</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Apple</td>
                <td>$2</td>
            </tr>
            <tr>
                <td>Mango</td>
                <td>$3</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="2">End of Table ✅</td>
            </tr>
        </tfoot>
    </table>

    <!-- 📚 Explanation -->
    <p>
        - `<tr>` → used to display **table row** <br>
        - `<td>` → used to display **table data** <br>
        - `<th>` → used to display **table header** <br>
        - `<thead>` → wraps **table header** <br>
        - `<tbody>` → wraps **table body** <br>
        - `<tfoot>` → wraps **table footer** <br>
    </p>

</body>
</html>
