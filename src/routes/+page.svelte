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
	title="One partner for safer, cleaner spaces"
	subtitle="Plenar brings fire safety, hygiene, and essential building services under one contract—so you can focus on running safer, smarter facilities."
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
	title="One provider. Every service. Every site covered."
	text="Managing multiple locations shouldn't mean juggling multiple vendors. Plenar simplifies operations by delivering fire safety, hygiene, pest control, and maintenance services through one centralized partner—so you can focus on running your business, not chasing contractors.

We partner with office, retail, healthcare, and warehouse teams to standardize safety protocols, maintain cleanliness standards, and ensure regulatory compliance—helping you protect your operations while reducing vendor complexity and administrative overhead."
/>

<Testimonials
	testimonials={[
		{
			name: "Maxine Teo",
			position: "Director of Facilities",
			company: "HarborPoint Medical Group",
			quote:
				"Plenar consolidated our fire safety, hygiene, and pest control under one contract. We reduced vendor-related incidents by 40% and cut weekly update meetings in half across our 23 facilities.",
			image: "/generated/image-confident-asian-woman-in-business-attire.webp"
		},
		{
			name: "Darnell Okafor",
			position: "Regional Operations Manager",
			company: "Simtra Retail Holdings",
			quote:
				"From fire alarm testing to washroom maintenance, Plenar gives us instant oversight across 87 locations. Real-time compliance tracking means we catch issues before they become problems.",
			image: "/generated/image-trustworthy-black-man-dressed-profession.webp"
		},
		{
			name: "Lina Chavez",
			position: "VP of Campus Services",
			company: "MetroEd Facilities Group",
			quote:
				"We consolidated 8 different service providers into 1 with Plenar and saved over $120,000 in the first year. Having fire safety, hygiene, and maintenance coordinated through one partner has been transformational.",
			image: "/generated/image-authoritative-latina-woman-in-elegant-bu.webp"
		}
	]}
/>

<Features
	title="Complete facility services under one contract"
	subtitle="From fire safety to hygiene management, we deliver consistent standards across all your locations"
	features={[
		{
			title: "Fire safety compliance and monitoring",
			description: "Comprehensive fire protection services including alarm testing, extinguisher maintenance, and emergency lighting checks. Stay audit-ready with automated compliance tracking and immediate alerts for any safety issues across all locations.",
			imageSrc: "/generated/image-a-professional-fire-safety-technician-in.webp"
		},
		{
			title: "Commercial hygiene and washroom services", 
			description: "Professional washroom maintenance, waste management, and hygiene supply services designed for high-traffic commercial environments. Maintain consistent cleanliness standards that protect your brand reputation and employee satisfaction.",
			imageSrc: "/generated/image-a-commercial-cleaning-professional-in-a-.webp"
		},
		{
			title: "Integrated pest control programs",
			description: "Proactive pest monitoring and treatment programs tailored to your industry requirements. Prevent infestations before they start with regular inspections, targeted treatments, and detailed reporting across all sites.",
			imageSrc: "/generated/image-a-professional-pest-control-specialist-i.webp"
		},
		{
			title: "Preventive maintenance scheduling",
			description: "Scheduled maintenance programs that prevent costly breakdowns and extend equipment life. Our predictive approach reduces emergency repairs and keeps your facilities running smoothly with minimal disruption.",
			imageSrc: "/generated/image-a-diverse-facility-maintenance-team-work.webp"
		},
		{
			title: "Real-time compliance tracking and reporting",
			description: "Centralized dashboard providing instant visibility into compliance status, service completion, and audit readiness across all locations. Generate comprehensive reports for stakeholders and regulatory requirements with one click.",
			imageSrc: "/generated/image-an-operations-manager-in-a-modern-office.webp"
		},
		{
			title: "Multi-site service coordination",
			description: "Seamless coordination of all facility services through a single point of contact and unified management system. Scale operations efficiently while maintaining consistent service quality and reducing administrative overhead.",
			imageSrc: "/generated/image-a-facility-services-coordinator-in-a-bri.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction />
