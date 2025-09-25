<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Facility services that actually scale"
	subtitle="One partner. Every location. Always on time."
	imageSrc="/generated/image-a-professional-operations-manager-stands.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/hilton.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/starbucks.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/marriott.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/target.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="One provider. Every site covered."
	text="Managing multiple sites shouldn't mean juggling dozens of vendors. Our platform brings hygiene, safety, and compliance services under one roof—so you can focus on running your business, not chasing checklists. From offices to warehouses to retail chains, we help operations teams standardize cleanliness, reduce compliance risk, and avoid the costly surprises that come with fragmented service providers."
/>

<Testimonials
	testimonials={[
		{
			name: "Maxine Teo",
			position: "Director of Facilities",
			company: "HarborPoint Medical Group",
			quote:
				"We reduced vendor-related incidents by 40% and cut weekly update meetings in half. The real-time visibility across all our medical facilities has been transformative.",
			image: "/generated/image-a-professional-asian-woman-smiles-confid.webp"
		},
		{
			name: "Darnell Okafor",
			position: "Regional Operations Manager",
			company: "Simtra Retail Holdings",
			quote:
				"Company gave us instant oversight across 87 locations—we finally stopped flying blind. Compliance tracking that used to take days now happens in minutes.",
			image: "/generated/image-a-professional-black-man-in-business-att.webp"
		},
		{
			name: "Lina Chavez",
			position: "VP of Campus Services",
			company: "MetroEd Facilities Group",
			quote:
				"We consolidated 8 vendors into 1 and saved over $120,000 in the first year alone. The streamlined operations freed up our team to focus on strategic initiatives.",
			image: "/generated/image-a-professional-latina-woman-stands-in-a-.webp"
		}
	]}
/>

<Features
	title="Complete facility management solution"
	subtitle="Everything you need to maintain consistent hygiene standards across all your locations"
	features={[
		{
			title: "Unified service delivery",
			description: "One partner manages all your hygiene services across every location. No more juggling multiple vendors or dealing with inconsistent service quality.",
			imageSrc: "/generated/image-a-contemporary-commercial-building-lobby.webp"
		},
		{
			title: "Real-time compliance tracking",
			description: "Monitor safety and hygiene standards across all sites instantly. Get immediate alerts when issues arise, preventing potential violations before they impact your business.",
			imageSrc: "/generated/image-a-team-of-professionals-gathered-around-.webp"
		},
		{
			title: "Rapid deployment at scale",
			description: "Launch comprehensive hygiene programs at new locations within days, not weeks. Our proven deployment process ensures consistent standards from day one."
		},
		{
			title: "24/7 operational visibility",
			description: "See exactly what's happening at every location through our centralized dashboard. Track service completion, compliance scores, and performance metrics in real-time."
		},
		{
			title: "Multi-service expertise",
			description: "From deep cleaning to waste management, we handle every aspect of facility hygiene under one contract. Streamline your vendor relationships and reduce administrative overhead."
		},
		{
			title: "Proactive issue resolution",
			description: "Our intelligent monitoring system identifies potential problems before they become costly violations. Automatic escalation ensures critical issues receive immediate attention.",
			imageSrc: "/generated/image-a-professional-cleaning-crew-in-uniforms.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
