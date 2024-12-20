# Ex09 Event Registration Web Application
# Date:25\11\2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
# page 1
<style>
.register-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  color: #1e1e1e;
  white-space: nowrap;
  text-align: center;
  margin: 0 auto;
  font: 400 40px Irish Grover, sans-serif;
}

.register-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 932px;
  width: 100%;
  align-items: center;
  padding: 76px 17px 36px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-logo {
  aspect-ratio: 4.95;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.profile-image {
  aspect-ratio: 1.11;
  object-fit: contain;
  object-position: center;
  width: 159px;
  margin-top: 93px;
  max-width: 100%;
}

.register-button {
  position: relative;
  background-color: #23acbb;
  margin-top: 93px;
  width: 232px;
  max-width: 100%;
  padding: 15px 25px;
  border: none;
  color: inherit;
  font: inherit;
  cursor: pointer;
}

.register-button:focus {
  outline: 2px solid #000;
  outline-offset: 2px;
}

.footer-image {
  aspect-ratio: 1.55;
  object-fit: contain;
  object-position: center;
  width: 100%;
  border-radius: 41px;
  margin-top: 111px;
  max-width: 373px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
</style>

<div class="register-container">
  <div class="register-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/4b36f63c0aee8abe601976cac076e862481bb8e0680991b0f5e003a5ae044fa1?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/a819235d6845dd1f2232a633fcd9052dd00ab27720940248dd78fc5d73d3a9c7?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="header-logo"
      alt="Company logo"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/8442853799784b188790e5e24a39457ffe548500e0f81edd9fdb633940e1ad18?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="profile-image"
      alt="User profile illustration"
    />
    <button class="register-button" tabindex="0">REGISTER</button>
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/385affb9cada127e0af4a1cd7cdfa85b32787a47e7a7a0ef1fc5be8d3260b33d?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="footer-image"
      alt="Registration benefits illustration"
    />
  </div>
</div>

# page 2
<style>
.sports-events-container {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  color: rgba(255, 255, 255, 1);
  font-weight: 400;
  text-align: center;
  margin: 0 auto;
}

.sports-content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 932px;
  width: 100%;
  padding: 76px 17px 274px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-image {
  aspect-ratio: 4.95;
  object-fit: contain;
  object-position: center;
  width: 397px;
}

.events-title {
  position: relative;
  align-self: start;
  margin-top: 72px;
  font: 32px Irish Grover, sans-serif;
}

.events-list {
  position: relative;
  align-self: center;
  width: 311px;
  margin: 142px 0 -55px;
  font: 40px Jersey 25, sans-serif;
}
</style>

<div class="sports-events-container">
  <div class="sports-content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/4b36f63c0aee8abe601976cac076e862481bb8e0680991b0f5e003a5ae044fa1?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="background-image"
      alt="Sports day background"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/a819235d6845dd1f2232a633fcd9052dd00ab27720940248dd78fc5d73d3a9c7?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="header-image"
      alt="Sports day header"
    />
    <h1 class="events-title">SPORTS DAY EVENTS</h1>
    <div class="events-list" role="list">
      FOOT BALL
      <br />
      CRICKET
      <br />
      VOLLEY BALL
      <br />
      THROW BALL
      <br />
      100 MTS
      <br />
      200 MTS
      <br />
      400 MTS
    </div>
  </div>
</div>

# page 3
<style>
.registration-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  font: 400 24px Istok Web, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 932px;
  width: 100%;
  align-items: start;
  padding: 68px 15px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-image {
  aspect-ratio: 4.95;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.registration-title {
  position: relative;
  color: #1e1e1e;
  text-align: center;
  margin: 29px 0 0 45px;
  font: 36px Irish Grover, sans-serif;
}

.form-field {
  position: relative;
  background-color: #d9d9d9;
  margin-top: 27px;
  width: 304px;
  max-width: 100%;
  padding: 13px;
}

.submit-button {
  position: relative;
  background-color: #23acbb;
  align-self: end;
  margin-top: 124px;
  color: #1e1e1e;
  text-align: center;
  padding: 15px 25px;
  font: 40px Irish Grover, sans-serif;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <div class="registration-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/4b36f63c0aee8abe601976cac076e862481bb8e0680991b0f5e003a5ae044fa1?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/a819235d6845dd1f2232a633fcd9052dd00ab27720940248dd78fc5d73d3a9c7?apiKey=86c1af1f767541158ea03be1103547ec&"
      class="header-image"
      alt="Event registration header"
    />
    
    <form>
      <h1 class="registration-title">EVENT REGISTRATION</h1>
      
      <label for="name" class="visually-hidden">Name</label>
      <input type="text" id="name" class="form-field" placeholder="NAME" required />
      
      <label for="gender" class="visually-hidden">Gender</label>
      <select id="gender" class="form-field" required>
        <option value="">GENDER</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>
      
      <label for="age" class="visually-hidden">Age</label>
      <input type="number" id="age" class="form-field" placeholder="AGE" required />
      
      <label for="mobile" class="visually-hidden">Mobile Number</label>
      <input type="tel" id="mobile" class="form-field" placeholder="MOBILE NO" required />
      
      <label for="register-no" class="visually-hidden">Register Number</label>
      <input type="text" id="register-no" class="form-field" placeholder="REGISTER NO" required />
      
      <label for="events" class="visually-hidden">Events to Register</label>
      <select id="events" class="form-field" required>
        <option value="">EVENTS TO REGISTER</option>
      </select>
      
      <button type="submit" class="submit-button">REGISTER</button>
    </form>
  </div>
</div>

# page 4
<style>
  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }

  .hero-image {
    aspect-ratio: 0.46;
    object-fit: contain;
    object-position: center;
    width: 100%;
    max-width: 480px;
    margin: 0 auto;
  }
</style>

<img
  loading="lazy"
  src="https://cdn.builder.io/api/v1/image/assets/86c1af1f767541158ea03be1103547ec/4b36f63c0aee8abe601976cac076e862481bb8e0680991b0f5e003a5ae044fa1?apiKey=86c1af1f767541158ea03be1103547ec&"
  alt="Hero section main visual"
  class="hero-image"
/>
```
# OUTPUT:

![image](https://github.com/user-attachments/assets/e7d3a31b-13cd-49e5-a900-be4c431e9d92)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
