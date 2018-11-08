<template>
	<div id="app">

		<b-navbar toggleable="md" type="dark" variant="dark">
			<b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
			<b-navbar-brand href="javascript:void(0)">vCRUD</b-navbar-brand>
			<b-collapse is-nav id="nav_collapse">
				<b-navbar-nav>
					<b-nav-item to="/home">Home</b-nav-item>
					<b-nav-item to="/about">About</b-nav-item>
				</b-navbar-nav>
			</b-collapse>
		</b-navbar>

		<router-view/>
	</div>
</template>
