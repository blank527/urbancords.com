

<!DOCTYPE html>
<html>
<head>
  <title>Urban Cords</title>
  <style>
    /* Reset default styles */
    body, h1, h2, h3, p, ul, li {
      margin: 0;
      padding: 0;
    }

    /* Set global styles */
    body {
  	font-family: Arial, sans-serif;
  	line-height: 1.5;
  	background-color: transparent; /* Set the background color to transparent */
  	color: #333;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }

    header {
      background-color: #333;
      padding: 20px;
      color: #fff;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin-left: 20px;
      font-weight: bold;
      font-size: 18px;
      letter-spacing: 1px;
      text-transform: uppercase;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffc107;
    }

    section {
      padding: 40px 0;
    }

    #hero {
      background-color: #555;
      text-align: center;
      color: #fff;
      padding: 60px 0;
    }

    #hero img {
      max-width: 400px;
      margin-bottom: 20px;
      animation: fade-in 1s ease-in-out;
    }

    @keyframes fade-in {
      0% {
        opacity: 0;
        transform: translateY(-50px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }
#hero {
  background-image: url("banner.jpg");
  background-size: cover;
  background-position: center;
  text-align: center;
  color: #fff;
  padding: 60px 0;
}


    #about, #bracelet-collection, #why-choose, #connect {
      background-color: #999;
      text-align: center;
      color: #fff;
      transform: translateY(50px);
      opacity: 0;
      padding: 20px;
      transition: transform 0.5s ease, opacity 0.5s ease;
    }

    #about.show, #bracelet-collection.show, #why-choose.show, #connect.show {
      transform: translateY(0);
      opacity: 1;
    }

    #about p, #bracelet-collection p, #why-choose p, #connect p {
      margin-bottom: 20px;
    }

    #about, #why-choose {
      padding-bottom: 60px;
    }

    #about h2, #bracelet-collection h2, #why-choose h2, #connect h2 {
      margin-bottom: 20px;
      font-size: 28px;
      text-transform: uppercase;
    }

    #hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
      letter-spacing: 2px;
    }

    #hero p {
      font-size: 24px;
      margin-bottom: 40px;
    }

    #bracelet-collection ul {
      list-style-type: none;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: flex-start;
      padding: 0;
    }

    #bracelet-collection li {
      width: 200px;
      height: 200px; /* Adjusted height to accommodate rectangular images */
      background-color: #777;
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 10px;
      font-size: 20px;
      transition: transform 0.3s ease;
    }

    #bracelet-collection li img {
      max-width: 160px; /* Adjusted width to fit within the list item */
      max-height: 280px; /* Adjusted height to fit within the list item */
    }
#bracelet-collection ul li img {
  border: 2px solid #000;
  border-radius: 5px;
  background-color: transparent; /* Set the background color to transparent */
  padding: 0; /* Remove any padding around the image */
  margin: 0; /* Remove any margin around the image */
}

    #bracelet-collection li:hover {
      transform: scale(1.1);
    }

    /* Add the black outline to text fonts */
    h1, h2, h3, p, ul, li {
      text-shadow: 1px 1px 0px #002;
    }

    footer {
      background-color: #333;
      padding: 20px;
      color: #fff;
      text-align: center;
    }

    footer a {
      color: #fff;
      text-decoration: none;
      margin: 0 5px;
    }

    footer a:hover {
      text-decoration: underline;
    }

    .social-icons {
      margin-top: 20px;
    }

    .social-icons img {
      width: 32px;
      height: 32px;
      margin: 0 5px;
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <a href="#">Home</a>
      <a href="#bracelet-collection">Bracelet Collection</a>
      <a href="#why-choose">Why Choose UrbanCords?</a>
      <a href="#connect">Connect</a>
    </nav>
  </header>

  <main>
<section id="hero">
  <div class="container">
    <h1>UrbanCords: Unleash Your Style!</h1>
    <p>Elevate Your Everyday Look with Trendy Paracord Bracelets</p>
  </div>
</section>

<section id="bracelet-collection">
  <div class="container">
    <h2>Our Bracelet Collection</h2>
    <p>Explore our diverse collection of paracord bracelets, designed to suit every taste and occasion.</p>
    <ul>
      <li><img src="para1.jpg" alt="Bracelet 1" onclick="zoomImage(this)" /></li>
      <li><img src="para2.jpg" alt="Bracelet 2" onclick="zoomImage(this)" /></li>
      <li><img src="para3.jpg" alt="Bracelet 3" onclick="zoomImage(this)" /></li>
      <li><img src="para4.jpg" alt="Bracelet 4" onclick="zoomImage(this)" /></li>
      <li><img src="para5.jpg" alt="Bracelet 5" onclick="zoomImage(this)" /></li>

    </ul>
  </div>
</section>

<script>
  function zoomImage(image) {
    // Create a modal element
    const modal = document.createElement("div");
    modal.classList.add("modal");

    // Create an image element inside the modal
    const modalImage = document.createElement("img");
    modalImage.src = image.src;
    modalImage.alt = image.alt;
    modalImage.classList.add("modal-image");

    // Add the image to the modal
    modal.appendChild(modalImage);

    // Add the modal to the body
    document.body.appendChild(modal);

    // Remove the modal when clicked outside the image
    modal.addEventListener("click", function () {
      modal.remove();
    });
  }
</script>

<style>
  /* Other styles... */

  .modal {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.9);
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 9999;
    overflow: hidden;
  }

  .modal-image {
    max-width: 90%;
    max-height: 90%;
    object-fit: contain;
  }
</style>

    <section id="about">
      <div class="container">
        <h2>About UrbanCords</h2>
        <p>At UrbanCords, we specialize in crafting high-quality paracord bracelets that are not only fashionable but also functional. Our bracelets are meticulously 

handcrafted using premium materials to ensure durability and style. Whether you're an outdoor enthusiast, an urban explorer, or simply someone with a taste for unique 

accessories, UrbanCords has the perfect bracelet to complement your lifestyle.</p>
      </div>
    </section>

    <section id="why-choose">
      <div class="container">
        <h2>Why Choose UrbanCords?</h2>
        <p>Superior Quality: Our paracord bracelets are made with the utmost attention to detail and craftsmanship, using premium materials that ensure durability and 

long-lasting wear.</p>
        <p>Style & Versatility: UrbanCords offers a wide variety of designs, allowing you to express your unique style effortlessly. Our bracelets seamlessly 

transition from outdoor adventures to urban settings, making them versatile accessories for any occasion.</p>
        <p>Functional & Practical: Beyond their fashionable appeal, our bracelets are woven with authentic paracord, offering you a practical and reliable tool in 

emergency situations. Unravel the cord to use it for various survival purposes.</p>
        <p>Exceptional Customer Service: At UrbanCords, we are dedicated to providing the best customer experience. We strive to exceed your expectations by offering 

prompt support and ensuring your satisfaction with every purchase.</p>
      </div>
    </section>

    <section id="connect">
      <div class="container">
        <h2>Connect with UrbanCords</h2>
        <p>Stay up to date with the latest trends, promotions, and new releases by following us on social media. Visit our website to browse our complete collection 

and place your order today!</p>
        <div class="social-icons">
          <a href="#"><img src="facebook-icon.png" alt="Facebook"></a>
          <a href="#"><img src="twitter-icon.png" alt="Twitter"></a>
          <a href="#"><img src="instagram-icon.png" alt="Instagram"></a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>&copy; 2023 Urban Cords. All rights reserved.</p>
      <p>Email: info@urbancords.com | Phone: 123-456-7890</p>
  </footer>

  <script>
    // Intersection Observer API to trigger animations
    const sections = document.querySelectorAll('section');

    const options = {
      root: null,
      threshold: 0.2,
      rootMargin: '-100px',
    };

    const animateSections = (entries, observer) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('show');
        }
      });
    };

    const observer = new IntersectionObserver(animateSections, options);

    sections.forEach((section) => {
      observer.observe(section);
    });
  </script>
</body>
</html>
