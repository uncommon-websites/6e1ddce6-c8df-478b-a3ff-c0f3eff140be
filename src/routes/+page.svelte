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
	text="Managing multiple locations shouldn't mean juggling multiple vendors. We simplify operations by delivering hygiene, safety, and compliance services through one centralized partner—so you can focus on running your business, not chasing contractors.

We partner with office, retail, and warehouse teams to standardize cleanliness, increase compliance, and reduce risk—helping you maintain your standards while avoiding unnecessary costs and surprises."
/>

<Testimonials
	testimonials={[
		{
			name: "Maxine Teo",
			position: "Director of Facilities",
			company: "HarborPoint Medical Group",
			quote:
				"We reduced vendor-related incidents by 40% and cut weekly update meetings in half. Having one partner manage everything across our 23 facilities has been transformational.",
			image: "/generated/image-confident-asian-woman-in-business-attire.webp"
		},
		{
			name: "Darnell Okafor",
			position: "Regional Operations Manager",
			company: "Simtra Retail Holdings",
			quote:
				"Company gave us instant oversight across 87 locations—we finally stopped flying blind. Real-time compliance tracking means we catch issues before they become problems.",
			image: "/generated/image-trustworthy-black-man-dressed-profession.webp"
		},
		{
			name: "Lina Chavez",
			position: "VP of Campus Services",
			company: "MetroEd Facilities Group",
			quote:
				"We consolidated 8 vendors into 1 and saved over $120,000 in the first year alone. The streamlined communication and consistent service quality has been incredible.",
			image: "/generated/image-authoritative-latina-woman-in-elegant-bu.webp"
		}
	]}
/>

<Features
	title="Built for operations at scale"
	subtitle="Everything you need to maintain consistent hygiene standards across all your locations"
	features={[
		{
			title: "Real-time compliance monitoring",
			description: "Track hygiene standards across all locations instantly with automated reporting and alerts that keep you ahead of compliance issues.",
			imageSrc: "/generated/image-an-operations-manager-in-a-modern-office.webp"
		},
		{
			title: "Unified multi-site coordination", 
			description: "Eliminate fragmented communication with a single platform that connects all your facilities and service teams seamlessly.",
			imageSrc: "/generated/image-a-diverse-professional-team-communicatin.webp"
		},
		{
			title: "Rapid deployment system",
			description: "Get new locations operational in hours, not weeks, with our proven deployment process that scales to thousands of sites.",
			imageSrc: "/generated/image-staff-members-quickly-setting-up-hygiene.webp"
		},
		{
			title: "Integrated service umbrella",
			description: "Manage multiple service lines through one partner, reducing vendor complexity while maintaining consistent quality standards.",
			imageSrc: "/generated/image-a-cohesive-facility-services-team-workin.webp"
		},
		{
			title: "Proactive risk mitigation",
			description: "Identify and address potential issues before they impact operations with predictive monitoring and immediate response protocols.",
			imageSrc: "/generated/image-employees-performing-safety-checks-and-r.webp"
		},
		{
			title: "Revenue protection analytics",
			description: "Prevent revenue loss from compliance failures and facility issues with data-driven insights that protect your bottom line.",
			imageSrc: "/generated/image-a-group-of-business-professionals-gather.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
