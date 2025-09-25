<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
		}
	];
</script>

<SecondaryHero
	title="Making safety simple"
	subtitle="One provider for every site"
	imageSrc="/generated/image-a-diverse-group-of-professionals-engaged.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Most operations teams are stuck with disconnected service partners, poor reporting, and constant surprises. That leads to gaps in safety, compliance failures, and unnecessary risk exposure. We built Company because managing hygiene and compliance across multiple locations shouldn't feel impossible—and because we understood that operations managers needed a partner who truly gets the pressure of keeping every site safe and compliant.",
		"We took a different approach: instead of adding another vendor to your list, we became the one partner that consolidates everything. We built unified service management that gives you real-time visibility, standardized execution, and rapid deployment capabilities. From our first contract to our ten-thousandth, we've refined our process to eliminate the chaos of juggling multiple providers while ensuring consistent quality across every location you manage.",
		"Today, operations teams across healthcare, retail, logistics, and property management trust us to keep their facilities running smoothly. We've transformed the $600B hygiene services market by proving that you don't have to choose between comprehensive coverage and operational simplicity. When you partner with Company, you get both—plus the peace of mind that comes from never having to scramble again."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to collaborate?"
	subtitle="Let's create something amazing"
	description="Join the companies already leveraging our expertise to transform their digital presence and achieve their business goals."
/>
