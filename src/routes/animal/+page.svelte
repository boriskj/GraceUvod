<script>
	let name = 'slon';
	let clicks = 0;

	function clicker() {
		clicks = clicks + 1;
	}
</script>

<div class="flex justify-center">
	<div
		class="grid justify-items-center bg-sky-200 rounded-2xl shadow-2xl m-40
"
	>
		<p
			class="
  text-center text-4xl"
		>
			{name} x {clicks}
		</p>
		<p class="italic text-2xl text-center">Elephantidae</p>
		<p class="text-center">
			Sloni so večja skupina sesalcev, ki tvorijo družina živali Elephantidae (sloni) v redu
			trobčarjev (Proboscidea). Danes so poznane tri živeče vrste, ki jim grozi izumrtje: afriški
			gozdni slon, afriški savanski slon in azijski slon (znan tudi kot indijski slon). Sloni živijo
			v podsaharski Afriki, Južni Aziji in Jugovzhodni Aziji. Družina Elephantidae (sloni) je edina
			preživela družina iz roda Proboscidea (trobčarji); ostali, danes izumrli, člani reda
			vključujejo dinoterije, gomfoterije, mamute in mastodone.
		</p>
		<img
			on:click={clicker}
			class="text-center rounded-xl p-10"
			src="//upload.wikimedia.org/wikipedia/commons/thumb/3/37/African_Bush_Elephant.jpg/220px-African_Bush_Elephant.jpg"
		/>
		<a class=" p-10 bg-blue-900 text-sky-200 rounded-3xl px-10 py-2 hover:bg-blue-400" href=""
			>POKAŽI VEČ</a
		>
	</div>
</div>
