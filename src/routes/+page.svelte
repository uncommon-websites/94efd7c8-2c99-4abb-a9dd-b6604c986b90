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
	title="Bold creative that scales with your brand"
	subtitle="We transform brand identities into collaborative systems that empower your team to execute with confidence and consistency."
	imageSrc="/generated/image-a-marketing-leader-thoughtfully-reviewin.webp"
	centered={false}
	callsToAction={[
		{
			href: "/contact",
			label: "Start a project"
		},
		{
			href: "/about",
			label: "Our approach"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/meta.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/tonal.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/quayaustralia.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/nordstrom.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Double Agency transforms brand identities into scalable creative systems for growth-stage marketing leaders. We partner with brands like Meta, Tonal, and Quay Australia to deliver not just beautiful design, but the tools and processes that empower your team to execute with confidence. From visual identity to marketing materials and immersive experiences, we build collaborative frameworks that grow with your business."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "VP of Marketing",
			company: "Bloom Naturals",
			quote:
				"Double Agency delivered a brand system that cut our creative turnaround time by 60%. Our team can now produce campaign assets in hours instead of weeks, and everything stays perfectly on brand.",
			image: "/generated/image-warm-editorial-style-environmental-portr.webp"
		},
		{
			name: "Marcus Williams",
			position: "Chief Marketing Officer",
			company: "Peak Performance Co",
			quote:
				"The comprehensive brand guidelines they created eliminated the risk of inconsistent messaging across our 12 retail locations. We finally have confidence that our brand shows up cohesively everywhere.",
			image: "/generated/image-warm-editorial-environmental-portrait-of.webp"
		},
		{
			name: "Sofia Rodriguez",
			position: "VP of Brand",
			company: "Haven Home Goods",
			quote:
				"Their implementation toolkit saved us over $85K in agency fees last year. Our in-house team can now execute professional-level creative independently, and we only bring in outside help for major launches.",
			image: "/generated/image-editorial-sunlit-portrait-of-a-confident.webp"
		}
	]}
/>

<Features
	title="How we partner with you"
	subtitle="Beyond deliverables, we build the systems and processes that empower your team to execute with confidence."
	features={[
		{
			title: "Collaborative creative process",
			description:
				"Full transparency into our design methodology using industry-standard tools. We work alongside your team, not in isolation, building trust through open communication and shared ownership."
		},
		{
			title: "Scalable brand systems",
			description:
				"Flexible visual identities designed to evolve with your business. We create comprehensive systems that adapt and grow, ensuring consistency across every touchpoint as you scale."
		},
		{
			title: "Implementation toolkits",
			description:
				"Customized resources that empower your team to iterate independently. From brand guidelines to template libraries, we equip you with everything needed for confident execution."
		},
		{
			title: "Strategic brand architecture",
			description:
				"Comprehensive strategies that ensure cohesive brand experiences. We go beyond visual identity to develop frameworks that maintain consistency across marketing, digital, and physical spaces."
		},
		{
			title: "Flexible engagement models",
			description:
				"Choose the partnership structure that fits your needs. Retainer relationships for ongoing support, project-based fees for defined scopes, or hourly flexibility for evolving requirements."
		},
		{
			title: "Long-term empowerment",
			description:
				"Training and ongoing support to maximize your investment. We ensure your team can maintain and iterate on designs for years, providing the knowledge transfer that creates lasting independence."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Ready to scale your brand with confidence?"
	subtitle="Start building systems that empower your team"
	description="Stop bottlenecking on external agencies. Partner with us to create collaborative brand systems that give your team the confidence to execute consistently—without sacrificing quality or creative vision."
	imageSrc="/generated/image-a-marketing-leader-sits-at-a-warm-wood-d.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Start a project",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn our process",
			variant: "secondary"
		}
	]}
/>
