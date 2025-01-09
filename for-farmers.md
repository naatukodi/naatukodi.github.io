---
layout: default
title: For Farmers
---

# For Farmers

## Empowering Farmers
We provide farmers with high-quality chickens and empower them with scientific methods, training, and veterinary support to ensure success.

## Our Offerings
- **Chickens**: Access to healthy, robust chickens.
- **Training**: Workshops on scientific farming methods.
- **Vet Support**: Expert veterinary assistance to ensure the health of the flock.
- **Feed Solutions**: Affordable, sustainable feed derived from BSF larvae.

# FAQ for Farmers

## Personal and Farm Information
**What basic information should I provide about my farm?**
- Name
- Location
- Contact Number/Email
- Breeds or types of chickens raised

**Why is location information important?**
- It helps determine local market opportunities and access to veterinary services.

---

## Farming Details
**What chicken-rearing methods are there?**
- **Free-range**: Chickens are allowed to roam outdoors.
- **Farm-based**: Chickens are reared in enclosed environments.
- **Others**: Specify any unique methods you follow.

**How many chickens should I rear to start?**
- 0-50: For small-scale, personal farming.
- 50-100: Moderate-scale farming.
- 100-500 or More: Commercial-scale farming.

**What feed materials are suitable for chickens?**
- **Commercial feed**: Balanced feed with essential nutrients.
- **Grains**: Wheat, millet, and corn.
- **Pulses**: Protein-rich feed like lentils.
- **Others**: Any additional locally available feed.

---

## Quality and Health
**What practices should I follow to maintain chicken health?**
- Disease prevention (hygiene and biosecurity measures).
- Regular health check-ups.
- Timely vaccinations.

**Do I need access to veterinary services?**
- Yes, having veterinary support ensures quick response to health issues.

---

## Sales and Market
**How can I sell my chickens?**
- Connect with GSR
- Direct sales in farmer markets.
- Selling to wholesalers.
- Supplying to retail stores.

**Are there specific weight or size requirements for market chickens?**
- 1-2 kg chickens.
- 2-3 kg chickens.
- Others: Specify any market-specific requirements.

---

## Support and Challenges
**What challenges might I face in chicken farming?**
- Feeding methods and costs.
- Disease outbreaks.
- Market access or fair pricing.

**What support can I seek?**
- Advice on feeding methods.
- Disease prevention strategies.
- Marketing and sales assistance.

---

## Feedback
**Are there new methods or technologies to explore?**
- Yes, adopting modern tools and techniques can improve productivity.

**Do you have suggestions for improving farming operations?**
- Provide specific feedback or comments to improve collaboration and support.

---

<style>
  .registration-form {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    font-family: Arial, sans-serif;
  }

  .registration-form h3 {
    margin-top: 20px;
    color: #2c3e50;
  }

  .registration-form label {
    font-weight: bold;
    display: block;
    margin-top: 10px;
    color: #34495e;
  }

  .registration-form input[type="text"],
  .registration-form input[type="email"],
  .registration-form input[type="number"],
  .registration-form textarea,
  .registration-form select {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
  }

  .registration-form input[type="radio"],
  .registration-form input[type="checkbox"] {
    margin-right: 10px;
  }

  .registration-form textarea {
    resize: vertical;
    height: 80px;
  }

  .registration-form button {
    background-color: #3498db;
    color: #fff;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
  }

  .registration-form button:hover {
    background-color: #2980b9;
  }

  .form-section {
    margin-bottom: 20px;
  }
</style>

<div class="registration-form">
  <form action="https://formspree.io/f/mwppaebe" method="POST">
    <h3>Personal and Farm Information</h3>
    <div class="form-section">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="location">Location:</label>
      <input type="text" id="location" name="location" required>

      <label for="contact">Contact Number/Email:</label>
      <input type="text" id="contact" name="contact" required>

      <label for="breeds">Breeds or Types of Chickens:</label>
      <input type="text" id="breeds" name="breeds">
    </div>

    <h3>Farming Details</h3>
    <div class="form-section">
      <label for="method">Chicken Rearing Method:</label><input type="radio" id="free-range" name="method" value="Free-range">
      <label for="free-range">Free-range</label>
      <input type="radio" id="farm-based" name="method" value="Farm-based">
      <label for="farm-based">Farm-based</label>
      <input type="radio" id="others-method" name="method" value="Others">
      <label for="others-method">Others</label>
      <input type="text" id="method-details" name="method-details" placeholder="Specify if others">

      <label for="chicken-count">How many chickens do you currently have?</label>
      <select id="chicken-count" name="chicken-count">
        <option value="0-50">0-50</option>
        <option value="50-100">50-100</option>
        <option value="100-500">100-500</option>
        <option value="more-than-500">More than 500</option>
      </select>
    </div>

    <h3>Quality and Health</h3>
    <div class="form-section">
      <label>What key practices do you follow for chicken health?</label>
      <input type="checkbox" id="disease-prevention" name="health-practices" value="Disease prevention">
      <label for="disease-prevention">Disease prevention</label>
      <input type="checkbox" id="check-ups" name="health-practices" value="Regular health check-ups">
      <label for="check-ups">Regular health check-ups</label>
      <input type="checkbox" id="vaccinations" name="health-practices" value="Vaccinations">
      <label for="vaccinations">Vaccinations</label>
      <input type="checkbox" id="others-health" name="health-practices" value="Others">
      <label for="others-health">Others</label>
      <input type="text" id="health-details" name="health-details" placeholder="Specify if others">
    </div>

    <h3>Sales and Market</h3>
    <div class="form-section">
      <label>What are your primary methods for selling chickens?</label>
      <input type="checkbox" id="markets" name="sales-method" value="Directly in farmer markets">
      <label for="markets">Directly in farmer markets</label>
      <input type="checkbox" id="wholesalers" name="sales-method" value="To wholesalers">
      <label for="wholesalers">To wholesalers</label>
      <input type="checkbox" id="retail" name="sales-method" value="To retail stores">
      <label for="retail">To retail stores</label>
      <input type="checkbox" id="others-sales" name="sales-method" value="Others">
      <label for="others-sales">Others</label>
      <input type="text" id="sales-details" name="sales-details" placeholder="Specify if others">
    </div>

    <h3>Support and Challenges</h3>
    <div class="form-section">
      <label for="challenges">Are you facing any challenges in chicken farming?</label>
      <textarea id="challenges" name="challenges" placeholder="Specify challenges"></textarea>
    </div>

    <button type="submit">Submit</button>
  </form>
</div>



[Contact Us to Learn More](contact.html)