<script lang="ts">
	let currentYear = new Date().getFullYear();
</script>

<div class=" bg-[#212121] py-12 px-4">
	<div
		tabindex="0"
		aria-label="footer"
		class="focus:outline-none mx-auto container flex flex-col items-center justify-center"
	>
		<div tabindex="0" aria-label="nobit logo" role="img">
			<p class=" text-gray-900 dark:text-white text-2xl font-bold">Nobit</p>
		</div>
		<div class="text-black flex flex-col md:items-center f-f-l pt-3">
			<h1 tabindex="0" class="focus:outline-none dark:text-white text-2xl font-semibold">
				Build. Review. Ship.
			</h1>
			<div class="md:flex items-center mt-5 md:mt-10 text-base text-color f-f-l">
				<h2 class=" md:mr-6 pb-4 md:py-0 cursor-pointer">
					<a
						class="focus:outline-none dark:text-white   focus:underline hover:text-gray-700"
						href="https://www.google.com" target="_blank" rel="external">Download Now</a
					>
				</h2>
				<h2 class="cursor-pointer">
					<a
						class="focus:outline-none dark:text-white focus:underline hover:text-gray-700"
						href="https://www.google.com" target="_blank" rel="external">License</a
					>
				</h2>
			</div>
			<div class="my-6 text-base text-color f-f-l">
				<ul class="md:flex items-center">
					<li class="md:mr-6 cursor-pointer pt-4 lg:py-0">
						<a
							href="https://www.google.com" target="_blank" rel="external"
							class="focus:outline-none dark:text-white  focus:underline hover:text-gray-500"
							>About
						</a>
					</li>
					<li class="md:mr-6 cursor-pointer pt-4 lg:py-0">
						<a
							href="https://www.google.com" target="_blank" rel="external"
							class="focus:outline-none dark:text-white  focus:underline hover:text-gray-500"
							>Features
						</a>
					</li>
					<li class="md:mr-6 cursor-pointer pt-4 lg:py-0">
						<a
							href="https://www.google.com" target="_blank" rel="external"
							class="focus:outline-none dark:text-white  focus:underline hover:text-gray-500"
							>Pricing
						</a>
					</li>
					<li class="md:mr-6 cursor-pointer pt-4 lg:py-0">
						<a
							href="https://www.google.com" target="_blank" rel="external"
							class="focus:outline-none dark:text-white  focus:underline hover:text-gray-500"
							>Careers
						</a>
					</li>
					<li class="md:mr-6 cursor-pointer pt-4 lg:py-0">
						<a
							href="https://www.google.com" target="_blank" rel="external"
							class="focus:outline-none dark:text-white  focus:underline hover:text-gray-500"
							>Help
						</a>
					</li>
					<li class="cursor-pointer pt-4 lg:py-0">
						<a
							href="https://www.google.com" target="_blank" rel="external"
							class="focus:outline-none focus:underline dark:text-white hover:text-gray-500"
							>Privacy Policy
						</a>
					</li>
				</ul>
			</div>
			<div class="text-sm text-color mb-10 f-f-l">
				<p tabindex="0" class="dark:text-white focus:outline-none">
					© {currentYear} Nobit. All rights reserved
				</p>
			</div>
		</div>
		<div class="w-9/12 h-0.5 bg-gray-100 dark:bg-gray-700 rounded-full" />
		<div class="flex justify-between items-center pt-12">
			<a
				href="https://www.google.com" target="_blank" rel="external"
				class="hover:shadow-lg mr-4 focus:outline-none rounded-md focus:ring-2 focus:ring-offset-2 focus:ring-gray-600"
				aria-label="download on the app store"
				><div class="">
					<img
						src="https://tuk-cdn.s3.amazonaws.com/can-uploader/simple_center_aligned_with_logo-svg2.svg"
						alt="download on the app store"
					/>
				</div>
			</a>
			<button
				class="hover:shadow-lg focus:outline-none rounded-md focus:ring-2 focus:ring-offset-2 focus:ring-gray-600"
				aria-label="get it on google play"
			>
				<div>
					<img
						src="https://tuk-cdn.s3.amazonaws.com/can-uploader/simple_center_aligned_with_logo-svg3.svg"
						alt="get it on google play"
					/>
				</div>
			</button>
		</div>
	</div>
</div>
