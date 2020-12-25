---
layout: post
title: Test markdown
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge:
- star
- fork
- follow
tags: []
comments: false

---
You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:
<style> table, th, td { border: 1px solid black;}</style>

| Nomor | Berikut number | Sebelum number | TOTAL |
| 1. |   Two  |    Five  |      7  |
| 2. | Eleven | Nine     | 20 |
| 3. | Eight  | Six      |14 |
| 4. | Three  | One      | 4 |

How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

Here's a code chunk:

    var foo = function(x) {
      return(x + 5);
    }
    foo(3)

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes

You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

<hr>

<style>

table, th, td { border: 10px solid black;margin-left: auto;margin-right: auto;

}

</style>

<h1>The table element</h1>

<table>

<tr>

    <th>Month</th>
    
    <th>Savings</th>

</tr>

<tr>

    <td>January</td>
    
    <td>$100</td>

</tr>

<tr>

    <td>February</td>
    
    <td>$80</td>

</tr>

</table>

<head>   <meta charset="utf-8">   <title>Bening Room</title>  <meta name="viewport" content="width=device-width, initial-scale=1"> <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css"> <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script> <!-- Demo styles -->   <style>     html,     body {       position: relative;       height: 50%;     }      body {       background: #eee;       font-family: Helvetica Neue, Helvetica, Arial, sans-serif;       font-size: 14px;       color: #000;       margin: 0;       padding: 0;     }      .swiper-container {       width: 320px;       height: 240px;     }      .swiper-slide {       text-align: center;       font-size: 18px;       background: #fff;        /* Center slide text vertically */       display: -webkit-box;       display: -ms-flexbox;       display: -webkit-flex;       display: flex;       -webkit-box-pack: center;       -ms-flex-pack: center;       -webkit-justify-content: center;       justify-content: center;       -webkit-box-align: center;       -ms-flex-align: center;       -webkit-align-items: center;       align-items: center;     }   </style> </head> <body> <!-- Swiper -->   <div class="swiper-container">     <div class="swiper-wrapper">      <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/s1.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/s2.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/s3.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/s4.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/s5.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/s6.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k1.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k13.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k3.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k4.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k5.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k6.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k7.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k8.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k9.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k10.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k11.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/k12.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m1.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m2.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m3.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m4.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m5.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m6.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m7.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m8.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m9.jpg"></div>       <div class="swiper-slide"><img src="https://raw.githubusercontent.com/ariefbuddies/bening-out/master/uploads/m10.jpg"></div> 	  </div> </div>    <!-- Add Pagination -->     <div class="swiper-pagination"></div>

<!-- Swiper JS -->  <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>    <!-- Initialize Swiper -->   <script>     var swiper = new Swiper('.swiper-container', {       spaceBetween: 60,       centeredSlides: true,       autoplay: {         delay: 2000,         disableOnInteraction: true,       },     }); 	</script> </body>