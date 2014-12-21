More than 100+ Pure CSS Image Hover Effects Which is very useful for your projects. By using this CSS You Will be able to add Variety of Image hover effects.


<h3>Effects You will get:</h3>
<ul>
<li>Zoom In & Zoom Out</li>
<li>Rotate Right & Left</li>
<li>Rotate & Scale</li>
<li>Rotate X & Rotate Y</li>
<li>Image Opacity</li>
<li>Layer Hover</li>
<li>Cubic Transition</li>
<li>and Many More</li>
</ul>


<h2>HTML Structure:</h2>


```
<div class="ImageWrapper">
            <img src="Your_Image.jpg" alt="">
            <div class="ImageOverlayH"></div>
            <div class="Buttons StyleH">
                <span class="white-rounded"><a href=""><i class="fa fa-search"></i></a>
                </span>
                <span class="white-rounded"><a href=""><i class="fa fa-link"></i></a>
                </span>
            </div>
        </div>
```


<h2>CSS Structure:</h2>

```
.ImageWrapper .ImageOverlayH {
        background: none repeat scroll 0 0 rgba(0, 0, 0, 0.5);
        bottom: 0;
        display: block;
        height: 100%;
        left: 0;
        opacity: 0;
        position: absolute;
        right: 0;
        top: 0;
        transition: all 0.2s ease 0s;
        width: 100%;
    }
    .ImageWrapper:hover .ImageOverlayH {
        opacity: 1;
    }

    .ImageWrapper .StyleH {
        visibility: hidden;
        margin: 0;
        opacity: 0;
        position: absolute;
        text-align: center;
        width: 100%;
        top: 50%;
        margin-top: -20px;
    }
    .ImageWrapper:hover .StyleH {
        opacity: 1;
        visibility: visible;
    }
```        

Using this css hover effects in your pojects is very easy. Before adding this, We Recommend you to add FontAwesome, To grab this pligin you just need go <a href="http://fortawesome.github.io/Font-Awesome/">here</a> and follow the structure to use this plugin . After that, to use this css file insert this code before tag </head> in your index.html .

```
<link rel="stylesheet" href="css/sinister.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
```


<h2>How to Use</h2>

<h3>First Step</h3>
First of all, add a image in your projects file, as bellow.

```
<div class="ImageWrapper">
        <img src="YourImage.jpg" alt="">
    </div>
```

<h3>Second Step : Add Overlay Tag</h3>

```
 <div class="ImageWrapper">
        <img src="YourImage.jpg" alt="">
        <div class="ImageOverlayH"></div>
    </div>
```

<h3>Thired Step : Add Hover Style & Buttons</h3>

```
<div class="ImageWrapper">
        <img src="YourImage.jpg" alt="">
        <div class="ImageOverlayH"></div>
        <div class="StyleH">
            <span class="WhiteRounded"><a href=""><i class="fa fa-search"></i></a>
            </span>
            <span class="WhiteRounded"><a href=""><i class="fa fa-link"></i></a>
            </span>
        </div>
    </div>
```

<h3>Fourth Step : Add Hover Style & Buttons</h3> 

```
<div class="ImageWrapper">
        <img src="YourImage.jpg" alt="">
        <div class="ImageOverlayH"></div>
        <div class="StyleH">
            <span class="WhiteRounded"><a href=""><i class="fa fa-search"></i></a>
            </span>
            <span class="WhiteRounded"><a href=""><i class="fa fa-link"></i></a>
            </span>
        </div>
    </div>
```


<h3>Last is not last : After doins as above, Your Code Shoud Be Like This:</h3>

```
<div class="ImageWrapper">
        <img src="YourImage.jpg" alt="">
        <div class="ImageOverlayH"></div>
        <div class="StyleH">
            <span class="WhiteRounded"><a href=""><i class="fa fa-search"></i></a>
            </span>
            <span class="WhiteRounded"><a href=""><i class="fa fa-link"></i></a>
            </span>
        </div>
    </div>
```

