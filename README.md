# shopping-cart-items-number
Showing users how many items are in their shopping cart helps encourage conversions.

## Tutorial
For detailed instruction's, view Solodev's [How to Show the Total Number of Items in Customer Shopping Carts](https://www.solodev.com/blog/web-design/how-to-show-the-total-number-of-items-in-customer-shopping-carts.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/rpuLfkg5/).

## HTML
The tutorial contains the following basic HTML markup.

```
<div class="header navigation">
      <div class="col-xl-3 col-lg-2 col-sm-4 col-5">
        <a href="/">
          <img alt="Logo" class="img-fluid py-3 logo" src="https://raw.githubusercontent.com/solodev/shopping-cart-items-number/master/images/lunar-xp-logo.png" aria-role="logo">
        </a>
      </div>
      <div class="col-xl-9 col-lg-10 col-sm-8 col-7">
      
        <ul class="navbar-nav flex-row justify-content-end flex-wrap align-items-center mr-lg-4 mr-xl-0">
         
          <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
            <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/locations/"><strong>Locations</strong></a>
           
          </li>          
          <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
            <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/products/"><strong>Products</strong></a>
          
          </li>
          <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
            <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/shop/"><strong>Shop</strong></a>
          </li>
          <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
            <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/contact/"><strong>Contact</strong></a>
          </li>
          <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
            <div id="cart" class="d-none">
            </div>
            <a href="#" class="cart position-relative d-inline-flex" aria-label="View your shopping cart">
              <i class="fas fa fa-shopping-cart fa-lg"></i>
              <span class="cart-basket d-flex align-items-center justify-content-center">
                0
              </span>
            </a>
          </li>
      </div>
    </div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<!-- FontAwesome -->
<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
```
