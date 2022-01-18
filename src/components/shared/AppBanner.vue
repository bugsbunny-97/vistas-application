<template>
	<!-- App Banner -->
	<!-- <section
		class="flex flex-col sm:justify-between items-center sm:flex-row mt-12 sm:mt-10"
	> -->
		<div class="banner_w3lspvt">
			<div class="csslider infinity" id="slider1">
				<input type="radio" name="slides" checked="checked" id="slides_1" />
				<input type="radio" name="slides" id="slides_2" />
				<input type="radio" name="slides" id="slides_3" />
				<input type="radio" name="slides" id="slides_4" />
				<ul class="banner_slide_bg">
					<li>
						<div class="container">
							<div class="w3ls_banner_txt">
								<h3 class="w3ls_pvt-title text-wh text-uppercase let">VISTAS</h3>
							</div>
						</div>
					</li>
					<li>
						<div class="container">
							<div class="w3ls_banner_txt">
								<h3 class="w3ls_pvt-title text-wh text-uppercase let">VISTAS</h3>
							</div>
						</div>
					</li>
					<li>
						<div class="container">
							<div class="w3ls_banner_txt">
								<h3 class="w3ls_pvt-title text-wh text-uppercase let">VISTAS</h3>
							</div>
						</div>
					</li>
					<li>
						<div class="container">
							<div class="w3ls_banner_txt">
								<h3 class="w3ls_pvt-title text-wh text-uppercase let">VISTAS</h3>
							</div>
						</div>
					</li>
				</ul>
				<div class="arrows">
					<label for="slides_1"></label>
					<label for="slides_2"></label>
					<label for="slides_3"></label>
					<label for="slides_4"></label>
				</div>
			</div>
		</div>
</template>

<script>
import feather from 'feather-icons';
import '../../assets/css/css_slider.css';
import '../../assets/css/style.css'

export default {
	name: 'Home',
	data: () => {
		return {
			theme: '',
		};
	},
	created() {
		this.theme = localStorage.getItem('theme') || 'light';
	},
	mounted() {
		feather.replace();
		this.theme = localStorage.getItem('theme') || 'light';
	},
	updated() {
		feather.replace();
	},
	methods: {},
};
</script>

<style scoped></style>
