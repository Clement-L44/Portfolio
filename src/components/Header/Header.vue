
<script>

export default {
	name: 'HeaderPortfolio'
}
/*
var wh = document.getSelection(window).height(),
	half = wh / 2,
	headerHeight = document.getElementsByClassName('header').outerHeight();
	

document.getSelection(window).scroll(function() {
	var scrollTop = document.getSelection(window).scrollTop();

if (scrollTop >= half) {
	document.getElementsByClassName('header').addClass('is-scroll');
} else {
	document.getElementsByClassName('header').removeClass('is-scroll');
}
    
document.getElementsByClassName('.onepage-nav').dropdownMenu({
	menuClass:'onepage-menu',
	breakpoint: 1200,
	toggleClass: 'active',
	classButtonToggle: 'navbar-toggle',
	subMenu: {
		class: 'sub-menu',
		parentClass: 'menu-item-has-children',
		toggleClass: 'active'
	}
});
    
document.getElementsByClassName('.onepage-nav').onePageNav({
	currentClass: 'current-menu-item',
	scrollOffset: headerHeight
});
*/

</script>

<template>
	<header class="header header--fixed">
				<div class="container">
					<div class="header__inner">
						<div class="header__logo"><a href="index.html"><img src="../../assets/img/Clément LEHUEDE.png" alt=""/></a></div>
						<div class="header__menu">
							
							<!-- onepage-nav -->
							<nav class="onepage-nav">
								
								<!-- onepage-menu -->
								<ul class="onepage-menu">
									<li class="current-menu-item"><a href="#id-1">Home</a>
									</li>
									<li><a href="#id-2">A Propos</a>
									</li>
									<li><a href="#id-3">Formations</a>
									</li>
									<li><a href="#id-4">Portfolio</a>
									</li>
								</ul><!-- onepage-menu -->
								
								<div class="navbar-toggle"><span></span><span></span><span></span></div>
							</nav><!-- End / onepage-nav -->
							
						</div>
					</div>
				</div>
			</header>
</template>

<style>
	@import './Header.css';
</style>