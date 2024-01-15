# Travelling-website
simple_ travelling _website

# index.html
travelling simple website
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Tourist-Home</title>
   <!-- favicon -->
   <link rel="shortcut icon" href="images/about.jpg" type="image/x-icon">
   <!-- bootstrap css -->
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" 
   integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
   <!-- css file -->
   <link rel="stylesheet" href="styles.css">
   <!-- google fonts -->
   <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,wght@0,300;0,500;0,800;1,700&family=Nunito:ital,wght@1,700&display=swap" rel="stylesheet">
</head>
<body>

   <!-- navbar -->
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">About</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"></a>
            </li>
            <li class="nav-item">
               <a class="nav-link" href="#">Gallery</a>
             </li>
             <li class="nav-item">
               <a class="nav-link" href="#"></a>
             </li>
             <li class="nav-item">
               <a class="nav-link" href="#">Book</a>
             </li>
             <li class="nav-item">
               <a class="nav-link" href="#"></a>
             </li>
            
             <li class="nav-item">
               <a class="nav-link" href="#">Packages</a>
             </li>
             <li class="nav-item">
               <a class="nav-link" href="#"></a>
             </li>
             <li class="nav-item">
               <a class="nav-link" href="#">Contact</a>
             </li>
             <li class="nav-item">
               <a class="nav-link" href="#"></a>
             </li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </nav>

   <!-- hero section -->
   <div class="container-fluid position-relative p-0">
      <div class="container-fluid bg-primary py-5 mb-5 hero-header">
         <div class="container py-5">
            <div class="row justify-content-center py-5">
               <div class="col-lg-10 pt-lg-5 mt-lg-5 text-center">
               <h1 class="display-3 text-white mb-3"></h1>
               <p class="fs-4 text-white mb-4"></p>
               <div class="position-relative w-75 mx-auto">
                  <!-- input box -->
                  <input type="text" class="form-control border-0 rounded-pill w-100 py-3 ps-4 pe-5" placeholder="Eg: London">
                  <!-- button types -->
                  <button type="button" class="btn btn-primary rounded-pill py-2 px-4 position-absolute top-0 end-0 me-2" style="margin-top:7px;">search</button>
               </div>
            </div>
         </div>
      </div>
      </div>
   </div>
           
   <!-- about section -->
<div class="container-xxl py-5">
   <div class="container">
      <div class="row g-5">
        <div class="col-lg-6" style="min-height:400px;">
         <div class="position-relative h-100">
             <img src="images/about.jpg" alt="" style="object-fit:cover;" class="img-fluid position-absolute  w-100 h-100">
         </div>
      </div>
      <div class="col-lg-6">
         <h6 class="section-title bg-white text-start text-primary pe-3">About us</h6>
         <h1 class="mb-4">Welcome to <span class="text-primary">Tourist</span></h1>

         <p class="mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur suscipit debitis, ipsum ea molestiae 
            quaerat ullam nam. Molestias blanditiis minima obcaecati cum autem, harum est culpa at assumenda, magni eveniet!</p>
            <p class="mb-4">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reiciendis iste dicta ipsum qui molestiae a officia ducimus nobis ratione.
                Accusamus dolor reprehenderit sequi dicta iusto in nemo culpa maxime saepe.</p>

                <div class="First class flight" id="First class Example">
                  <div class="First-class">
                    <h2 class="First-class" id="headingOne">
                      <button class="First-class" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                        First class Flights 
                      </button>
                    </h2>
                    <div id="collapseOne" class="firstclass-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                      <div class="accordion-body">
                        <strong>This is the first class accordiong body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                      </div>
                    </div>
                  </div>
                  <div class="luxirious-hotels">
                    <h2 class="accordion-header" id="headingTwo">
                      <button class="luxrious hotel-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                        Luxurious hotels
                      </button>
                    </h2>
                    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                      <div class="accordion-body">
                        <strong>This is the Luxurious luxirious-hotels accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                      </div>
                    </div>
                  </div>
                  <!-- button -->
                  <div class="btn btn-primary py-3 px-5 mt-2">Read more</div>
                    </div>
                  </div>
                </div>
             </div>
         </div>
      </div>
   </div>
</div>
<!-- destination section -->
<div class="container-xxl py-5 destination">
  
      <div class="text-center">
         <h6 class="section-title bg-white text-center text-primary px-3">
            Destination
         </h6>
         <h1 class="mb-5">Popular Destination</h1>
      </div>

      <div class="row g-3">
         <div class="col-lg-7 col-md-6">
            <div class="row g-3">


               <div class="col-lg-12 col-md-12">
                  <a href=""   class="d-block position-relative overflow-hidden">
                     <img src="images/destination-1.jpg" alt="" class="img-fluid">
                     <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">30% off</div>
                     <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2">Thailand</div>
                  </a>
               </div>

               <div class="col-lg-6 col-md-12">
                  <a href=""   class="d-block position-relative overflow-hidden">
                     <img src="images/destination-2.jpg" alt="" class="img-fluid">
                     <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">50% off</div>
                     <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2">Malaysia</div>
                  </a>
            </div>
            <div class="col-lg-6 col-md-12">
               <a href=""   class="d-block position-relative overflow-hidden">
                  <img src="images/destination-3.jpg" alt="" class="img-fluid">
                  <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">25% off</div>
                  <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2">Australia</div>
               </a>
         </div>

      </div>
   </div>
   <div class="col-lg-5 col-md-6" style="min-height:350px;">
      <a href="" class="d-block position-relative h-100 overflow-hidden">
         <img src="images/destination-4.jpg"  alt="" class="img-fluid position-absolute w-100 h-100"  style="object-fit: cover;">
         <div class="bg-white text-danger fw-bold position-absolute top-0 start-0 m-3 py-1 px-2">20% Off</div>
         <div class="bg-white text-primary fw-bold position-absolute bottom-0 end-0 m-3 py-1 px-2">Indonesia</div>
      </a>
   </div>
</div>

<!-- slider -->
<div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
   <div class="carousel-inner">
     <div class="carousel-item active">
       <img src="images/package-1.jpg" class="d-block w-100" alt="...">
     </div>
     <div class="carousel-item">
       <img src="images/package-2.jpg" class="d-block w-100" alt="...">
     </div>
     <div class="carousel-item">
       <img src="images/package-3.jpg" class="d-block w-100" alt="...">
     </div>
   </div>
   <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
     <span class="carousel-control-prev-icon" aria-hidden="true"></span>
     <span class="visually-hidden">Previous</span>
   </button>
   <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
     <span class="carousel-control-next-icon" aria-hidden="true"></span>
     <span class="visually-hidden">Next</span>
   </button>
 </div>
<!-- form login -->
<div class="col-lg-6"></div>
<h2>Sign up here!!!</h2>
<form onsubmit="return validation()" name="submit-googlesheet" method="post">
</form>
<form>
   <div class="mb-3">
      <label for="exampleInput1" class="form-label">Full name</label>
      <input type="text" class="form-control" id="exampleInput1">
      <span id="error-name" style="font-size: 10px; color:red;"></span>
      
    </div>
   <div class="mb-3">
     <label for="exampleInputEmail1" class="form-label">Email address</label>
     <input type="email" class="form-control" id="exampleInputEmail1">
     <span id="error-name" style="font-size: 10px; color:red;"></span>
   </div>

   <div class="mb-3">
      <label for="exampleInput2" class="form-label">Contact number</label>
      <input type="number" class="form-control" id="exampleInput2" aria-describedby="emailHelp">
      <span id="error-name" style="font-size: 10px; color:red;"></span>
    </div>

   <div class="mb-3">
     <label for="exampleInputPassword1" class="form-label">New Password</label>
     <input type="password" class="form-control" id="exampleInputPassword1">
     <span id="error-name" style="font-size: 10px; color:red;"></span>
   </div>
   <div class="mb-3">
      <label for="exampleInputPassword2" class="form-label">confirm Password</label>
      <input type="password" class="form-control" id="exampleInputPassword2">
      <span id="error-name" style="font-size: 10px; color:red;"></span>
    </div>
   <button type="sign in" class="btn btn-primary">sign in</button>
 </form>

<!-- testimonial -->

<div class="container-xxl py-5">
   <div class="container">
      <div class="text-center">
         <h6 class="section-title bg-white text-center text-primary px-3">testimonial</h6>
         <h1 class="mb-5">Our clients say!!!</h1>
      </div>
      <div class="owl-carousel testimonial-carousel position-relative">
         <div class="testimonial-item bg-white text-center border p-4">
            <img src="images/team-1.jpg" alt=""  class="bg-white rounded-circle shadow p-1 mx-auto mb-3"  style="width: 80px; height: 80px;">
            <h5 class="mb-0">Jhon Doe</h5>
            <p> New york,USA</p>
            <p class="mb-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
         </div>
         <div class="testimonial-item bg-white text-center border p-4">
            <img src="images/team-2.jpg" alt=""  class="bg-white rounded-circle shadow p-1 mx-auto mb-3"  style="width: 80px; height: 80px;">
            <h5 class="mb-0">Jhon Mathew</h5>
            <p> New york,USA</p>
            <p class="mb-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure voluptatibus odio, ea porro animi eum adipisci </p>
      </div>
      <div class="testimonial-item bg-white text-center border p-4">
         <img src="images/team-3.jpg" alt=""  class="bg-white rounded-circle shadow p-1 mx-auto mb-3"  style="width: 80px; height: 80px;">
         <h5 class="mb-0">Jhon Robot</h5>
         <p> New york,USA</p>
         <p class="mb-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure voluptatibus odio, ea porro animi eum adipisci consequuntur tempore ratione soluta recusandae molestiae accusamus modi </p>
   </div>
</div>
