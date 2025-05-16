# school-children-support<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Формирование двигательных действий</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      background-color: #f0f4ff;
      color: #2c3e50;
    }
    header {
      text-align: center;
      padding: 2rem 1rem;
      background-color: #3b82f6;
      color: white;
    }
    header h1 {
      margin-bottom: 0.5rem;
      font-size: 2rem;
    }
    section {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      margin: 1rem 0;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .card h2 {
      color: #2563eb;
    }
    .subscribe {
      text-align: center;
      margin: 2rem 0;
    }
    input[type=email] {
      padding: 0.5rem;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      margin-right: 0.5rem;
      width: 250px;
    }
    button {
      padding: 0.5rem 1rem;
      background-color: #2563eb;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #1d4ed8;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #e0e7ff;
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #475569;
    }
  </style>
</head>
<body>

<header>
  <h1>Формирование двигательных действий у детей с интеллектуальными нарушениями</h1>
  <p>Образовательный ресурс для специалистов, педагогов и родителей</p>
</header>

<section>
  <div class="card">
    <h2>🎯 Цели и задачи</h2>
    <p>Основная цель — развитие координации, моторики и самостоятельности у детей с интеллектуальными нарушениями через адаптированные физические упражнения и игровые формы.</p>
  </div>

  <div class="card">
    <h2>📚 Методики и подходы</h2>
    <p>Используются современные методики: сенсорная интеграция, игровая терапия, физкультурные минутки и индивидуальный подход к каждому ребенку.</p>
  </div>

  <div class="card">
    <h2>🏃‍♀️ Примеры упражнений</h2>
    <p>• Игра с мячом (броски, ловля)<br>• Балансировка на линии<br>• Простые танцевальные движения под музыку<br>• Подвижные игры на развитие координации</p>
  </div>

  <div class="card">
    <h2>👨‍👩‍👧 Для кого?</h2>
    <p>Педагоги коррекционных школ, специалисты-дефектологи, логопеды, а также родители, желающие развивать двигательную активность у своих детей дома.</p>
  </div>

  <div class="subscribe">
    <h2>📩 Подпишитесь на обновления</h2>
    <input type="email" placeholder="Ваш e-mail" />
    <button onclick="subscribe()">Подписаться</button>
  </div>
</section>

<footer>
  © 2025 Разработано для поддержки инклюзивного образования
</footer>

<script>
  function subscribe() {
    const email = document.querySelector('input[type=email]').value;
    if (email) {
      alert(`Спасибо за подписку, ${email}!`);
    } else {
      alert(\"Пожалуйста, введите корректный e-mail.\");
    }
  }
</script>

</body>
</html>
