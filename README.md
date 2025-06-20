# 📦 MERN Snippet Pack – VS Code Snippets for MERN Stack Developers

Boost your MERN development with ready-to-use code snippets to save time and reduce boilerplate.

## 🚀 Features
This extension includes handy snippets for:

- 🟢 **MongoDB (Mongoose)** connection setup
- 🔵 **Express.js** REST API boilerplate
- 🟣 **React** functional components
- 🔐 **JWT authentication** middleware

Just type the prefix and press `Tab` to expand the code.

---

## 💡 Usage

1. Install the extension from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=habibcodes.mern-snippet-pack)
2. Open any `.js`, `.jsx`, `.ts`, or `.tsx` file.
3. Type one of the following prefixes and hit `Tab`:

| Prefix          | Description                       |
|-----------------|-----------------------------------|
| `mongo-conn`    | MongoDB (Mongoose) setup          |
| `express-route` | Express.js route handler template |
| `react-func`    | React functional component        |
| `jwt-auth`      | JWT authentication middleware     |

---

## 🍀 Example

Type `express-route` and hit `Tab` to get:

```js
app.get('/api/example', (req, res) => {
  res.send('Hello from Express!');
});
