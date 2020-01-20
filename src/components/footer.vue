<template>
    <div class="footer">
        <div class="container">

            <div class="bottom">
            <div class="row">
                <div class="col-lg-4 col-md-6 col-sm-12"><img src="../assets/logo.png">
                    <p>The Entertainment Oxygen is a resource network for entertainment professionals worldwide to
                        showcase creative talents, socially connect, and collaborate using EO chat and more.</p>
                    <p>Email: <a href="mailto:">info@entertainmentoxygen.com</a></p>
                    <!--<p>Tel: <a href="tel:"></a></p>-->
                </div>
                <div class="col-lg-2 col-md-6 col-sm-12">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="blog.html">Blogs & Newsletters</a></li>
                        <li><a href="eo-stories.html">EO Stories</a></li>
                        <li><a href="gallery.html">Gallery</a></li>
                    </ul>
                </div>

                <div class="col-lg-3 col-md-6 col-sm-12">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="faq.html">FAQ's</a></li>
                        <li><a href="termsandconditions.html">Terms & conditions</a></li>
                        <li><a href="contact-us.html">Contact Us</a></li>
                    </ul>
                </div>
                <div class="col-lg-3 col-md-6 col-sm-12">
                    <h4>Get In Touch</h4>
                    <p>Enter your email and we'll send you more information.</p>
                    <form id="eo-form-newsletter" method="POST">
                        <input type="email" placeholder="Your Email" name="email" required>
                        <button type="submit">Subscribe</button>
                    </form>
                </div>
            </div>
           
            
</div>
        </div>

        
    </div>








</template>

<style>
img{
    max-width: 100%;
}
.footer {
  background: #0e3b5a;
  padding: 20px 0;
}
.bottom img {
    margin: 0 0 30px;
}
.bottom p {
  font-size: 13px;
  color: #c6d6f8;
  margin: 0 0 15px;
  line-height: 20px;
}
.bottom h4 {
  color: #ffffff;
  font-size: 17px;
  font-weight: 600;
  text-align: left;
  margin: 25px 0 50px;
}
.bottom p a {
    font-size: 13px;
    color: #c6d6f8;
    margin: 0 15px 10px;
    display: inline-block;
}
.bottom ul{
    padding: 0;
}
.bottom ul li {
  margin: 0 0 15px;
  list-style-type: none;
}
.bottom ul li a {
  font-size: 13px;
  color: #c6d6f8;
}
.bottom input[type="email"] {
  background: transparent;
  border: 1px solid #5980e7;
  border-radius: 0 15px 15px 15px;
  padding: 5px 10px;
  margin: 0 0 15px;
  color: #fff;
  font-size: 14px;
}
.bottom button {
  border: 1px solid #5980e7;
  border-radius: 0 15px 15px 15px;
  padding: 10px 15px;
  margin: 0 0 15px;
  background: #f54726;
  color: #fff;
  font-size: 11px;
}
</style>