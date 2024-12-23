# Project Responsive Web Design using Bootstrap
# Date:07.12.24
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
main
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Responsive Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .gallery-card img {
            height: 180px;
            object-fit: cover;
        }
        .navbar-brand {
            font-weight: bold;
            font-size: 1.5rem;
        }
        footer {
            background-color: #343a40;
            color: white;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Gallery Showcase</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="aboutus.html">About Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="contactus.html">Contact Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="login.html">Login</a></li>
                    <li class="nav-item"><a class="nav-link" href="signup.html">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="bg-primary text-white text-center py-5">
        <h1>Welcome to the Gallery Showcase</h1>
        <p>Explore stunning images and more!</p>
    </div>

    <div class="container my-4">
        <h2 class="text-center mb-4">Explore Our Gallery</h2>
        <div class="row">
            <div class="col-md-4 mb-4">
                <div class="card gallery-card">
                    <img src="https://picsum.photos/400/300?random=1" class="card-img-top" alt="Gallery Image 1">
                    <div class="card-body">
                        <h5 class="card-title">Gallery Item 1</h5>
                        <button class="btn btn-outline-primary btn-sm">Like</button>
                        <button class="btn btn-outline-secondary btn-sm">Share</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card gallery-card">
                    <img src="https://picsum.photos/400/300?random=2" class="card-img-top" alt="Gallery Image 2">
                    <div class="card-body">
                        <h5 class="card-title">Gallery Item 2</h5>
                        <button class="btn btn-outline-primary btn-sm">Like</button>
                        <button class="btn btn-outline-secondary btn-sm">Share</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card gallery-card">
                    <img src="https://picsum.photos/400/300?random=3" class="card-img-top" alt="Gallery Image 3">
                    <div class="card-body">
                        <h5 class="card-title">Gallery Item 3</h5>
                        <button class="btn btn-outline-primary btn-sm">Like</button>
                        <button class="btn btn-outline-secondary btn-sm">Share</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card gallery-card">
                    <img src="https://picsum.photos/400/300?random=4" class="card-img-top" alt="Gallery Image 4">
                    <div class="card-body">
                        <h5 class="card-title">Gallery Item 4</h5>
                        <button class="btn btn-outline-primary btn-sm">Like</button>
                        <button class="btn btn-outline-secondary btn-sm">Share</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card gallery-card">
                    <img src="https://picsum.photos/400/300?random=5" class="card-img-top" alt="Gallery Image 5">
                    <div class="card-body">
                        <h5 class="card-title">Gallery Item 5</h5>
                        <button class="btn btn-outline-primary btn-sm">Like</button>
                        <button class="btn btn-outline-secondary btn-sm">Share</button>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-4">
                <div class="card gallery-card">
                    <img src="https://picsum.photos/400/300?random=6" class="card-img-top" alt="Gallery Image 6">
                    <div class="card-body">
                        <h5 class="card-title">Gallery Item 6</h5>
                        <button class="btn btn-outline-primary btn-sm">Like</button>
                        <button class="btn btn-outline-secondary btn-sm">Share</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="text-center py-3">
        <p>&copy; 2024 Gallery Showcase</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
login
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #8471ff8f;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-box {
            background-color: #ffffff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
        }
        .login-box h2 {
            text-align: center;
            margin-bottom: 1.5rem;
            color: #333;
        }
        .form-label {
            font-size: 1rem;
        }
    </style>
</head>
<body>
    <div class="login-box">
        <h2>Login</h2>
        <form>
            <div class="mb-3">
                <label for="loginEmail" class="form-label">Email</label>
                <input type="email" class="form-control" id="loginEmail" placeholder="Enter your email">
            </div>
            <div class="mb-3">
                <label for="loginPassword" class="form-label">Password</label>
                <input type="password" class="form-control" id="loginPassword" placeholder="Enter your password">
            </div>
            <button type="submit" class="btn btn-primary w-100">Login</button>
        </form>
        <div class="mt-3 text-center">
            <p>Don't have an account? <a href="signup.html">Sign Up</a></p>
        </div>
    </div>
</body>
</html>

```
sign up
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #8cc4f6;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .signup-box {
            background-color: #ffffff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
        }
        .signup-box h2 {
            text-align: center;
            margin-bottom: 1.5rem;
            color: #333;
        }
        .form-label {
            font-size: 1rem;
        }
        .social-buttons {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }
    </style>
</head>
<body>
    <div class="signup-box">
        <h2>Sign Up</h2>
        <form>
            <div class="mb-3">
                <label for="signupEmail" class="form-label">Email</label>
                <input type="email" class="form-control" id="signupEmail" placeholder="Enter your email">
            </div>
            <div class="mb-3">
                <label for="signupPassword" class="form-label">Password</label>
                <input type="password" class="form-control" id="signupPassword" placeholder="Create a password">
            </div>
            <div class="mb-3">
                <label for="confirmPassword" class="form-label">Confirm Password</label>
                <input type="password" class="form-control" id="confirmPassword" placeholder="Confirm your password">
            </div>
            <button type="submit" class="btn btn-primary w-100">Sign Up</button>
        </form>
        <div class="mt-3 text-center">
            <p>or sign up with</p>
            <div class="social-buttons">
                <button class="btn btn-danger w-100">Sign Up with Google</button>
                <button class="btn btn-warning w-100">Sign Up with Facebook</button>
            </div>
        </div>
        <div class="mt-3 text-center">
            <p>Already have an account? <a href="login.html">Login</a></p>
        </div>
    </div>
</body>
</html>

```
# OUTPUT:
![Screenshot 2024-12-23 143937](https://github.com/user-attachments/assets/c273d3ff-fe5d-4a46-9ece-ffb6ce8e41d4)
![Screenshot 2024-12-23 143947](https://github.com/user-attachments/assets/338cff1a-8162-4795-91f6-7db18181a602)
![Screenshot 2024-12-23 144000](https://github.com/user-attachments/assets/d7cbc458-1900-4b81-b1ec-541462355f9c)
![Screenshot 2024-12-23 144024](https://github.com/user-attachments/assets/3fa44a3d-1126-44d2-b1ba-aafbda39482f)
![Screenshot 2024-12-23 144035](https://github.com/user-attachments/assets/1b02fc1b-fa8a-42ff-87be-0232c3b6fb07)






# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
