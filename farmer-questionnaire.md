---
layout: default
title: Farmer Questionnaire
---

<style>
  body {
    font-family: Arial, sans-serif;
    margin: 20px;
    padding: 0;
  }

  h1, h3 {
    color: #2c3e50;
  }

  form {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 10px;
    background-color: #f9f9f9;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }

  label {
    font-weight: bold;
    display: block;
    margin-top: 15px;
    color: #34495e;
  }

  input[type="text"],
  input[type="email"],
  input[type="tel"],
  textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
  }

  input[type="radio"],
  input[type="checkbox"] {
    margin-right: 10px;
  }

  textarea {
    resize: vertical;
    height: 100px;
  }

  button {
    background-color: #3498db;
    color: #fff;
    border: none;
    padding: 10px 15px;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    margin-top: 20px;
  }

  button:hover {
    background-color: #2980b9;
  }

  .form-section {
    margin-bottom: 20px;
  }

  .form-section h3 {
    border-bottom: 2px solid #3498db;
    padding-bottom: 5px;
    margin-bottom: 10px;
  }
</style>

<h1>Farmer Questionnaire: Chicken Sales Partnership</h1>
<p>This questionnaire is designed to understand your farming and chicken-rearing needs and explore potential partnership opportunities. Please take a few minutes to fill it out.</p>

<form action="https://naatukodiappservice.azurewebsites.net/api/farmer/submit" method="POST" id="farmerQuestionnaireForm">
  <div class="form-section">
    <h3>Personal and Farm Information</h3>
    <label for="customerId">Customer ID:</label>
    <input type="text" id="customerId" name="customerId" required>

    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="location">Location:</label>
    <input type="text" id="location" name="location" required>

    <label for="contact">Contact Number/Email:</label>
    <input type="text" id="contact" name="contact" required>

    <label for="chickenBreeds">Breeds or types of chickens you raise:</label>
    <input type="text" id="chickenBreeds" name="chickenBreeds">
  </div>

  <div class="form-section">
    <h3>Farming Details</h3>
    <label>What is your chicken-rearing method?</label>
    <input type="radio" name="rearingMethod" value="Free-range"> Free-range<br>
    <input type="radio" name="rearingMethod" value="Farm-based"> Farm-based<br>
    <input type="radio" name="rearingMethod" value="Others"> Others: <input type="text" name="rearingMethodOther"><br>

    <label>How many chickens do you currently have?</label>
    <input type="radio" name="chickenCount" value="0-50"> 0-50<br>
    <input type="radio" name="chickenCount" value="50-100"> 50-100<br>
    <input type="radio" name="chickenCount" value="100-500"> 100-500<br>
    <input type="radio" name="chickenCount" value="More than 500"> More than 500<br>

    <label>On average, how many chickens do you sell in a month?</label>
    <input type="radio" name="monthlySales" value="0-50"> 0-50<br>
    <input type="radio" name="monthlySales" value="50-100"> 50-100<br>
    <input type="radio" name="monthlySales" value="100-500"> 100-500<br>
    <input type="radio" name="monthlySales" value="More than 500"> More than 500<br>
  </div>

  <div class="form-section">
    <h3>Quality and Health</h3>
    <label>What key practices do you follow to maintain chicken health?</label>
    <input type="checkbox" name="healthPractices" value="Disease prevention"> Disease prevention<br>
    <input type="checkbox" name="healthPractices" value="Regular health check-ups"> Regular health check-ups<br>
    <input type="checkbox" name="healthPractices" value="Vaccinations"> Vaccinations<br>
    <input type="checkbox" name="healthPractices" value="Others"> Others: <input type="text" name="healthPracticesOther"><br>

    <label>Do you have access to veterinary services nearby?</label>
    <input type="radio" name="hasVetAccess" value="Yes"> Yes<br>
    <input type="radio" name="hasVetAccess" value="No"> No<br>
  </div>

  <div class="form-section">
    <h3>Sales and Market</h3>
    <label>What are your primary methods for selling chickens?</label>
    <input type="checkbox" name="sellingMethods" value="Farmer markets"> Directly in farmer markets<br>
    <input type="checkbox" name="sellingMethods" value="Wholesalers"> To wholesalers<br>
    <input type="checkbox" name="sellingMethods" value="Retail stores"> To retail stores<br>
    <input type="checkbox" name="sellingMethods" value="Others"> Others: <input type="text" name="sellingMethodsOther"><br>

    <label>Do you have any suggestions or additional comments?</label>
    <textarea name="suggestions"></textarea>
  </div>

  <button type="submit">Submit Questionnaire</button>
</form>