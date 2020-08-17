<script>
	import Header from './components/Header.svelte'
</script>

<style>

</style>

<div class="bg-gray-100">
	<Header />

	<main class="mt-10">
		<div class="px-4">
			<h1 class="mx-5 text-center text-gray-800 text-2xl font-bold leading-snug">
				<span class="inline-flex relative">
					<span class="absolute inset-0 bg-indigo-600" style="transform: skewY(-.5deg) scaleX(1.05)"></span>
					<span class="text-white relative">Pays for itself</span>
				</span>
				<span class="ml-1">in happier, more productive engineers</span> 
			</h1>

			<p class="mb-10">71% of our customers say adopting Tuple increased their pairing frequency.</p>
			
			<div class="px-4 pt-6 pb-4 mb-5 bg-indigo-600 text-white text-center rounded-lg shadow-lg">
				<h3 class="text-xl">Engineering Teams</h3>
				<div class="my-6 pb-6 flex justify-center items-center border-b border-indigo-500">
					<strong class="text-6xl font-bold leading-none">$25</strong>
					<span class="ml-3 text-left text-sm leading-tight">
						per user<br>
						per month
					</span>
				</div>

				<ul class="text-left">
					<li class="flex items-center mb-2">
						<svg viewBox="0 0 20 20" fill="currentColor" class="check-circle w-6 h-6"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
						<span class="ml-2 text-sm leading-none">
							Unlimited pairing sessions
						</span>
					</li>
					<li class="flex items-center mb-2">
						<svg viewBox="0 0 20 20" fill="currentColor" class="check-circle w-6 h-6"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
						<span class="ml-2 text-sm leading-none">
							Pair with external collaborators for free
						</span>
					</li>
				</ul>

				<a class="block py-3 mt-5 bg-indigo-500 font-semibold text-sm rounded shadow-md border-t border-indigo-400" href="#">Start 14-day free trial</a>
			</div>
			
			<div>
				<h3>Enterprises</h3>
				<div>
					<strong>$600</strong>
					<span>
						per user<br>
						per month
					</span>
				</div>

				<ul>
					<li>
						<svg viewBox="0 0 20 20" fill="currentColor" class="check-circle w-6 h-6"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
						Single sign-on (SSO)
					</li>
					<li>
						<svg viewBox="0 0 20 20" fill="currentColor" class="check-circle w-6 h-6"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
						Custom contracts
					</li>
					<li>
						<svg viewBox="0 0 20 20" fill="currentColor" class="check-circle w-6 h-6"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
						Payment via invoice/PO
					</li>
				</ul>
				<a href="#">Read More Details</a>
			</div>

		</div>
	</main>
</div>