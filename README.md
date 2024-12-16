- 👋 Hi, I’m @NIKA22117
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ელექტრო ავტომობილები</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="logo">
      <h1>EV Cars</h1>
      <p>დროა მომავლისთვის!</p>
    </div>
    <nav>
      <ul>
        <li><a href="#new-cars">ახალი ავტომობილები</a></li>
        <li><a href="#used-cars">მეორადი ავტომობილები</a></li>
        <li><a href="#contact">კონტაქტი</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Banner -->
  <section class="main-banner">
    <h2>ახალი და მეორადი ელექტრო ავტომობილები</h2>
    <p>მოწყვეთ უკეთესი მომავალი ელექტრო ავტომობილებით!</p>
    <input type="text" placeholder="მოძებნე ავტომობილი..." />
  </section>

  <!-- Categories Section -->
  <section class="categories">
    <div class="category" id="new-cars">
      <h3>ახალი ავტომობილები</h3>
      <p>შეარჩიეთ ახალი ელექტრო ავტომობილები.</p>
    </div>
    <div class="category" id="used-cars">
      <h3>მეორადი ავტომობილები</h3>
      <p>მოიძიეთ მეორადი ავტომობილები საუკეთესო ფასებში.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h3>კონტაქტი</h3>
    <p>დაგვიკავშირდით საიტის ან თქვენი ავტომობილის შესახებ დამატებითი ინფორმაციისთვის.</p>
  </section>

  <!-- Footer Section -->
  <footer>
    <p>© 2024 EV Cars - ყველა უფლება დაცულია.</p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="ka">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ელექტრო ავტომობილები</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <img src="assets/logo.png" alt="ECO CARS Logo" />
    </div>
    <nav>
      <ul>
        <li><a href="#new-cars">ახალი ავტომობილები</a></li>
        <li><a href="#used-cars">მეორადი ავტომობილები</a></li>
        <li><a href="#contact">კონტაქტი</a></li>
      </ul>
    </nav>
  </header>

  <section class="main-banner">
    <h2>ახალი და მეორადი ელექტრო ავტომობილები</h2>
    <p>მოწყვეთ უკეთესი მომავალი ელექტრო ავტომობილებით!</p>
    <input type="text" placeholder="მოძებნე ავტომობილი..." />
  </section>

  <section class="categories">
    <div class="category" id="new-cars">
      <h3>ახალი ავტომობილები</h3>
      <p>შეარჩიეთ ახალი ელექტრო ავტომობილები.</p>
    </div>
    <div class="category" id="used-cars">
     

სუპერ, რომ დაწყებილი გაქვს! ახლა გადავალთ შემდეგ ნაბიჯებზე, რომ ყველაფრის სწორად მუშაობა და ატვირთვა მოხდეს.

### *2. ფაილების შექმნა*

#### *ა. HTML ფაილი (index.html)*
1. გახსენით თქვენი კომპიუტერი და შეიქმენით ახალი ფაილი სახელწოდებით index.html.
2. გაიღეთ ფაილი და ჩასვით HTML კოდი, რომელიც მე გამოგიგზავნე.

#### *ბ. CSS ფაილი (styles.css)*
1. ახლა შექმენით ახალი ფაილი სახელწოდებით styles.css.
2. ამ ფაილში ჩააკოპირეთ შემდეგი CSS კოდი:

```css
/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body Style */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  color: #333;
}

/* Header Style */
header {
  background-color: #2c3e50;
  color: white;
  padding: 10px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header .logo img {
  width: 150px;
  height: auto;
}

header nav ul {
  display: flex;
  list-style-type: none;
}

header nav ul li {
  margin-left: 20px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
}

header nav ul li a:hover {
  text-decoration: underline;
}

/* Main Banner */
.main-banner {
  background-color: #3498db;
  color: white;
  text-align: center;
  padding: 50px 20px;
}

.main-banner input {
  padding: 10px;
  margin-top: 20px;
  width: 50%;
  font-size: 16px;
  border-radius: 5px;
}

/* Categories Section */
.categories {
  display: flex;
  justify-content: space-around;
  padding: 40px 20px;
}

.categories .category {
  background-color: #ecf0f1;
  padding: 20px;
  width: 30%;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.categories .category h3 {
  font-size: 20px;
  color: #2c3e50;
}

/* Footer Section */
footer {
  text-align: center;
  padding: 20px;
  background-color: #2c3e50;
  color: white;
}

  
