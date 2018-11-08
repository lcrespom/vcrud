<template>
	<div id="app">
		<nav class="navbar navbar-expand-lg navbar-light bg-light">
			<!-- Title -->
			<a class="navbar-brand" href="javascript:void(0)">vCRUD</a>
			<!-- Responsive hamburger menu -->
			<button class="navbar-toggler" type="button" data-toggle="collapse"
				data-target="#navbarSupportedContent"
				aria-controls="navbarSupportedContent" aria-expanded="false"
				aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<!-- Collapsible nav elements -->
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav mr-auto">
					<li class="nav-item active">
						<router-link to="/" class="nav-link">Home</router-link>
					</li>
					<li class="nav-item">
						<router-link to="/about" class="nav-link">About</router-link>
					</li>
				</ul>
			</div>
		</nav>

		<router-view/>
	</div>
</template>

