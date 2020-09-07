<script>
export default {
    name: 'PresentationPortfolio',
    
}
</script>

<template>

    <section class="md-section bg-gray" id="id-2">
		<div class="container">
			<div class="row">
				<div class="col-lg-5 ">
								
								
					<div class="slide-image">
									
									
						<div class="swiper__module swiper-container slide-image__front" data-options='{"slidesPerView":1,"spaceBetween":0}'>
							<div class="swiper-wrapper">
								<div class="slide-item" style="background-image: url('../../../assets/img/about/paper-3213924_1920.jpg');"></div>
								<div class="slide-item" style="background-image: url('../../../assets/img/about/slide1.a.jpg');"></div>
								<div class="slide-item" style="background-image: url('../../../assets/img/about/smartphone-2454611_1920.jpg');"></div>
							</div>
							<div class="swiper-pagination-custom"></div>
						</div>
									
									
									
						<div class="swiper-thumbnails__module swiper-container slide-image__black" data-options='{"slidesPerView":1,"spaceBetween":0,"delay":10000}'>
							<div class="swiper-wrapper">
								<div class="slide-item" style="background-image: url('../../../assets/img/about/plans-1867745_1920.jpg');"></div>
								<div class="slide-item" style="background-image: url('../../../assets/img/about/pexels-hitesh-choudhary-879109.jpg');"></div>
								<div class="slide-item" style="background-image: url('../../../assets/img/about/mobile-phone-1875813_1920.jpg');"></div>
							</div>
						</div>
									
					</div>
								
				</div>
				<div class="col-lg-6 col-xs-offset-0 col-sm-offset-0 col-md-offset-0 col-lg-offset-1 ">	
					<div class="title">
						<h2 class="title__title">Hello from Clément</h2>
					</div>
					<p class="fz-16">Après une reconversion dans le monde du digital en intégrant la formation de développeur Web et Web Mobile, je me suis découvert une véritable passion pour la programmation.</p>
					<p class="fz-16">Aujourd'hui, je souhaite continuer en y faisant mon métier pour participer à l'innovation technologique du monde de demain.</p>
				</div>
			</div>

			<div class="swiper__module swiper-container mt-50" data-options='{"slidesPerView":3,"spaceBetween":30,"autoplay":2000,"breakpoints":{"640":{"slidesPerView":1},"991":{"slidesPerView":2}}}'>
				<div class="swiper-wrapper">
								
					<div class="service mb-0">
						<div class="service__icon"><i class="pe-7s-rocket"></i></div>
						<h3 class="service__title">Technoligies</h3>
						<p class="service__text">HTML5, CSS3, Javascript, PHP 7, Java, SQL, XML.</p>
					</div>
								
								
								
					<div class="service mb-0">
						<div class="service__icon"><i class="pe-7s-science"></i></div>
						<h3 class="service__title">Plateformes/Frameworks</h3>
						<p class="service__text">Symfony 4, 5, Angular 9, Node.JS, Java EE, SE, Bootstrap, JQuery.</p>
					</div>
								
								
					<div class="service mb-0">
						<div class="service__icon"><i class="pe-7s-server"></i></div>
						<h3 class="service__title">Base de données</h3>
                        <p class="service__text">MySQL, MongoDB, SQL Server, Oracle.</p>
					</div>
								
								
                               
					<div class="service mb-0">
						<div class="service__icon"><i class="pe-7s-pin"></i></div>
						<h3 class="service__title">Méthodologies</h3>
						<p class="service__text">Méthode de développement Agile (Scrum), UML (Unified Modeling Language), Modélisation des données (Oracle CDM).</p>
					</div>
                                
                                
								
					<div class="service mb-0">
						<div class="service__icon"><i class="pe-7s-plugin"></i></div>
						<h3 class="service__title">CMS</h3>
						<p class="service__text">Wordpress.</p>
					</div>>
                                
					<div class="service mb-0">
						<div class="service__icon"><i class="pe-7s-diamond"></i></div>
						<h3 class="service__title">Outils</h3>
						<p class="service__text">PHPStorm, Visual Studio Code, Bracket, Sublime Text, Eclipe, Git.</p>
					</div>              							
				</div>
			</div>					
		</div>
	</section>
</template>

<style>
	@import './Presentation.css';
</style>