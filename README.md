<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    .typing-container {
      font-family: 'Fira Code', monospace;
      font-weight: 600;
      font-size: 25px;
      color: white;
      text-align: center;
      white-space: nowrap;
      overflow: hidden;
      border-right: .15em solid orange;
      animation: typing 4s steps(30, end), blink-caret .75s step-end infinite;
      text-shadow:
        -1px -1px 0 #000,  
         1px -1px 0 #000,
        -1px  1px 0 #000,
         1px  1px 0 #000;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }

    @keyframes blink-caret {
      from, to { border-color: transparent }
      50% { border-color: orange; }
    }
  </style>
</head>
<body>
  <p align="center">
    <span class="typing-container">Olá, eu sou Derek Diniz! ☕</span>
  </p>
</body>
</html>



