/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f4f4;
  color: #222;
  line-height: 1.6;
}

/* Header & Nav */
header {
  background-color: #003300;
  color: #fff;
  padding: 1rem 0;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1100px;
  margin: auto;
  padding: 0 1rem;
}

nav h1 {
  font-size: 1.8rem;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}

nav a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #00cc66;
}

/* Hero Section */
.hero {
  background: linear-gradient(rgba(0, 51, 0, 0.8), rgba(0, 51, 0, 0.8)), url('https://via.placeholder.com/1200x400') center/cover;
  color: #fff;
  text-align: center;
  padding: 4rem 1rem;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
}

/* Sections */
section {
  max-width: 1000px;
  margin: auto;
  padding: 2rem 1rem;
}

h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  colo
