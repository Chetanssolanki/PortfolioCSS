<script>
	import ItemCard from './ItemCard.svelte';
	import AnimatedLink from './atoms/AnimatedLink.svelte';
</script>

<div class="projects md:space-y-2 mt-5">
	<ItemCard
		timespan="April 2023"
		href="https://github.com/Chetanssolanki/Chatbot"
		role="MEDBOT"
		short_desc="AI based Medical Assistant Chatbot"
		external_links={[
			{
				url: 'https://chetanssolanki.github.io/HospitalLandingPage/',
				label: 'Live Website'
			},
			{
				url: 'https://drive.google.com/file/d/1x0bwDovS7acIrfPvde0LK7TOvDAvZ0Tw/view?usp=drivesdk',
				label: 'NASA - Runner UP'
			}
		]}
		tags={['HTML', 'CSS', 'JavaScript', 'MySQL', 'Python']}
	>
		The MEDBOT project aims to develop an AI-based Medical Assistant Chatbot with an hospital
		website. It provides valuable assistance to doctors and patients by offering a user-friendly
		healthcare website interface. With machine learning techniques and healthcare datasets, it
		achieves an accuracy of 93% in understanding and responding to medical inquiries. The
		application's robust architecture is built using the Flask framework, allowing for seamless
		integration between the front-end and back-end components.
	</ItemCard>
	<ItemCard
		timespan="February 2020"
		href="https://ijsrd.com/Article.php?manuscript=IJSRDV7I110419"
		role="IoT-SWMS"
		short_desc="Smart Water Management System for Smart Cities"
		external_links={[
			{
				url: 'https://ijsrd.com/Article.php?manuscript=IJSRDV7I110419',
				label: 'Paper Published'
			}
		]}
		tags={[
			'IoT Development',
			'Sensor Integration',
			'Networking and Communication',
			'HTML',
			'CSS',
			'JavaScript',
			'MySQL',
			'Data Visualization',
			'System Integration'
		]}
	>
		The IoT-based Smart Water Management System aims to address the growing need for efficient water
		management in smart cities. By leveraging IoT technologies, the project focuses on monitoring
		and managing water resources effectively to ensure sustainability and optimize water usage. The
		system incorporates various sensors, communication protocols, cloud computing, and data
		analytics to provide real-time monitoring, early leak detection, and data-driven decision-making
		capabilities.
	</ItemCard>
	<!-- <ItemCard
		timespan="January 2022 - February 2022"
		href="https://github.com/Aunali321/torrent_scraper"
		role="Torrent Scraper"
		short_desc="a torrent scraper for 1337x."
		external_links={[
			{
				url: 'https://github.com/Aunali321/torrent_scraper',
				label: 'Torrent Scraper'
			},
			{
				url: 'https://github.com/webtorrent/webtorrent',
				label: 'WebTorrent'
			}
		]}
		tags={['Dart', 'WebTorrent', 'Web Scraping']}
	>
		Scrapes 1337x torrent site to get magnet links. Magnet links are then passed to <AnimatedLink
			href="https://github.com/webtorrent/webtorrent">WebTorrent</AnimatedLink
		>
		to download the file and stream it locally in VLC media player. It is built using Dart and WebTorrent.
		It is a CLI application.
	</ItemCard> -->
</div>
