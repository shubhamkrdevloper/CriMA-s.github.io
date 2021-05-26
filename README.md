<!doctype html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">

  <title>CriMA's Tours & travels!</title>
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-success bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">CriMA's</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="home.html">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="family.html">Our Family</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="facility.html" id="navbarDropdown" role="button"
              data-bs-toggle="dropdown" aria-expanded="false">
              Our Facilities
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="tour.html">Tourism</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="mental.html">Mental Support</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="education.html">Education</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="social.html">Social works</a></li>

              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="idea.html">New Ideas</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="/contact.html" id="navbarDropdown" role="button"
              data-bs-toggle="dropdown" aria-expanded="false">
              Contact Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="mobile.html">Mobile call</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="whatsapp.html">Whatsapp</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="mail.html">Email</a></li>

              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="facebook.html">Facebook</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="instagram.html">Instagram</a></li>
            </ul>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
        <div class="mx-2">
          <button class="btn btn-success" data-toggle="modal" 
          data-target="#loginModal">Login</button>
          <button class="btn btn-success" data-toggle="modal" 
          data-bs-target="#signupModal">SignUp</button>
        </div>
      </div>
    </div>
  </nav>
  

<!-- Login Modal -->
<div class="modal fade" id="loginModal" tabindex="-1" aria-labelledby="loginModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Logged your account</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <form>
          <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
          </div>
          <div class="mb-3">
            <label for="exampleInputPassword1" class="form-label">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
          </div>
          <div class="mb-3 form-check">
            <input type="checkbox" class="form-check-input" id="exampleCheck1">
            <label class="form-check-label" for="exampleCheck1">Check me out</label>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>


<!--sign up Modal -->
<div class="modal fade" id="signupModal" tabindex="-1" aria-labelledby="signupModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="signupModalLabel">Create CriMA's Account</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <form>
          <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">Email address</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
          </div>
          <div class="mb-3">
            <label for="exampleInputPassword1" class="form-label">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
          </div>
          <div class="mb-3 form-check">
            <input type="checkbox" class="form-check-input" id="exampleCheck1">
            <label class="form-check-label" for="exampleCheck1">Check me out</label>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>

  

  <div class="card bg-dark text-white border">
    <img src="https://source.unsplash.com/800x400/?nature,sea" class="card-img" alt="...">
    <div class="card-img-overlay border">
      <h2 class="card-title">CriMA's</h2>
      <h3 class="card-title">Our dream is to fulfill your dreams</h3>
      <h5 class="card-text">Try to jump once again</h5>
      
    </div>
  </div>
  <!--new tab-->
  <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators border">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner border">
      <div class="carousel-item active border">
        <img src="2nd.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h3>Welcome To CriMA's</h3>
          <p>We are a Family of CriMA's<br>Mountain Trip</p>
          <button class="btn btn-danger">Hotels</button>
          <button class="btn btn-primary">Trip Days</button>
          <button class="btn btn-dark">Package</button>
        </div>
      </div>
      <div class="carousel-item">
        <img src="keral.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Kerala Trip</h5>
          <p>We are with you in kerala </p>
          <button class="btn btn-danger">Hotels</button>
          <button class="btn btn-primary">Trip Days</button>
          <button class="btn btn-dark">Package</button>
        </div>
      </div>
      <div class="carousel-item">
        <img src="sea23.jpg" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h5>Goa Trip</h5>
          <p>Chilling Time</p>
          <button class="btn btn-danger">Hotels</button>
          <button class="btn btn-primary">Trip Days</button>
          <button class="btn btn-secondary">Package</button>
        </div>
      </div>
    </div>
    <div class="container my-4 ml-4 mr-4">
      <div class="row mb-2">
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-primary">South India</strong>
              <h3 class="mb-0">Best Deals</h3>
              <div class="mb-1 text-muted">Today</div>
              <p class="card-text mb-auto">See the latest best package for you</p>
              <!--a href="#" class="stretched-link">Continue reading</a>-->
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="keral.jpg" alt="">

            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-success">North-East India</strong>
              <h3 class="mb-0">Jumbo Package</h3>
              <div class="mb-1 text-muted">Today</div>
              <p class="mb-auto">This Jumbo Package is specially designed for touring all North-East India.</p>
              <!--a href="#" class="stretched-link">Continue reading</a>-->
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="thumb7.jpg" alt="">

            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container my-4 ml-4 mr-4">
      <div class="row mb-2">
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-primary">North India</strong>
              <h3 class="mb-0">Best Deals</h3>
              <div class="mb-1 text-muted">Today</div>
              <p class="card-text mb-auto">See the latest best package for you</p>
              <!--a href="#" class="stretched-link">Continue reading</a>-->
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="thumb8.jpg" alt="">

            </div>
          </div>
        </div>
        <div class="col-md-6">
          <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
            <div class="col p-4 d-flex flex-column position-static">
              <strong class="d-inline-block mb-2 text-success">INDIA</strong>
              <h3 class="mb-0">Jumbo Package</h3>
              <div class="mb-1 text-muted">Today</div>
              <p class="mb-auto">The Jumbo Package is specially designed for touring all over India.</p>
              <!--a href="#" class="stretched-link">Continue reading</a>-->
            </div>
            <div class="col-auto d-none d-lg-block">
              <img class="bd-placeholder-img" width="200" height="250" src="thumb9.jpg" alt="">

            </div>
          </div>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner border">
      <div class="carousel-item active border" data-bs-interval="10000">
        <img src="beauty.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item border" data-bs-interval="2000">
        <img src="beauty2.jpg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="s.jpg" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <footer class="container">
    <p class="float-right"><a href="#">Back to top</a></p>
    <p>© 2021-2020 Company, Inc. · <a href="#">CriMa's</a> · <a
        href="https://www.facebook.com/profile.php?id=100045916906265">Shubham Kumar</a></p>
  </footer>

  <!--3rd
      <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner border">
          <div class="carousel-item active ">
            <img src="1.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block ">
              <h5>Building</h5>
              <p>Very attractive place.</p>
            </div>
          </div>
          <div class="carousel-item border">
            <img src="mou2.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block ">
              <h5>Nature with Technology.</h5>
              <p>Try to feel this moments of time.</p>
            </div>
          </div>
          <div class="carousel-item border">
            <img src="sea3.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block ">
              <h5>Beauty of Nature.</h5>
              <p>Feeling Happy Stay with nature.</p>
              <p>Stay as a family.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    -->



  <!-- Optional JavaScript; choose one of the two! -->

  <!-- Option 1: Bootstrap Bundle with Popper -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
    crossorigin="anonymous">
    var myModal = document.getElementById('myModal')
    var myInput = document.getElementById('myInput')
    
    myModal.addEventListener('shown.bs.modal', function () {
      myInput.focus()
    })
  </script>

  <!-- Option 2: Separate Popper and Bootstrap JS -->
  <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
    -->
</body>

</html>
