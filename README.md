# Bootstrap-4.1.3-rtl
---
## ***Note: this version of bootstrap add full rtl support to bootstrap 4.1.3***


> Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery.
## ***As we were trying to change CSS and JS to be RTL we pass some steps***


#### ***Follow these steps to have RTL CSS:***

- First of all we download bootstrap version 4.0.0 from [getbootstrap.com](https://getbootstrap.com)

- Then we get RTL bootstrap version 4.0.0 from [bootstrap.rtlcss.com](http://bootstrap.rtlcss.com),this css file have been created by Mohammad Younes and works well

- There is a CSS RTL generator in [rtlcss.com](http://rtlcss.com) . you can put your not right to lefted styles in one side and get rtl styles in other side , we want to use this generator for all version of bootstrap 
but this generator makes some wrong decisions,to find these, we compare generated css file,line by line with Mohammad Younes created css file,so we find the critical points that are wrong in generator

- Now we know critical wrong decisions and we can use this generator for all version of bootstrap

#### ***Follow these steps to have RTL JS:***

- In Bootstrap.js , just we have to change Dropdown displaying direction


Add bootstrap-rtl.css and bootstrap-rtl.js to your project :

### ***Note: add poper.js before bootstrap-rtl.js***


```html

<!-- Bootstrap 4.x RTL CSS -->

<link rel="stylesheet" href="bootstrap-rtl.css">


<!-- Bootstrap 4.x RTL JS -->

<Script src="bootstrap-rtl.js"></Script>

```


Or load it from CDN:


```html

<!-- Load Bootstrap 4.x RTL CSS from our CDN -->

<link rel="stylesheet" href="//cdn.xxxxx">


<!-- Load Bootstrap 4.x RTL JS from our CDN -->

<Script src="//cdn.xxx"></Script>

```






#### Feature requests, and bug fixes



If you want a feature or a bug fixed, [report it via project's issues tracker](https://github.com/SahraCompany/Bootstrap-4.x-RTL/issues). However, if it's something you can fix yourself, *fork* the project, *do* whatever it takes to resolve it, and finally submit a *pull* request. I will personally thank you, and add your name to the list of contributors.



#### Author


- **Sahra-Soft Company** [http://github.com/SahraCompany](http://github.com/SahraCompany)

  

- **Mohammad Ramezani** [http://github.com/mohammadramezani](http://github.com/mohammadramezani)
 

  
- **Meghdad Ansari** [http://github.com/meghdad0072000](http://github.com/meghdad0072000)

- **Mahnoosh Mahdavi** [http://github.com/mmahdavi2018](http://github.com/mmahdavi2018)

  





#### License
I have no idea what licenses are for exactly. So there is no license control over this bootstrap-rtl project. However bootstrap itself is licensed by Twitter, Inc. under the MIT License (MIT).
