# Project Responsive Web Design using Bootstrap
## Date:26.12.2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
    <nav class="navbar navbar-expand-lg shadow-sm">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Hire a Designer</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Find Jobs</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container mt-4">
        <div class="w-50">
        <input type="text" class="form-control" placeholder="search">
    </div>
    </div>
    <div class="container mt-4">
    <div class="row g-4">
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="img-1.jpg" width="304" height="225">
              
                <div class="card-body text-center">
                    <p class="card-text mb-0">B-Mark</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="img-2.png" width="300" height="225">
                
                <div class="card-body text-center">
                    <p class="card-text mb-0">Casper Cards</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="img-3.png" width="300" height="225">
                <div class="card-body text-center">
                    <p class="card-text mb-0">𝗘𝘃𝗼𝗹𝘂𝗿</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="https://cdn.dribbble.com/users/1739084/screenshots/4448965/kyzzlj.jpg?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
               
                <div class="card-body text-center">
                    <p class="card-text mb-0">MakeReign</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="https://cdn.dribbble.com/users/140043/screenshots/9106916/dribbble_4_compressed.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                <div class="card-body text-center">
                    <p class="card-text mb-0">Mattias Johannson</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="img-4.jpg" width="300" height="225">
                
                <div class="card-body text-center">
                    <p class="card-text mb-0">Exito mobile website</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="img-5.png"width="300" height="225">
                <div class="card-body text-center">
                    <p class="card-text mb-0">CentralHub dashboard</p>
                </div>
            </div>
        </div>
        <div class="col-md-3 col-sm-6">
            <div class="card shot-card">
                <img src="https://cdn.dribbble.com/userupload/10964296/file/original-ffa83431e0b8639f6d1036a0f80c76ae.png?resize=400x300&vertical=center" class="card-img-top" alt="Shot 2">
                <div class="card-body text-center">
                    <p class="card-text mb-0">Romain Tystramm</p>
                </div>
        </div></div></div></div>


    <footer style="text-align: center; background-color: black; color: white; padding: 15px;" >
        <p>&copy; Harish 2024 All Rights Reserved.</p>
    </footer>
</body>
</html>

```

## OUTPUT:
![alt text](<harish/dribble/static/Screenshot 2024-12-27 192423.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
