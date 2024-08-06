# Header Section

## Header 1 :-

### HTML

![Header_1](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

```
    <!-- Header Starts  -->
    <header class="fixed-top shadow-sm">
      <nav
        class="navbar navbar-expand-lg mx-auto"
        style="background-color: #ffffff"
        id="main-navbar">
        <div class="container-fluid">
          <a class="navbar-brand" href="index.html">
            <img
              src="img/logo/logo.png"
              srcset="img/logo/logo.svg"
              alt="Logo"
              height="50px"
              style="padding-left: 10%" />
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"> </span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a
                  class="nav-link active"
                  aria-current="page"
                  href="#slider_section">
                  <i class="fa-solid fa-house nav-icon"></i>
                  <span class="d-sm-inline"> Home </span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#overview_section">
                  <i class="fa-solid fa-coins nav-icon"></i>
                  <span class="d-sm-inline"> Overview </span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#gallery_section">
                  <i class="fa-solid fa-images nav-icon"></i>
                  <span class="d-sm-inline"> Gallery </span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#configuration_section">
                  <i class="fa-solid fa-sliders nav-icon"></i>
                  <span class="d-sm-inline"> Configuration </span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#amenities_section">
                  <i class="fa-solid fa-wifi nav-icon"></i>
                  <span class="d-sm-inline"> Amenities </span>
                </a>
              </li>

              <li class="nav-item">
                <a class="nav-link" href="#location_section">
                  <i class="fa-solid fa-map-location nav-icon"></i>
                  <span class="d-sm-inline"> Location </span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#about_section">
                  <i class="fa-solid fa-user nav-icon"></i>
                  <span class="d-sm-inline"> About Us </span>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <!-- Header Ends  -->
```

### CSS

```
/* Navbar Starts */
header {
  height: 80px;
}

/* Navbar */
.navbar-nav {
  justify-content: flex-end;
  width: 100%;
}

.navbar-nav .nav-link {
  color: var(--colorBlack);
}

.navbar-nav .nav-link.active,
.navbar-nav .nav-link.show {
  background-color: var(--colorPrimary);
  height: 100%;
  color: var(--colorWhite);
}

.nav-link:hover {
  background-color: var(--colorPrimary);
  color: var(--colorWhite);
}

.nav-icon {
  margin-right: 5px;
}
@media only screen and (min-width: 1000px) {
  .navbar-nav .nav-link {
    font-size: 1.01vw !important;
    letter-spacing: 0.02vw;
  }
}
@media screen and (max-width: 600px) {
  .navbar-brand img {
    height: 45px;
  }
}

/* Navbar Ends */

```
