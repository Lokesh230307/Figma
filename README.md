# Ex09 Event Registration Web Application
## Date:14.05.2025

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
Page 1



<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-13-14-1-1">
<img src="images/node-2.png" class="node-2" alt="screenshot-2025-05-14-193915-1" />
<img src="images/download-1-3.png" class="download-1-3" alt="download-1" />
<div class="rectangle-4"></div>
<div class="rectangle-1-5"></div>
<p class="text-6"><span class="text-white">                   LOGIN
</span></p>
<p class="text-7"><span class="text-white">             REGISTER</span></p>
<div class="frame-1-8"></div>
<div class="frame-2-9"></div>
</div>

</body>
</html>


/* Add font files for Inknut Antiqua */
@font-face {
  font-family: 'Inknut Antiqua';
  src: url('fonts/inknut-antiqua.woff2') format('woff2'),
       url('fonts/inknut-antiqua.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-inknut-antiqua: 'Inknut Antiqua', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.download-1-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(56, 102, 255, 1);
}

.rectangle-1-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(57, 70, 255, 1);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: 700;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inknut-antiqua);
  font-weight: 700;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.frame-1-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.frame-2-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.iphone-13-14-1-1 {
@media (max-width: 1440px) {
  .iphone-13-14-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(221, 249, 255, 1);
}

Page 2


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-13-14-2-1">
<img src="images/download-2-2.png" class="download-2-2" alt="download-2" />
<p class="text-3"><span class="text-black">Name</span></p>
<p class="text-4"><span class="text-black">Year</span></p>
<p class="text-5"><span class="text-black">Dept</span></p>
<img src="images/images-2-6.png" class="images-2-6" alt="images-2" />
<p class="text-7"><span class="text-black">Age</span></p>
<p class="text-8"><span class="text-black">Email</span></p>
<p class="text-9"><span class="text-black">Mobile No</span></p>
<p class="text-10"><span class="text-black">    EVENT DAY</span></p>
</div>

</body>
</html>


/* Add font files for Katibeh */
@font-face {
  font-family: 'Katibeh';
  src: url('fonts/katibeh.woff2') format('woff2'),
       url('fonts/katibeh.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-katibeh: 'Katibeh', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.download-2-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4000000059604645;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.images-2-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.699999988079071;
  width: 100%;
  height: auto;
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 60px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.iphone-13-14-2-1 {
@media (max-width: 1440px) {
  .iphone-13-14-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(248, 218, 192, 1);
}

Page 3


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-13-14-3-1">
<p class="text-2"><span class="text-black">  EVENT DAY </span></p>
<p class="text-3"><span class="text-black">~Quiz </span></p>
<p class="text-4"><span class="text-black">~Treasure hunt</span></p>
<p class="text-5"><span class="text-black"> ~Hackathon</span></p>
<p class="text-6"><span class="text-black">~App Development</span></p>
<p class="text-7"><span class="text-black">~Poster Preparation</span></p>
<p class="text-8"><span class="text-black">~Web Development</span></p>
<img src="images/images-1-9.png" class="images-1-9" alt="images-1" />
<img src="images/download-2-1-10.png" class="download-2-1-10" alt="download-2-1" />
</div>

</body>
</html>


/* Add font files for Katibeh */
@font-face {
  font-family: 'Katibeh';
  src: url('fonts/katibeh.woff2') format('woff2'),
       url('fonts/katibeh.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Lateef */
@font-face {
  font-family: 'Lateef';
  src: url('fonts/lateef.woff2') format('woff2'),
       url('fonts/lateef.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-katibeh: 'Katibeh', sans-serif;
  --font-family-lateef: 'Lateef', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 60px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
  font-family: var(--font-family-lateef);
  font-weight: normal;
  font-size: 60px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-katibeh);
  font-weight: normal;
  font-size: 40px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.images-1-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4000000059604645;
  width: 100%;
  height: auto;
}

.download-2-1-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.44999998807907104;
  width: 100%;
  height: auto;
}

.iphone-13-14-3-1 {
@media (max-width: 1440px) {
  .iphone-13-14-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(252, 255, 223, 1);
}

Page 4


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-13-14-4-1">
<img src="images/download-3-2.png" class="download-3-2" alt="download-3" />
</div>

</body>
</html>

:root {
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.download-3-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4399999976158142;
  width: 100%;
  height: auto;
}

.iphone-13-14-4-1 {
@media (max-width: 1440px) {
  .iphone-13-14-4-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-13-14-4-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(224, 242, 253, 1);
}

```

## OUTPUT:
![alt text](<Screenshot 2025-05-14 214832.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
