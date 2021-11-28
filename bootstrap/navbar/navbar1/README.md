Navbar
------

1) Build a basic nav bar
2) Move the navigation to the right
3) Add a logo
4) Ensure that the navigation is ADA accessible per the W3.org guidines

* sm - small
* md - medium
* lg - large
* xl - extra-large

```
<button class="navbar-toggler" type="button" 
            data-bs-toggle="collapse" 
            data-bs-target="#toggleMobileMenu"    // using this as id 
            aria-controller= "toggleMobileMenu"   
            aria-expanded="false"  // by default it should not in expanded state
            aria-label="Toggle navigation">
```

* anchor element should have text but make it invisible by style display none
```
<a href="#" class="navbar-brand">
                <img src="#img" alt="image" width="30" height="24"
                class="d-inline-block align-top" >
                <span class="hidden">Logo</span>    
            </a>
```
