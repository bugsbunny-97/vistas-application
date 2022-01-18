<template>
	<div class="container mx-auto">
		<!-- Banner -->
		<AppBanner class="mb-5 sm:mb-8" />

	</div>
</template>

<script>
import AppBanner from '@/components/shared/AppBanner';

export default {
	name: 'Home',
	components: {
		AppBanner,
	},
};
</script>

<style scoped></style>
