<template>
  <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign up for UN Wallet</title>
    <partial name="head"></partial>   
</head>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <div class="col">
        <h2>
            <a href="/"><i class="fas fa-wallet"></i> UN Wallet</a>
        </h2>
        </div>
    </div>
</nav>

<body>

    <div class="container p-3">
        <div class="row">
            <div class="col -md-0 offset -md-0">
                <div class="card animated flipInY">
                    <div class="card-header bg-primary text-white text-center">
                        <h3>
                            Sign up
                        </h3>
                    </div>
                    <div class="card-body">
                        <form>
                            <div class="form-group">
                                <label for="inputName">Name</label>
                                <input name="name" id="inputName" type="text" class="form-control" placeholder="Name"
                                    required>
                            </div>
                            <div class="form-group">
                                <label for="inputLastName">Last Name</label>
                                <input name="lastName" id="inputLastName" type="text" class="form-control"
                                    placeholder="Last Name" required>
                            </div>
                            <div class="form-group">
                                <label for="inputEmail">Email</label>
                                <input name="email" id="inputEmail" type="email" class="form-control"
                                    placeholder="Email" required>
                            </div>
                            <div class="form-group">
                                <label for="confirmPassword">Confirm Email</label>
                                <input name="confirmEmail" id="confirmEmail" type="text" class="form-control"
                                    placeholder="Confirm Email" required>
                            </div>
                            <div class="form-group">
                                <label for="inputPassword">Password</label>
                                <input name="password" id="inputPassword" type="password" class="form-control"
                                    placeholder="Password" required>
                            </div>
                            <div class="form-group">
                                <label for="confirmPassword">Confirm Password</label>
                                <input name="confirmPassword" id="confirmPassword" type="password" class="form-control"
                                    placeholder="Confirm Pasword" required>
                            </div>
                            <div class="form-group">
                                <div style="text-align: center">
                                    <input type="submit" value="Submit" class="btn btn-primary">
                                    <input type="button" value="Go Back" onclick="history.back()" class="btn btn-primary">
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <partial name="footer"></partial>
</body>
</html>
</template>

<script>
export default {

}
</script>

<style>

</style>