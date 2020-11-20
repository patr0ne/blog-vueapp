<template>
	<div>
		<blog-topbar />
		<router-view />
	</div>
</template>

<script>
import BlogTopbar from '@/components/Topbar'

export default {
	name: 'BlogApp',
	components: {
		BlogTopbar
	}
}
</script>
