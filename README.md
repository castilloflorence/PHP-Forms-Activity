# PHP-Forms_Avtivity

##<!DOCTYPE html>
<html>
<head>
	<title>PHP FORM ACTIVITY</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css">
</head>
<body>
	<div class="container">
		<h1>PHP FORM ACTIVITY</h1>
		<form method="post" action="process_form.php">
			<div class="mb-3">
				<label for="firstname" class="form-label">First Name:</label>
				<input type="text" id="firstname" name="firstname" class="form-control" required>
			</div>

			<div class="mb-3">
				<label for="lastname" class="form-label">Last Name:</label>
				<input type="text" id="lastname" name="lastname" class="form-control" required>
			</div>

			<div class="mb-3">
				<label for="email" class="form-label">Email:</label>
				<input type="email" id="email" name="email" class="form-control" required>
			</div>

			<div class="mb-3">
				<label for="username" class="form-label">Username:</label>
				<input type="text" id="username" name="username" class="form-control" required>
			</div>

			<div class="mb-3">
				<label for="password" class="form-label">Password:</label>
				<input type="password" id="password" name="password" class="form-control" required>
			</div>

			<div class="mb-3">
				<label for="confirmpassword" class="form-label">Confirm Password:</label>
				<input type="password" id="confirmpassword" name="confirmpassword" class="form-control" required>
			</div>

			<button type="submit" class="btn btn-primary">Submit</button>
		</form>
	</div>

	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
