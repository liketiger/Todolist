# Todolist

<h1> Webpage detail </h1>
- Todolist for personal use <br>
- Created to practice node.js <br>

<h1> Deployed link </h1>
<a href="https://stark-beyond-54418.herokuapp.com/">https://stark-beyond-54418.herokuapp.com/</a> <br>

![스크린샷 2021-08-10 오후 2 50 58](https://user-images.githubusercontent.com/50165633/128815042-e3e9af8b-3e1c-40bb-addb-eb116e1a0f84.png)

<br>

<h1>Refactoring</h1>
able to reduce lines of code using app.route()
<br><br>
<strong>before</strong> :
<br><br>
app.get("/", ...{
<br>...<br>
});
<br><br>
app.post("/", ...{
<br>...<br>
});
<br><br>
<strong>after</strong> :
<br><br>
app.route("/").get(...).post(...);

<h1>Used tech</h1>
Node.js / express / MongoDB / Mongoose / Atlas
