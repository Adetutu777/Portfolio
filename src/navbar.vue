<template>
    <nav class="navbar navbar-expand-lg navbar-light">
	<a class="navbar-brand" href="#">Brand<b>Name</b></a>  		
	<button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
		<span class="navbar-toggler-icon"></span>
	</button>
	<!-- Collection of nav links, forms, and other content for toggling -->
	<div id="navbarCollapse" class="collapse navbar-collapse justify-content-start">
		<div class="navbar-nav">
			<a href="#" class="nav-item nav-link">Home</a>
			<a href="#" class="nav-item nav-link">About</a>			
			<div class="nav-item dropdown">
				<a href="#" class="nav-item nav-link dropdown-toggle" data-toggle="dropdown">Services</a>
				<div class="dropdown-menu">					
					<a href="#" class="dropdown-item">Web Design</a>
					<a href="#" class="dropdown-item">Web Development</a>
					<a href="#" class="dropdown-item">Graphic Design</a>
					<a href="#" class="dropdown-item">Digital Marketing</a>
                </div>
            </div>
			<a href="#" class="nav-item nav-link">Portfolio</a>
			<a href="#" class="nav-item nav-link active">Blog</a>
			<a href="#" class="nav-item nav-link">Contact</a>
        </div>
		<div class="navbar-nav ml-auto">
			<div class="navbar-form-wrapper">
				<form class="navbar-form form-inline">
					<div class="input-group search-box">								
						<input type="text" id="search" class="form-control" placeholder="Search Here...">
						<div class="input-group-append">
							<span class="input-group-text">
								<i class="material-icons">&#xE8B6;</i>
							</span>
						</div>
					</div>
                </form>
            </div>
			<a href="#" class="nav-item nav-link"><i class="fa fa-facebook"></i></a>
			<a href="#" class="nav-item nav-link"><i class="fa fa-twitter"></i></a>
			<a href="#" class="nav-item nav-link"><i class="fa fa-google-plus"></i></a>
			<a href="#" class="nav-item nav-link"><i class="fa fa-pinterest-p"></i></a>
        </div>		
	</div>
</nav>
</template>