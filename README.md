# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
homepage

html code
<div class="home-page">
  <img class="logo" src="logo0.svg" />
  <img class="rectangle-385" src="rectangle-3850.svg" />
  <div class="loading">Loading...</div>
  <img class="images-1" src="images-10.png" />
  <div class="rectangle-1630"></div>
  <div class="login">LOGIN</div>
  <div class="rectangle-1631"></div>
  <div class="register">REGISTER</div>
</div>

css code 
.home-page,
.home-page * {
  box-sizing: border-box;
}
.home-page {
  background: linear-gradient(
    131.41deg,
    rgba(0, 0, 0, 0.74) 0%,
    rgba(76, 38, 125, 1) 99.14812445640564%
  );
  opacity: 0.96;
  height: 926px;
  position: relative;
  overflow: hidden;
}
.logo {
  width: 419px;
  height: 57px;
  position: absolute;
  left: 0px;
  top: 0px;
  overflow: visible;
  object-fit: cover;
}
.rectangle-385 {
  width: 600.11px;
  height: 81.71px;
  position: absolute;
  left: 58px;
  top: 916.18px;
  transform: translate(36.92px, -271.18px);
  overflow: visible;
}
.loading {
  color: #ffffff;
  text-align: center;
  font-family: "MontserratAlternates-SemiBold", sans-serif;
  font-size: 28px;
  font-weight: 600;
  position: absolute;
  left: 45px;
  top: 611px;
  width: 320px;
  height: 67px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.images-1 {
  border-radius: 117px;
  width: 257px;
  height: 259px;
  position: absolute;
  left: 77px;
  top: 133px;
  object-fit: cover;
}
.rectangle-1630 {
  background: #ffffff;
  border-radius: 18px;
  width: 292px;
  height: 54px;
  position: absolute;
  left: 73px;
  top: 453px;
}
.login {
  color: #000000;
  text-align: center;
  font-family: "Montserrat-SemiBold", sans-serif;
  font-size: 32px;
  font-weight: 600;
  position: absolute;
  left: 93px;
  top: 465px;
  width: 251px;
  height: 28px;
}
.rectangle-1631 {
  background: #ffffff;
  border-radius: 16px;
  width: 292px;
  height: 53px;
  position: absolute;
  left: 73px;
  top: 540px;
}
.register {
  color: #000000;
  text-align: center;
  font-family: "Montserrat-SemiBold", sans-serif;
  font-size: 32px;
  font-weight: 600;
  position: absolute;
  left: 91px;
  top: 547px;
  width: 243px;
  height: 34px;
}

login page 

html code 
<div class="login-page">
  <div class="ic-baseline-remove-red-eye">
    <img class="vector" src="vector0.svg" />
    <img
      class="ic-baseline-remove-red-eye2"
      src="ic-baseline-remove-red-eye1.svg"
    />
  </div>
  <img
    class="ic-baseline-remove-red-eye3"
    src="ic-baseline-remove-red-eye2.svg"
  />
  <div class="ic-baseline-remove-red-eye4">
    <img
      class="ic-baseline-remove-red-eye5"
      src="ic-baseline-remove-red-eye4.svg"
    />
    <img class="vector2" src="vector1.svg" />
  </div>
  <img class="rectangle-389" src="rectangle-3890.png" />
  <img class="rectangle-384" src="rectangle-3840.svg" />
  <img class="rectangle-383" src="rectangle-3830.svg" />
  <img class="rectangle-388" src="rectangle-3880.svg" />
  <img class="rectangle-385" src="rectangle-3850.svg" />
  <img class="rectangle-387" src="rectangle-3870.svg" />
  <img class="group-141" src="group-1410.svg" />
  <img class="group-149" src="group-1490.svg" />
  <div
    class="_1-foot-ball-2-cricket-3-batminton-4-vollyball-5-throwball-6-100-mts-7-200-mts-8-400-mts"
  >
    1 FOOT BALL
    <br />
    <br />
    2 CRICKET
    <br />
    <br />
    3 BATMINTON
    <br />
    <br />
    4 VOLLYBALL
    <br />
    <br />
    5 THROWBALL
    <br />
    <br />
    6 100 MTS
    <br />
    <br />
    7 200 MTS
    <br />
    <br />
    8 400 MTS
  </div>
  <div class="sports-events-eventsevents">sports events eventsevents</div>
</div>

css code
.login-page,
.login-page * {
  box-sizing: border-box;
}
.login-page {
  background: linear-gradient(
    131.41deg,
    rgba(0, 0, 0, 1) 32.08332061767578%,
    rgba(54, 42, 96, 1) 99.14812445640564%
  );
  height: 926px;
  position: relative;
  overflow: hidden;
}
.ic-baseline-remove-red-eye {
  width: 24px;
  height: 24px;
  position: absolute;
  left: 308px;
  top: 488px;
  overflow: hidden;
}
.vector {
  width: 91.67%;
  height: 62.5%;
  position: absolute;
  right: 4.17%;
  left: 4.17%;
  bottom: 18.75%;
  top: 18.75%;
  overflow: visible;
}
.ic-baseline-remove-red-eye2 {
  width: 100%;
  height: 100%;
  position: absolute;
  right: -4.17%;
  left: 4.17%;
  bottom: 0%;
  top: 0%;
  overflow: visible;
}
.ic-baseline-remove-red-eye3 {
  width: 24px;
  height: 24px;
  position: absolute;
  left: 298px;
  top: 361px;
  overflow: visible;
}
.ic-baseline-remove-red-eye4 {
  width: 24px;
  height: 24px;
  position: absolute;
  left: 310px;
  top: 366px;
  overflow: hidden;
}
.ic-baseline-remove-red-eye5 {
  width: 100%;
  height: 100%;
  position: absolute;
  right: 4.17%;
  left: -4.17%;
  bottom: 33.33%;
  top: -33.33%;
  overflow: visible;
}
.vector2 {
  width: 91.67%;
  height: 62.5%;
  position: absolute;
  right: 4.17%;
  left: 4.17%;
  bottom: 18.75%;
  top: 18.75%;
  overflow: visible;
}
.rectangle-389 {
  background: linear-gradient(
    to left,
    rgba(196, 196, 196, 0.5),
    rgba(196, 196, 196, 0.5)
  );
  width: 648px;
  height: 981px;
  position: absolute;
  left: -164px;
  top: -22px;
  filter: blur(0px);
  mix-blend-mode: multiply;
  object-fit: cover;
}
.rectangle-384 {
  border-radius: 0px;
  width: 560.12px;
  height: 81.71px;
  position: absolute;
  left: -127px;
  top: 246.78px;
  transform: translate(127px, -244.58px);
  overflow: visible;
}
.rectangle-383 {
  border-radius: 0px;
  width: 600.11px;
  height: 81.71px;
  position: absolute;
  left: 43px;
  top: 122.18px;
  transform: translate(38.26px, -122.18px);
  overflow: visible;
}
.rectangle-388 {
  border-radius: 0px;
  width: 239.24px;
  height: 81.71px;
  position: absolute;
  left: -80px;
  top: 568.44px;
  transform: translate(80px, -101.42px);
  overflow: visible;
}
.rectangle-385 {
  width: 600.11px;
  height: 81.71px;
  position: absolute;
  left: 67px;
  top: 987.18px;
  transform: translate(36.92px, -271.18px);
  overflow: visible;
}
.rectangle-387 {
  border-radius: 0px;
  width: 600.11px;
  height: 81.71px;
  position: absolute;
  left: 142px;
  top: 611.18px;
  transform: translate(38.26px, -262.4px);
  overflow: visible;
}
.group-141 {
  height: auto;
  position: absolute;
  left: 0px;
  top: -6px;
  overflow: visible;
}
.group-149 {
  height: auto;
  position: absolute;
  left: -44.92px;
  top: 732.26px;
  transform: translate(44.92px, -12.17px);
  overflow: visible;
}
._1-foot-ball-2-cricket-3-batminton-4-vollyball-5-throwball-6-100-mts-7-200-mts-8-400-mts {
  color: #ffffff;
  text-align: left;
  font-family: "Alata-Regular", sans-serif;
  font-size: 28px;
  font-weight: 400;
  position: absolute;
  left: 58px;
  top: 132px;
  width: 325px;
  height: 562px;
}
.sports-events-eventsevents {
  background: linear-gradient(
    180deg,
    rgba(255, 0, 31, 1) 22.18748778104782%,
    rgba(235, 0, 255, 0) 97.18748927116394%
  );
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  text-align: center;
  font-family: "MontserratAlternates-SemiBold", sans-serif;
  font-size: 28px;
  font-weight: 600;
  position: absolute;
  left: 126px;
  top: 19px;
  width: 218px;
  height: 40px;
}

registration page 

html code 
<div class="homepage">
  <img class="rectangle-389" src="rectangle-3890.png" />
  <img class="rectangle-384" src="rectangle-3840.svg" />
  <img class="rectangle-383" src="rectangle-3830.svg" />
  <img class="rectangle-388" src="rectangle-3880.svg" />
  <img class="rectangle-385" src="rectangle-3850.svg" />
  <img class="rectangle-387" src="rectangle-3870.svg" />
  <div class="rectangle-381"></div>
  <img class="vector" src="vector0.svg" />
  <div class="registration">registration</div>
  <img class="group-150" src="group-1500.svg" />
  <div class="event-registration-form">EVENT REGISTRATION FORM</div>
  <div class="h">h</div>
  <div class="jk">\jk</div>
  <div class="group-130">
    <div class="rectangle-3812"></div>
  </div>
  <div class="group-130">
    <div class="rectangle-3813"></div>
  </div>
  <div class="group-130">
    <div class="rectangle-3814"></div>
  </div>
  <div class="group-130">
    <div class="rectangle-3815"></div>
  </div>
  <div class="group-130">
    <div class="rectangle-3816"></div>
  </div>
  <div class="group-130">
    <div class="rectangle-3817"></div>
  </div>
  <div class="group-130">
    <div class="rectangle-3818"></div>
  </div>
  <div class="group-130">
    <div class="rectangle-3819"></div>
  </div>
  <div class="full-name">full name</div>
  <div class="gender">gender</div>
  <div class="age">Age</div>
  <div class="register-number">register number</div>
  <div class="department">department</div>
  <div class="mobile-number">mobile number</div>
  <div class="email-id">email id</div>
  <div class="events-to-register">events to register</div>
</div>

check in page 

html code 
<div class="check-in">
  <img class="rectangle-389" src="rectangle-3890.png" />
  <img class="rectangle-384" src="rectangle-3840.svg" />
  <img class="rectangle-383" src="rectangle-3830.svg" />
  <img class="rectangle-388" src="rectangle-3880.svg" />
  <img class="rectangle-385" src="rectangle-3850.svg" />
  <img class="rectangle-387" src="rectangle-3870.svg" />
  <div class="frame-1">
    <img class="group-148" src="group-1480.svg" />
    <div class="group-147">
      <img class="group-146" src="group-1460.svg" />
      <div class="scan-qr-to-pay">Scan QR to pay</div>
    </div>
    <div class="pay-using-bank-networking">pay using bank networking</div>
  </div>
  <div class="rectangle-381"></div>
  <img class="vector" src="vector0.svg" />
  <div class="payment">payment</div>
  <img class="group-151" src="group-1510.svg" />
  <div class="pay-reg-fee-rs-50">Pay reg fee Rs.50</div>
</div>

verification

html code 

<div class="verification">
  <div class="ic-baseline-remove-red-eye">
    <img class="vector" src="vector0.svg" />
    <img
      class="ic-baseline-remove-red-eye2"
      src="ic-baseline-remove-red-eye1.svg"
    />
  </div>
  <img
    class="ic-baseline-remove-red-eye3"
    src="ic-baseline-remove-red-eye2.svg"
  />
  <div class="ic-baseline-remove-red-eye4">
    <img
      class="ic-baseline-remove-red-eye5"
      src="ic-baseline-remove-red-eye4.svg"
    />
    <img class="vector2" src="vector1.svg" />
  </div>
  <img class="rectangle-389" src="rectangle-3890.png" />
  <img class="rectangle-1619" src="rectangle-16190.png" />
  <img class="rectangle-384" src="rectangle-3840.svg" />
  <img class="rectangle-383" src="rectangle-3830.svg" />
  <img class="rectangle-388" src="rectangle-3880.svg" />
  <img class="rectangle-385" src="rectangle-3850.svg" />
  <img class="rectangle-387" src="rectangle-3870.svg" />
  <div class="rectangle-381"></div>
  <div class="un-hashed">UnHashed</div>
  <div class="un-hashed2">UnHashed</div>
  <img class="vector3" src="vector2.svg" />
  <div class="rectangle-381"></div>
  <img class="vector4" src="vector3.svg" />
  <div class="payment">payment</div>
  <div class="click-here-to-check-out">Click here to Check-out</div>
  <img class="group-145" src="group-1450.svg" />
  <div class="bi-qr-code">
    <img class="group" src="group0.svg" />
  </div>
  <img class="group-135" src="group-1350.svg" />
  <div class="paid-successfully">Paid Successfully</div>
  <img class="group-152" src="group-1520.svg" />
</div>


```

## OUTPUT:
![alt text](<Screenshot (190).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
