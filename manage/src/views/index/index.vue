<template>
	<div>welcome to come
		<footer-nav v-bind:class="{'isIndex':isNowPage}"></footer-nav>
	</div>
</template>

<script type="text/javascript">
	import FooterNav from '../../components/footer.vue'
	export default{
		components:{
			FooterNav
		},
		data(){
			return {
				isNowPage:true,
			// 	showAdd:false,
			// 	peoples:[{'name':'jack'},{'name':'linda'}]
			}
		},
		// methods:{
		// 	add(){
		// 		this.showAdd=true
		// 	}
		// }
	}
</script>