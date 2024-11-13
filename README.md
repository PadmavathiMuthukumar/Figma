# Ex09 Event Registration Web Application
## Date: 13-11-2024

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
## Frame 1:
```
<div style="width: 220px; height: 410px; position: relative; background: white">
  <img style="width: 220px; height: 410px; left: 0px; top: 0px; position: absolute; opacity: 0.90; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border-radius: 10px" src="https://via.placeholder.com/220x410" />
  <div style="width: 59px; height: 55px; padding-top: 13.75px; padding-bottom: 6.01px; padding-left: 8.71px; padding-right: 8.71px; left: 81px; top: 108px; position: absolute; background: #D4D4D4; border-radius: 100px; overflow: hidden; justify-content: center; align-items: center; display: inline-flex">
    <div style="width: 41.57px; height: 35.24px; background: black"></div>
  </div>
  <div style="left: 23px; top: 72px; position: absolute; color: #DB161D; font-size: 20px; font-family: Jacques Francois Shadow; font-weight: 400; word-wrap: break-word">Sports Day Events</div>
  <div style="width: 100px; height: 30px; left: 60px; top: 183px; position: absolute; background: #F9F9F9; border-radius: 8px; overflow: hidden; border: 1px #C6C6C6 solid; justify-content: center; align-items: center; display: inline-flex">
    <div style="padding-left: 12px; padding-right: 12px; padding-top: 6px; padding-bottom: 6px; background: rgba(71, 71, 71, 0.08); justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="text-align: center; color: #474747; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Username</div>
    </div>
  </div>
  <div style="width: 100px; height: 30px; left: 60px; top: 233px; position: absolute; background: #F9F9F9; border-radius: 8px; overflow: hidden; border: 1px #C6C6C6 solid; justify-content: center; align-items: center; display: inline-flex">
    <div style="padding-left: 12px; padding-right: 12px; padding-top: 6px; padding-bottom: 6px; background: rgba(71, 71, 71, 0.08); justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="text-align: center; color: #474747; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Password</div>
    </div>
  </div>
  <div style="width: 60px; height: 30px; left: 81px; top: 283px; position: absolute; background: #4A4458; border-radius: 100px; overflow: hidden; flex-direction: column; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; flex: 1 1 0; padding-left: 24px; padding-right: 24px; padding-top: 10px; padding-bottom: 10px; background: rgba(232, 222, 248, 0.12); justify-content: center; align-items: center; gap: 8px; display: inline-flex">
      <div style="text-align: center; color: #E8DEF8; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Login</div>
    </div>
  </div>
  <img style="width: 200px; height: 30.08px; left: 10px; top: 18px; position: absolute" src="https://via.placeholder.com/200x30" />
</div>
```
## Frame 2:
```
<div style="width: 220px; height: 414px; position: relative; background: white">
  <div style="width: 220px; height: 411px; left: 0px; top: 3px; position: absolute; background: white">
    <img style="width: 220px; height: 410px; left: 0px; top: 1px; position: absolute; border-radius: 10px" src="https://via.placeholder.com/220x410" />
    <div style="left: 72px; top: 114px; position: absolute; color: #2C09F6; font-size: 16px; font-family: Inter; font-weight: 600; line-height: 22.40px; word-wrap: break-word">Tennis</div>
    <div style="width: 202px; height: 50px; left: 9px; top: 24px; position: absolute; text-align: center; color: #80058C; font-size: 24px; font-family: Roboto; font-weight: 400; line-height: 32px; word-wrap: break-word">Sports Day <br/>Registration</div>
    <div style="left: 72px; top: 159px; position: absolute; color: #0445E9; font-size: 16px; font-family: Inter; font-weight: 600; line-height: 22.40px; word-wrap: break-word">Foot Ball</div>
    <div style="left: 72px; top: 212px; position: absolute; color: #0942D4; font-size: 16px; font-family: Inter; font-weight: 600; line-height: 22.40px; word-wrap: break-word">Volley Ball</div>
    <div style="left: 72px; top: 257px; position: absolute; color: #0445E9; font-size: 16px; font-family: Inter; font-weight: 600; line-height: 22.40px; word-wrap: break-word">Cricket</div>
  </div>
</div>
```
## Frame 3:
```
<div style="width: 220px; height: 410px; position: relative; background: white">
  <img style="width: 220px; height: 410px; left: 0px; top: 0px; position: absolute; border-radius: 10px" src="https://via.placeholder.com/220x410" />
  <div style="left: 45px; top: 40px; position: absolute; text-align: center; color: black; font-size: 24px; font-family: Inter; font-weight: 600; line-height: 28.80px; word-wrap: break-word">Information</div>
  <div style="width: 100px; height: 20px; left: 60px; top: 98px; position: absolute; background: #FDF7FF; border-radius: 8px; overflow: hidden; border: 1px #7D7983 solid; justify-content: center; align-items: center; display: inline-flex">
    <div style="padding-left: 12px; padding-right: 12px; padding-top: 6px; padding-bottom: 6px; background: rgba(69, 65, 74, 0.08); justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="text-align: center; color: #45414A; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Name</div>
    </div>
  </div>
  <div style="width: 100px; height: 20px; left: 60px; top: 138px; position: absolute; background: #FEF7FF; border-radius: 8px; overflow: hidden; border: 1px #CAC4D0 solid; justify-content: center; align-items: center; display: inline-flex">
    <div style="padding-left: 12px; padding-right: 12px; padding-top: 6px; padding-bottom: 6px; background: rgba(73, 69, 79, 0.08); justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="text-align: center; color: #49454F; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Dept</div>
    </div>
  </div>
  <div style="width: 100px; height: 20px; left: 60px; top: 176px; position: absolute; background: #FEF7FF; border-radius: 8px; overflow: hidden; border: 1px #CAC4D0 solid; justify-content: center; align-items: center; display: inline-flex">
    <div style="padding-left: 12px; padding-right: 12px; padding-top: 6px; padding-bottom: 6px; background: rgba(73, 69, 79, 0.08); justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="text-align: center; color: #49454F; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Year of Study</div>
    </div>
  </div>
  <div style="left: 19px; top: 218px; position: absolute; text-align: center; color: black; font-size: 14px; font-family: Roboto; font-weight: 600; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">If Team:</div>
  <div style="width: 100px; height: 20px; left: 60px; top: 244px; position: absolute; background: #FEF7FF; border-radius: 8px; overflow: hidden; border: 1px #CAC4D0 solid; justify-content: center; align-items: center; display: inline-flex">
    <div style="padding-left: 12px; padding-right: 12px; padding-top: 6px; padding-bottom: 6px; background: rgba(73, 69, 79, 0.08); justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="text-align: center; color: #49454F; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Team Name</div>
    </div>
  </div>
  <div style="width: 120px; height: 20px; left: 55px; top: 277px; position: absolute; background: #FEF7FF; border-radius: 8px; overflow: hidden; border: 1px #CAC4D0 solid; justify-content: center; align-items: center; display: inline-flex">
    <div style="padding-left: 12px; padding-right: 12px; padding-top: 6px; padding-bottom: 6px; background: rgba(73, 69, 79, 0.08); justify-content: center; align-items: center; gap: 8px; display: flex">
      <div style="text-align: center; color: #49454F; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">No. of Teammates</div>
    </div>
  </div>
  <div style="width: 100px; height: 30px; left: 60px; top: 336px; position: absolute; background: #FFA79B; border-radius: 100px; overflow: hidden; flex-direction: column; justify-content: center; align-items: center; gap: 8px; display: inline-flex">
    <div style="align-self: stretch; flex: 1 1 0; padding-left: 24px; padding-right: 24px; padding-top: 10px; padding-bottom: 10px; background: rgba(86, 30, 24, 0.12); justify-content: center; align-items: center; gap: 8px; display: inline-flex">
      <div style="text-align: center; color: #561E18; font-size: 14px; font-family: Roboto; font-weight: 500; line-height: 20px; letter-spacing: 0.10px; word-wrap: break-word">Finalize</div>
    </div>
  </div>
</div>
```
## Frame 4:
```
<div style="width: 225px; height: 409px; position: relative; background: white">
  <div style="width: 175px; height: 20px; left: 20px; top: 186px; position: absolute; text-align: center; color: #83075C; font-size: 11px; font-family: Roboto; font-weight: 500; line-height: 16px; letter-spacing: 0.50px; word-wrap: break-word">Thank you for registering! We’re excited to have you with us!</div>
  <img style="width: 200px; height: 30.08px; left: 6px; top: 18px; position: absolute" src="https://via.placeholder.com/200x30" />
  <div style="left: 17px; top: 95px; position: absolute; color: #C91252; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 500; line-height: 32px; word-wrap: break-word">Successfully <br/>Registered !!</div>
</div>
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/63d2fb43-4797-4662-b6d6-55051260d441)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
