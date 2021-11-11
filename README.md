![navbar](https://user-images.githubusercontent.com/37051222/141258047-b4cfa670-4aad-4d8a-9a3f-6d9c3195543f.png)



```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Medium</title>

    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/medium.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=Roboto+Slab:wght@100;300;400;700;800&display=swap" rel="stylesheet">

</head>
<body>

<!--Navbar-->
<div class="bg-yellow border-bottom-dark py-1">
    <div class="container">
        <!--Navbar-->
        <nav class="navbar navbar-expand-lg navbar-light ">
            <div class="container-fluid">
              <a class="navbar-brand fw-bold" style="font-size: 30px;" href="#">
                  <img src="img/medium-logo.png" style="width: 35px; height: 35;" alt="">Medium
              </a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">   <!--"ms-auto"=>sol taraftan otomarik kopsun-->
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                      </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Our Story</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Membership</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Write</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link">Sign In</a>
                  </li>
                  <li class="nav-item ms-4">
                    <a class="nav-link btn btn-dark text-light">Get Started</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </div>
</div>


<!--Container-->
<div class="bg-yellow py-5 border-bottom-dark">
    <div class="container">
        <div class="row">
            <div class="col-5">
                <h1 class="display-1">Explore new <br> perspectives</h1>
                <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi, nostrum Lorem ipsum dolor sit Lorem ipsum. <a class="text-dark" href="#">dolor sit amet</a></p>
                <a href="#" class="btn btn-outline-dark">Get Started</a>
            </div>
            <div class="col-7">
                <img src="img/medium-image.png" class="pe-5" style="width: 450px; height: 300px; float: right;" alt="image">
            </div>
        </div>
    </div>
</div>
    


<script src="js/bootstrap.bundle.min.js"></script>
</body>
</html>

```



```
css

body{
    font-family: 'Playfair Display', serif;
    font-family: 'Roboto Slab', serif;
}

.bg-yellow{
    background-color: #FFC017;
}

.border-bottom-dark{
    border-bottom: 1px solid #414141;
}

```
