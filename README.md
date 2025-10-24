body {
    font-family: Arial, sans-serif;
    background: #f1f7fb;
    margin: 0;
    padding: 0;
}

header {
    background: #0077b6;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

nav {
    margin-top: 10px;
}

nav a {
    color: #ffca28;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bold;
    font-size: 16px;
}

#hero {
    background: #caf0f8;
    text-align: center;
    padding: 30px 10px;
}

#hero img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    margin-top: 15px;
}

section {
    margin: 30px;
    padding: 20px;
    background: #fff;
    border-radius: 7px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.05);
}

ul {
    list-style-type: disc;
    padding-left: 20px;
}

footer {
    background: #023e8a;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

@media (max-width: 600px) {
    section { margin: 10px; padding: 10px; }
    header, footer { padding: 10px 0; }
    nav a { margin: 0 5px; font-size: 14px; }
}
