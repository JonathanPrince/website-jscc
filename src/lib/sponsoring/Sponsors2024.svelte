<script lang="ts">
	import alm from './sponsors-2024/alm-logo-2022.svg';
	import deno from './sponsors-2024/deno-logo.svg';
	import inovex from './sponsors-2024/inovex-logo.png';
	import jambit from './sponsors-2024/jambit.svg';
	import maibornwolff from './sponsors-2024/maibornwolff.svg';
	import peerigon from './sponsors-2024/peerigon.svg';
	import projectLary from './sponsors-2024/project-lary.svg';
	import saab from './sponsors-2024/saab.svg';
	import satellytes from './sponsors-2024/satellytes-blue.svg';
	import tng from './sponsors-2024/tng.png';
	import Sponsors from './Sponsors.svelte';
	const sponsors = [
		{
			image: alm,
			link: 'https://alm.sh',
			name: 'alm engineering',
			sponsoring: '500 €'
		},
		{
			image: deno,
			link: 'https://deno.land',
			name: 'deno',
			sponsoring: 'Stickers'
		},
		{
			image: inovex,
			link: 'https://inovex.de',
			name: 'inovex',
			sponsoring: 'Lunch'
		},
		{
			image: jambit,
			link: 'https://jambit.com',
			name: 'jambit',
			sponsoring: '500 €'
		},
		{
			image: maibornwolff,
			link: 'https://maibornwolff.com',
			name: 'maibornwolff',
			sponsoring: 'Location'
		},
		{
			image: peerigon,
			link: 'https://peerigon.com',
			name: 'peerigon',
			sponsoring: 'Coffee / Barista'
		},
		{
			image: projectLary,
			link: 'https://project-lary.com',
			name: 'project lary',
			sponsoring: 'Beverages'
		},
		{
			image: saab,
			link: 'https://www.saab.com',
			name: 'Saab AB',
			sponsoring: 'Breakfast'
		},
		{
			image: satellytes,
			link: 'https://www.satellytes.com/',
			name: 'Satellytes Digital Consulting',
			sponsoring: 'T-Shirts'
		},
		{
			image: tng,
			link: 'https://www.tngtech.com/',
			name: 'TNG Technology Consulting',
			sponsoring: 'Lunch'
		}
	];
</script>

<Sponsors title="A big thanks to our 2024 sponsors" {sponsors} />
