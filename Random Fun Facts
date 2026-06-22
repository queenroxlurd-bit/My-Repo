`html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Random Fun Facts</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f9f9;
      color: #333;
      text-align: center;
      padding: 50px;
    }
    h1 {
      color: #2c7a7b;
    }
    .fact {
      background: #e6fffa;
      border: 1px solid #b2f5ea;
      border-radius: 8px;
      padding: 15px;
      margin: 10px auto;
      width: 60%;
      font-size: 1.2em;
      transition: opacity 0.5s ease-in-out;
    }
  </style>
</head>
<body>
  <h1>🎉 Random Fun Facts 🎉</h1>
  <div id="facts"></div>

  <script>
    const funFacts = [
      "Bananas are berries, but strawberries are not.",
      "Octopuses have three hearts.",
      "Honey never spoils — archaeologists have found edible honey in ancient tombs.",
      "Sharks existed before trees.",
      "Sloths can hold their breath longer than dolphins.",
      "A day on Venus is longer than a year on Venus."
    ];

    function getRandomFacts(num) {
      const shuffled = funFacts.sort(() => 0.5 - Math.random());
      return shuffled.slice(0, num);
    }

    function displayFacts() {
      const factsContainer = document.getElementById("facts");
      factsContainer.innerHTML = "";
      const randomFacts = getRandomFacts(2);
      randomFacts.forEach(fact => {
        const factDiv = document.createElement("div");
        factDiv.className = "fact";
        factDiv.textContent = fact;
        factsContainer.appendChild(factDiv);
      });
    }

    // Show initial facts
    displayFacts();

    // Change facts every 5 seconds
    setInterval(displayFacts, 5000);
  </script>
</body>
</html>
`
