# Project Responsive Web Design using Bootstrap
## Date:29-4-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
introduction.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body style="background-color: #e3f2fd;">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">VitalRx Pharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="pharma.html">Pharma</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1 class="display-12"><br>WELCOME TO VITALRX PHARMACY</h1><br>
      <p class="lead">Welcome to VitalRx Pharmacy, your trusted partner in health and wellness.</p>
      <p class="lead">At VitalRx Pharmacy, we understand the importance of accessible and reliable healthcare services. That's why we are dedicated to providing you with personalized care and top-quality products.</p>
      <p class="lead">Our team of pharmacists and healthcare professionals is committed to helping you achieve your health goals. Whether you need prescription medications, over-the-counter remedies, or expert advice, we're here to support you every step of the way.</p>
      <p class="lead">Thank you for choosing VitalRx Pharmacy. We look forward to being your partner in health and wellness, and to helping you lead a healthier, happier life.</p>
      </div>
      <div class="col-md-4"></div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="fixed-bottom bg-dark text-white text-center py-2">
    <p class="mb-0">&copy;//Rohan J(212223040171)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```

pharma.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharma</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-info">
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">VitalRx Pharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="pharma.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Pharma
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12 bg-light py-4">
        <h1 class="text-center">Welcome to VitalRx Pharmacy</h1>
        <div id="vision">
          <h2 class="text-center">Why Choose VitalRx Pharmacy?</h2>
          <ul>
            <li>Wide Coverage: Serving over 1,200 cities and 20,000+ Pin codes, ensuring accessibility for all.</li>
            <li>Fast Delivery: Swift Express Delivery service to get your medications to you when you need them.</li>
            <li>Extensive Range: Offering an extensive catalog of over 1 Lakh medicines to cater to diverse healthcare needs.</li>
            <li>Convenience: Convenient Cash on Delivery option available for hassle-free transactions.</li>
            <li>Special Offers: Exciting offers and discounts to make healthcare more affordable.</li>
            <li>Rewarding Loyalty: Earn cashback with wallet payments, rewarding your loyalty.</li>
            <li>Quality Assurance: Stringent quality checks ensure safety and efficacy of all products.</li>
            <li>Trusted Partner: Trusted by over 10 million satisfied customers who rely on VitalRx Pharmacy for their healthcare needs.</li>
          </ul>
        </div>
        <div id="mission">
          <h2 class="text-center">Our Mission</h2>
          <p>At VitalRx Pharmacy, our mission is simple yet profound: to improve lives by providing safe, effective, and affordable medications that empower individuals to lead healthier and happier lives.</p>
        </div>
        <div id="values">
          <h2 class="text-center">Our Values</h2>
          <ul>
            <li>Quality: Committed to delivering products and services of the highest quality to our customers.</li>
            <li>Integrity: Conducting business with integrity, honesty, and transparency at all times.</li>
            <li>Innovation: Constantly innovating and adapting to meet the evolving needs of our customers and the healthcare industry.</li>
            <li>Customer-Centric: Putting our customers at the heart of everything we do, and striving to exceed their expectations.</li>
            <li>Collaboration: Fostering a culture of teamwork and collaboration to achieve common goals and deliver excellence.</li>
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-2 mt-5">
    <p>&copy; //Rohan J(212223040171)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
```
products.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">VitalRx Pharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="pharma.html">Pharma</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="pharma.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1 class="text-center mb-5">PharmEasy PRODUCTS</h1>
        <div class="card-deck">
          <div class="card">
            <img src="https://pipingrock.com/cdn/shop/products/b-complex-100-mg-60-quick-release-capsules-22150.jpg?height=500&pad_color=fff&v=1709224458&width=500" class="card-img-top" alt="Product 1" HEIGHT="200">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text"> Lindberg B-Complex is a supplement that contains a blend of essential B vitamins. Here’s a concise summary of its uses:
                Energy Production: B vitamins play a crucial role in converting food into energy1.
                Cell Health: They support cell growth, development, and function2.
                Mood and Cognitive Function: B-complex vitamins may help reduce fatigue and boost mood</p>
              <a href="#" class="btn btn-success btn-block">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="https://onemg.gumlet.io/l_watermark_346,w_690,h_700/a_ignore,w_690,h_700,c_pad,q_auto,f_auto/116d26f8123946f9b5cc4bbddca4ce94.jpg" class="card-img-top" alt="Product 2" HEIGHT="200">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Smartical New 1250mg/250IU Tablet:<br>
                Uses:
                Nutritional Deficiencies: Smartical New 1250mg/250IU Tablet is used to treat nutritional deficiencies.
                Bone Health: It helps manage bone loss (osteoporosis) and weak bones (osteomalacia/rickets).
                Hypoparathyroidism: Used to address decreased parathyroid gland activity.
                Muscle Illnesses: It can be beneficial for certain muscle conditions1.</p>
              <a href="#" class="btn btn-success btn-block">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="https://static.oxinis.com/healthmug/image/product/50053-1-1000.webp" class="card-img-top" alt="Product 3" HEIGHT="200">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">
                MB Vite Multivitamin:</br>
                Uses:
                Enhanced immunity: Boosts immune system with essential vitamins and minerals1.
                Boosted energy levels: Helps combat fatigue and improves physical performance1.
                Health risk reduction: Prevents nutritional deficiencies and reduces health complications1.
                Optimal gut health: Supports digestion and absorption of nutrients.
                </p>
              <a href="#" class="btn btn-success btn-block">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-4">
    <p>&copy;//Rohan J(212223040171)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
```
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-success">
    <a class="navbar-brand" href="#">VitalRx Pharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="pharma.html">pharma</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1 class="mb-4">CONTACT US</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">ENTER YOUR NAME:</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">ENTER YOUR EMAIL:</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <button type="submit" class="btn btn-success">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>VitalRx Pharmacy</h2>
        <address>
          <strong>Address:</strong><br>
          Anna Nagar<br>
          chennai-600040<br><br>
          <strong>Email:</strong><br>
          vitalrxpharmacy123@gmail.com<br><br>
          <strong>Phone:</strong><br>
          8428452109
        </address>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy;//Rohan J(212223040171)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


```


## OUTPUT:
![image](https://github.com/rohanjeyachandran/Pharma/assets/169586172/e26efbf1-2a61-4281-b9c0-4cd88d671be0)
![image](https://github.com/rohanjeyachandran/Pharma/assets/169586172/09bc91c3-87a4-449a-af71-819458347755)
![image](https://github.com/rohanjeyachandran/Pharma/assets/169586172/9e820e4f-f5d5-455e-bb4c-7ef05425bda5)
![image](https://github.com/rohanjeyachandran/Pharma/assets/169586172/508f35b9-cabd-4af4-9dcd-5874229e5690)




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
