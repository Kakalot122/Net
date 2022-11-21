<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
</head>
<body>
    <main class="container">
        <header class="row text-center"></header>
        <section class="row">
            <form action="" method="post">
                <div class="card">
                    <div class="card-header">
                        Login To System
                    </div>
                    <div class="card-body">
                        <div class="form-group">
                            <label for="username">Username</label>
                            <input type="text" class="form-control" name="username" id="username" aria-describedby="usernameHid" placeholder="Username">
                            <small id="usernameHid" class="form-text text-muted">Username is valid</small>
                        </div>
                        <div class="form-group">
                            <label for="password">Password</label>
                            <input type="password" class="form-control" name="username" id="password" aria-describedby="passwordHid" placeholder="Password">
                            <small id="passwordHid" class="form-text text-muted">Password is valid</small>
                        </div>
                        <div class="form-check">
                            <label class="form-check-label">
                                <input type="checkbox" class="form-check-input" name="rememberMe" id="rememberMe" value="true">Remember Me
                            </label>
                        </div>
                        <div class="card-footer text-muted">
                            <button class="btn btn-primary">Login</button>
                            <button class="btn btn-secondary">Reset</button>
                        </div>
                    </div>
                </div>
            </form>
        </section>
    </main>
</body>
</html>
