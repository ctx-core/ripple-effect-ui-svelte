<script context="module">
	import { ripple_effect__onclick } from '@ctx-core/ripple-effect'
	export { ripple_effect__onclick }
</script>

<script lang="ts">
	// See https://codepen.io/Craigtut/pen/dIfzv
</script>

<style>
	:global(.ripple) {
		overflow: hidden;
	}
	:global(.ripple-effect) {
		position: absolute;
		top: 0;
		left: 0;
		border-radius: 50%;
		width: 50px;
		height: 50px;
		background: white;
		opacity: 0.4;
		transform: scale(1);
		transition: all 2s;
	}
	:global(.ripple-effect.ripple-effect-start) {
		opacity: 0;
		transform: scale(100);
	}
</style>
