<script>
import SEO from '$lib/components/SEO/index.svelte'
import MyOrder from './_MyOrder.svelte'

const seoProps = {
	title: 'Orders ',
	description: 'Orders '
}

export let data
</script>

<SEO {...seoProps} />

<section>
	<MyOrder orders="{data.orders}" currentPage="{data.currentPage}" />
</section>
