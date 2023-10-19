<div class="contact-area py-120">
  <div class="container">
    <div class="contact-wrapper">
      <div class="row">
        <div class="col-lg-7 align-self-center">
          <div class="contact-form">
            <div class="contact-form-header">
              <h2>Get In Touch</h2>
              <p>
                It is a long established fact that a reader will be distracted
                by the readable content of a page when looking at its layout.
              </p>
            </div>
            <form
              method="post"
              action="/eduhub/assets/php/contact.php"
              id="contact-form"
            >
              <div class="row">
                <div class="col-md-6">
                  <div class="form-group">
                    <input
                      type="text"
                      class="form-control"
                      name="name"
                      placeholder="Your Name"
                      required
                    />
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="form-group">
                    <input
                      type="email"
                      class="form-control"
                      name="email"
                      placeholder="Your Email"
                      required
                    />
                  </div>
                </div>
              </div>
              <div class="form-group">
                <input
                  type="text"
                  class="form-control"
                  name="subject"
                  placeholder="Your Subject"
                  required
                />
              </div>
              <div class="form-group">
                <textarea
                  name="message"
                  cols="30"
                  rows="5"
                  class="form-control"
                  placeholder="Write Your Message"
                />
              </div>
              <button type="submit" class="theme-btn">
                <i class="far fa-paper-plane" /> Send Message</button
              >
              <div class="col-md-12 mt-3">
                <div class="form-messege text-success" />
              </div>
            </form>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="contact-content">
            <div class="contact-info">
              <div class="contact-info-icon contact-info-icon-1">
                <i class="far fa-map-marker-alt" />
              </div>
              <div class="contact-info-content">
                <h5>Office Address</h5>
                <p>Canberra, Australia</p>
              </div>
            </div>
            <div class="contact-info">
              <div class="contact-info-icon contact-info-icon-2">
                <i class="far fa-phone" />
              </div>
              <div class="contact-info-content">
                <h5>Call Us</h5>
                <p>+2 123 4565 789</p>
              </div>
            </div>
            <div class="contact-info">
              <div class="contact-info-icon contact-info-icon-3">
                <i class="far fa-envelope" />
              </div>
              <div class="contact-info-content">
                <h5>Email Us</h5>
                <p>info@example.com</p>
              </div>
            </div>
            <div class="contact-info">
              <div class="contact-info-icon contact-info-icon-4">
                <i class="far fa-clock" />
              </div>
              <div class="contact-info-content">
                <h5>Office Open</h5>
                <p>Mon - Fri (08AM - 5PMß)</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
