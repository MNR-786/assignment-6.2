* {
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 32px 20px;
  font-family: Arial, sans-serif;
  background: #f1f4f8;
  color: #243247;
}

.page {
  max-width: 1000px;
  margin: 0 auto;
}

h1 {
  margin-bottom: 28px;
  text-align: center;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  width: 280px;
  height: 270px;
  max-width: 100%;
  padding: 24px;
  border: 2px solid;
  border-radius: 18px;
}

.card h2 {
  margin-top: 0;
}

.card p {
  min-height: 68px;
  line-height: 1.5;
}

button {
  display: block;
  width: 100%;
  padding: 12px;
  border: 0;
  border-radius: 8px;
  font-size: 1rem;
  font-weight: bold;
  cursor: pointer;
}

.basic {
  border-color: #5d83aa;
  background: #e7f1fb;
}

.basic button {
  background: #386b9c;
  color: white;
}

.standard {
  border-color: #35866a;
  background: #e4f5ed;
}

.standard button {
  background: #267454;
  color: white;
}

.premium {
  border-color: #ae7925;
  background: #fff2d9;
}

.premium button {
  background: #986414;
  color: white;
}

.display-demo {
  max-width: 700px;
  margin: 40px auto 0;
  padding: 24px;
  border: 1px solid #ccd5df;
  border-radius: 12px;
  background: white;
}

.block-example {
  display: block;
  padding: 10px;
  background: #e7f1fb;
}

.inline-example {
  display: inline;
  padding: 4px;
  background: #ffe8c2;
}

.inline-block-example {
  display: inline-block;
  width: 170px;
  height: 42px;
  margin: 12px 6px 0 0;
  padding: 10px;
  border-radius: 6px;
  background: #e4f5ed;
  color: #205d47;
  text-align: center;
  text-decoration: none;
}