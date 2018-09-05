<template>
	<div class="modal-header">
		<h2>Modal Header</h2>
		<button class="modal-close-btn" @click="$emit('close')">
			<i class="fa fa-times" aria-hidden="true"></i>
		</button>
	</div>

	<div class="modal-body">
		<p class="modal-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
			quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
			consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
		cillum dolore eu fugiat nulla pariatur.</p>
	</div>

</template>