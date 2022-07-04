<script context="module">
	import { getLeagueStandings, getLeagueUsers } from '$lib/utils/helper';

    export async function load() {

		const standingsData = getLeagueStandings();
		const usersData = getLeagueUsers();
	
		return {
			props: {
				standingsData,
				usersData,
			}
		};
	}
</script>

<script>
	import { Standings } from '$lib/components'

	export let standingsData, usersData;
</script>

<style>
	.holder {
		position: relative;
		z-index: 1;
		text-align: center;
	}
	.standings {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
	}
</style>

<div class="standings">
	<p>
		<a href = "https://docs.google.com/spreadsheets/d/1Pa8a-XfLJ0OwoVeE1l5DMFiK8Pv1z8HzUmiRn-Pi8rQ/edit?usp=sharing">Link to Roulette Standings</a>
	</p>
	<p>
		<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS106eSbm5q9GRkNQgZGE_KKfEwzFauiETdzEvOpOL1BxcvjqLhLYGuAAXYqrCLHw5zCastgEIRR7Is/pubhtml?gid=1501533110&amp;range=A1:AH13&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
	</p>
</div>


<div class="holder">
	<Standings {standingsData} {usersData} />
</div>
