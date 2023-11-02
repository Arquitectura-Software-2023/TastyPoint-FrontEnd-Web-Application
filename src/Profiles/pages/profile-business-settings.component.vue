<template>
  <div class="settings">
    <h1>Settings</h1>
    <div class="profile-settings">
      <h2>Profile</h2>
      <div class="input-group">
        <label for="business-name">Business Name</label>
        <input type="text" id="business-name" />
      </div>
      <div class="input-group">
        <label for="email">E-mail</label>
        <input type="email" id="email" />
      </div>
      <div class="input-group">
        <label for="password">Password</label>
        <input type="password" id="password" />
      </div>
      <div class="input-group">
        <label for="contact-number">Contact Number</label>
        <input type="tel" id="contact-number" />
      </div>
    </div>

    <div class="social-media-settings">
      <h2>Social Media</h2>
      <div class="input-group">
        <label for="facebook-account">Facebook</label>
        <input type="text" id="facebook-account" />
      </div>
      <div class="input-group">
        <label for="instagram-account">Instagram</label>
        <input type="text" id="instagram-account" />
      </div>
      <div class="input-group">
        <label for="twitter-account">Twitter</label>
        <input type="text" id="twitter-account" />
      </div>
    </div>

    <div class="plan-settings">
      <h2>Update Plan</h2>
      <div class="plan-option">
        <div class="plan-details free-plan">
          <h3>Free</h3>
          <i class="pi pi-dollar"></i>0
          <p>We offer you:</p>
          <ul>
            <li>Advertising through your profile</li>
            <li>Publication of up to 10 food dishes</li>
            <li>Publication of up to 20 individual supplies</li>
            <li>Visualization of your product catalog</li>
          </ul>
        </div>
        <div class="plan-details premium-plan">
          <h3>Premium</h3>
          <i class="pi pi-dollar"></i>10
          <p>We offer you:</p>
          <ul>
            <li>Everything in the Free plan</li>
            <li>Unlimited food plate postings</li>
            <li>Unlimited publication of individual supplies</li>
            <li>Access to delivery using the application</li>
            <li>Consumer visibility</li>
            <li>Consumer feedback</li>
          </ul>
          <button class="acquire-button">Acquire</button>
        </div>
      </div>
    </div>

    <div class="save-changes">
      <button class="cancel-button">Cancel</button>
      <button class="save-button">Save Changes</button>
    </div>
  </div>
</template>

<style scoped>
.settings {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin: 20px;
  background-color: #f5f5f5;
  border-radius: 10px;
  padding: 20px;
  color: #3F1602;
}

h1 {
  font-size: 24px;
  margin-bottom: 20px;
  color: #333;
}

h2 {
  font-size: 20px;
  margin-top: 20px;
  color: #3f1602;
}

.input-group {
  display: flex;
  flex-direction: column;
  margin: 10px 0;
}

label {
  font-size: 18px;
  margin-bottom: 5px;
}

input {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 16px;
  width: 100%;
}

.plan-option {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
}

.plan-details {
  padding: 20px;
  border-radius: 10px;
  flex: 1;
  text-align: center;
  margin: 10px;
}

.plan-details h3 {
  font-size: 24px;
  margin-bottom: 10px;
}

.pi {
  font-size: 20px;
  margin-right: 5px;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  margin: 5px 0;
  text-align: left;
}

.acquire-button {
  background-color: #31135E;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
}

.save-changes {
  display: flex;
  justify-content: flex-end;
  margin-top: 20px;
}

.cancel-button {
  background-color: #D9D9D9;
  color: #000000;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  margin-left: 10px;
  cursor: pointer;
}

.save-button {
  background-color: #31135E;
  color: #ffffff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  margin-left: 10px;
  cursor: pointer;
}

.free-plan {
  background-color: #009D9A; /* Color para Free */
}

.premium-plan {
  background-color: #4589FF; /* Color para Premium */
}
</style>
