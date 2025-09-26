<script lang="ts">
	import SectionHeader from "$lib/components/layout/SectionHeader.svelte";

	let {
		title,
		subtitle,
		imageSrc = "https://www.unc.mn/image-placeholder.svg",
		...rest
	}: {
		title: string;
		subtitle: string;
		imageSrc: string;
		[key: string]: any;
	} = $props();
</script>

<header class="border-b border-gray-100 dark:border-gray-900" {...rest}>
	<div class="text-title3 section-px section-py container mx-auto grid gap-16 gap-y-0">
		<SectionHeader {title} {subtitle} size="lg" />
		<div class="aspect-video overflow-clip rounded-xl bg-gray-100 transition-all duration-300 hover:scale-[1.02] hover:shadow-lg">
			<img
				class="h-full w-full object-cover transition-transform duration-500 hover:scale-110"
				src={imageSrc}
				alt="Professional team collaborating in facility management meeting"
			/>
		</div>
	</div>
</header>
