<script>
	import { Card, Img } from 'flowbite-svelte';

	let baseIconsURL = 'https://cdn.simpleicons.org/';
	let skillsWithIcons = [
		{
			name: 'HTML',
			icon: `${baseIconsURL}/html5`,
			site: 'https://html.com'
		},
		{
			name: 'CSS',
			icon: `${baseIconsURL}/css3`,
			site: 'https://www.css3.com'
		},
		{
			name: 'Javascript',
			icon: `${baseIconsURL}/javascript`,
			site: 'https://developer.mozilla.org/en-US/docs/Web/JavaScript'
		},
		{
			name: 'React',
			icon: `${baseIconsURL}/react`,
			site: 'https://react.dev'
		},
		{
			name: 'MongoDB',
			icon: `${baseIconsURL}/mongodb`,
			site: 'https://www.mongodb.com/cloud/atlas/lp/try4?utm_source=google&utm_campaign=search_gs_pl_evergreen_atlas_core_prosp-brand_gic-null_apac-in_ps-all_desktop_eng_lead&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=12212624347&adgroup=115749713423&cq_cmp=12212624347&gad=1&gclid=EAIaIQobChMItYHxzd7r_wIVI5lmAh0mwgcyEAAYASAAEgKX2PD_BwE'
		},
		{
			name: 'MySQL',
			icon: `${baseIconsURL}/mysql`,
			site: 'https://www.mysql.com'
		},
		{
			name: 'Amazon AWS',
			icon: `${baseIconsURL}/amazon`,
			site: 'https://aws.amazon.com'
		}
	];
</script>

<!-- Experience Card -->
<Card class="m-0 mt-10 p-5 mx-auto md:mx-0">
	<div class="heading flex">
		<svg
			class="w-6 h-6 mr-2 text-ctp-mauve"
			aria-hidden="true"
			fill="none"
			stroke="currentColor"
			stroke-width="1.5"
			viewBox="0 0 24 24"
			xmlns="http://www.w3.org/2000/svg"
		>
			<path
				d="M20.25 14.15v4.25c0 1.094-.787 2.036-1.872 2.18-2.087.277-4.216.42-6.378.42s-4.291-.143-6.378-.42c-1.085-.144-1.872-1.086-1.872-2.18v-4.25m16.5 0a2.18 2.18 0 00.75-1.661V8.706c0-1.081-.768-2.015-1.837-2.175a48.114 48.114 0 00-3.413-.387m4.5 8.006c-.194.165-.42.295-.673.38A23.978 23.978 0 0112 15.75c-2.648 0-5.195-.429-7.577-1.22a2.016 2.016 0 01-.673-.38m0 0A2.18 2.18 0 013 12.489V8.706c0-1.081.768-2.015 1.837-2.175a48.111 48.111 0 013.413-.387m7.5 0V5.25A2.25 2.25 0 0013.5 3h-3a2.25 2.25 0 00-2.25 2.25v.894m7.5 0a48.667 48.667 0 00-7.5 0M12 12.75h.008v.008H12v-.008z"
				stroke-linecap="round"
				stroke-linejoin="round"
			/>
		</svg>
		<h3 class="tracking-tight font-semibold text-gray-900 dark:text-ctp-mauve">Organizations</h3>
	</div>

	<a
		href="https://www.larsentoubro.com/"
		class="flex items-center mt-5 hover:bg-gray-100 dark:hover:bg-gray-700 p-3 rounded-md cursor-pointer hover:scale-[1.02] transition-transform ease-in-out duration-200"
	>
		<img
			class="w-12 h-12 mr-2 rounded-full"
			src="https://media.licdn.com/dms/image/C4D0BAQFnEYpR8MlYsA/company-logo_200_200/0/1519856125136?e=2147483647&v=beta&t=Fiq4QiduUmzpsqTXhDXJSXcdLCq9Z9HhB0YpQ215vDc"
			alt="L&T"
		/>
		<div>
			<h4
				class="text-lg font-medium tracking-tight text-gray-900 dark:text-white hover:text-latte-lavender dark:hover:text-mocha-lavender focus-visible:text-mocha-lavender pointer-events-none"
			>
				Larsen & Toubro
			</h4>
			<p class="text-sm font-normal tracking-tight text-gray-900 dark:text-white">Trainee Intern</p>
		</div>
	</a>

	<a
		href="https://aws.amazon.com"
		class="flex items-center hover:bg-gray-100 dark:hover:bg-gray-700 p-3 rounded-md cursor-pointer hover:scale-[1.02] transition-transform ease-in-out duration-200"
	>
		<img
			class="w-12 h-12 mr-2 rounded-full"
			src="https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg"
			alt="Cossale"
		/>
		<div>
			<h4
				class="text-lg font-medium tracking-tight text-gray-900 dark:text-white hover:text-latte-lavender dark:hover:text-mocha-lavender focus-visible:text-mocha-lavender pointer-events-none"
			>
				Amazon Web Services
			</h4>
			<p class="text-sm font-normal tracking-tight text-gray-900 dark:text-white">Intern</p>
		</div>
	</a>
</Card>
<!-- Education Card -->
<Card class="mt-5 mx-auto md:mx-0">
	<div class="heading flex">
		<svg
			class="w-6 h-6 mr-2 text-ctp-mauve"
			aria-hidden="true"
			fill="none"
			stroke="currentColor"
			stroke-width="1.5"
			viewBox="0 0 24 24"
			xmlns="http://www.w3.org/2000/svg"
		>
			<path
				d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5"
				stroke-linecap="round"
				stroke-linejoin="round"
			/>
		</svg>
		<h3 class="tracking-tight font-semibold text-gray-900 dark:text-ctp-mauve">Education</h3>
	</div>
	<div
		class="items-center mt-5 hover:scale-[1.02] transition-transform ease-in-out duration-200 hover:bg-gray-100 dark:hover:bg-gray-700 p-2 hover:rounded-md cursor-pointer"
	>
		<a
			href="https://slrtce.in"
			class="text-lg font-medium tracking-tight text-gray-900 dark:text-white hover:text-latte-lavender dark:hover:text-mocha-lavender focus-visible:text-mocha-lavender"
		>
			Bachelor of Information Technology
		</a>
		<p class="text-sm mt-1 font-normal tracking-tight text-gray-900 dark:text-white">
			Shree L.R. Tiwari College of Engineering, University of Mumbai - CGPA 9.0
		</p>
		<p class="text-sm mt-1 font-normal tracking-tight text-gray-700 dark:text-gray-300">
			2020 - 2023
		</p>
	</div>
</Card>
<!-- skills card -->
<Card class="mt-5 mx-auto md:mx-0">
	<div class="heading flex">
		<svg
			class="w-6 h-6 mr-2 text-ctp-mauve"
			aria-hidden="true"
			fill="none"
			stroke="currentColor"
			stroke-width="1.5"
			viewBox="0 0 24 24"
			xmlns="http://www.w3.org/2000/svg"
		>
			<path
				d="M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L6.832 19.82a4.5 4.5 0 01-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 011.13-1.897L16.863 4.487zm0 0L19.5 7.125"
				stroke-linecap="round"
				stroke-linejoin="round"
			/>
		</svg>
		<h3 class="tracking-tight font-semibold text-gray-900 dark:text-ctp-mauve">Skills</h3>
	</div>
	<div class="items-center mt-5">
		<!-- map skills and icons -->
		{#each skillsWithIcons as skill}
			<a
				href={skill.site}
				class="flex space-x-3 items-center hover:bg-gray-100 dark:hover:bg-gray-600 p-3 rounded-md cursor-pointer hover:scale-[1.02] transition-transform ease-in-out duration-200"
			>
				<Img src={skill.icon} alt={skill.name + ' logo'} class="h-8 w-8" />
				<h4
					class="text-base tracking-tight text-gray-900 dark:text-white hover:text-latte-lavender dark:hover:text-mocha-lavender focus-visible:text-mocha-lavender"
				>
					{skill.name}
				</h4>
			</a>
		{/each}
	</div>
</Card>
