
<html>
<head>
    <title>Menu</title>
    <script type="text/javascript">
        const names = ["John", "Sarah", "Jack", "Mary", "James"];

for (let i = 0; i < names.length; i++) {
  const firstLetter = names[i][0];
  if (firstLetter.toUpperCase() === "J") {
    console.log(`Goodbye ${names[i]}`);
  } else {
    console.log(`Hello ${names[i]}`);
  }
}

    </script>
        
</head>
<body>
    <header>
        <h1>check the console messages</h1>
    </header>
    
</body>
</html>
