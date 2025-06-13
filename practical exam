<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Web Tech Tasks</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 40px;
    }

    h2 {
      color: #005b7f;
    }

    .info-bar {
      background-color: #0d5d78;
      color: white;
      padding: 10px;
      margin: 20px 0;
      font-weight: bold;
    }

    .task-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-bottom: 40px;
    }

    .task-buttons button {
      background-color: #0d5d78;
      color: white;
      padding: 12px 25px;
      border-radius: 10px;
      font-size: 16px;
      border: none;
      cursor: pointer;
    }

    .task-buttons button:hover {
      background-color: #09475d;
    }

    .project-section {
      margin-top: 30px;
    }

    .screenshots {
      margin-top: 30px;
      font-size: 24px;
      color: #0d5d78;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <h2>STUDENT NAME :Alwiya Saju</h2>
  <h2>CURRENT DATE :13/06/2025</h2>
  <h2>SUBJECT NAME :Web Technologies</h2>
  <div class="info-bar">INFORMATION ABOUT ME :I am Alwiya Saju,first semester 'Information Systems' student at ISMA university Riga,Latvia </div>

  <h3>Task Details :</h3>
  <div class="task-buttons">
    <button onclick="task1()">Task 1</button>
    <button onclick="task2()">Task 1</button>
    <button onclick="task3()">Task 1</button>
    <button onclick="task4()">Task 1</button>
    <button onclick="task5()">Task 1</button>
    <button onclick="task6()">Task 1</button>
    <button onclick="task7()">Task 1</button>
    <button onclick="task8()">Task 1</button>
    <button onclick="task9()">Task 1</button>
    <button onclick="task10()">Task 1</button>
  </div>

  <div class="project-section">
    <h3>Mini project Title :Local Loop</h3>
     <h4>Information :</h4>
    <p>Prepare a concise presentation covering the following points:</p>
    <p>1) Problem Statement:Describe the problem your project addresses.</p>
    <p>2) Objective: Explain the purpose of your project.</p>
    <p>3) Goal: Define the end goals and intended outcomes of your project.</p>
    <p>3) Result/Output: Outline the expected or actual results.</p>
    <p>4) Technology Used: List the tools, languages, or frameworks you used.</p>
    <p>5) User Audience: Identify the target audience or users of your project.</p>
    <p>6) Impact on Society: Discuss how your project could benefit society or people in general.</p>
  </div>

  <div class="screenshots">SCREENSHOTS</div>

  <!-- JavaScript Tasks -->
  <script>
    function task1() {
      let input = prompt("Enter array elements separated by commas:");
      let array = input.split(",");
      alert("The last element is: " + array[array.length - 1]);
    }

    function task2() {
      let number = prompt("Enter a 10-digit number:");
      if (/^\d{10}$/.test(number)) {
        alert("Valid 10-digit number: " + number);
      } else {
        alert("Invalid! Enter exactly 10 digits.");
      }
    }

    function task3() {
      let arr = prompt("Enter words separated by commas").split(",");
      let word = prompt("Enter word to find:");
      let found = arr.includes(word);
      alert(found ? "Word found!" : "Word not found.");

      let combined = arr.join("").toLowerCase();
      let counts = {};
      for (let char of combined) {
        counts[char] = (counts[char] || 0) + 1;
      }
      let repeated = Object.entries(counts).filter(([_, count]) => count > 1);
      alert("Repeated characters: " + repeated.map(([ch]) => ch).join(", "));
    }

    function task4() {
      let chars = prompt("Enter characters separated by commas:").split(",");
      let vowels = ['a', 'e', 'i', 'o', 'u'];
      let count = chars.filter(c => vowels.includes(c.toLowerCase())).length;
      alert("Number of vowels: " + count);
    }

    function task5() {
      let str = prompt("Enter a sentence:");
      let words = str.split(" ");
      let longest = words.reduce((a, b) => a.length > b.length ? a : b);
      alert("Longest word: " + longest);
    }

    function task6() {
      let str = prompt("Enter text:");
      let converted = '';
      for (let ch of str) {
        converted += (ch === ch.toUpperCase()) ? ch.toLowerCase() : ch.toUpperCase();
      }
      alert("Converted: " + converted);
    }

    function task7() {
      let sentence = prompt("Enter a sentence:");
      let word = prompt("Enter word to find:");
      let index = sentence.indexOf(word);
      alert(index !== -1 ? `Found at position: ${index}` : "Word not found.");
    }

    function task8() {
      let arr = ["A", "B", "C", "D", "E"];
      arr.splice(2, 1); // delete
      arr.splice(1, 0, "X"); // insert
      arr.splice(3, 1, "Y"); // replace
      alert("Modified array: " + arr.join(", "));
    }

    function task9() {
      let str = prompt("Enter a string:");
      let words = str.trim().split(/\s+/).length;
      let chars = str.length;
      let spaces = (str.match(/ /g) || []).length;
      let symbols = (str.match(/[!@#$%^&*()_+\-=\[\]{};':"\\|,.<>\/?]/g) || []).length;
      alert(`Words: ${words}, Characters: ${chars}, Spaces: ${spaces}, Symbols: ${symbols}`);
    }

    function task10() {
      let a = prompt("Enter first value:");
      let b = prompt("Enter second value:");
      let op = prompt("Enter operator (+, -, *, /):");

      let isNumber = !isNaN(a) && !isNaN(b);
      let result;

      if (isNumber) {
        a = parseFloat(a);
        b = parseFloat(b);
        switch (op) {
          case '+': result = a + b; break;
          case '-': result = a - b; break;
          case '*': result = a * b; break;
          case '/': result = b !== 0 ? a / b : "Division by zero"; break;
          default: result = "Invalid operator";
        }
      } else {
        result = op === '+' ? a + b : "Only addition allowed for strings.";
      }

      alert("Result: " + result);
    }
  </script>
</body>
</html>




