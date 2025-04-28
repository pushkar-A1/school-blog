<!-- booking.html -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Book a Tour | Backroad</title>
    <link rel="stylesheet" href="../css/booking.css" />
    <link rel="stylesheet" href="../css/booking.css" />
  </head>
  <body>
    <!-- Navbar (Optional: copy your navbar code here if needed) -->

    <section class="section">
      <div class="section-title">
        <h2>Book Your <span>Tour</span></h2>
      </div>

      <div class="section-center booking-form-container">
        <form id="bookingForm" onsubmit="return validateBookingForm()" class="form">
          <div class="form-row">
            <label for="name">Name</label>
            <input type="text" id="name" placeholder="Your Name" required />
          </div>
          <div class="form-row">
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Your Email" required />
          </div>
          <div class="form-row">
            <label for="destination">Destination</label>
            <input type="text" id="destination" placeholder="Enter Destination" required />
          </div>
          <div class="form-row">
            <label for="date">Date</label>
            <input type="date" id="date" required />
          </div>
          <div class="form-row">
            <label for="people">No. of People</label>
            <input type="number" id="people" placeholder="1 or more" min="1" required />
          </div>
          <div class="form-row">
            <button type="submit" class="btn">Book Now</button>
          </div>
        </form>
      </div>
    </section>

    <!-- Footer (optional) -->

    <script src="../js/booking.js"></script>
  </body>
</html>
