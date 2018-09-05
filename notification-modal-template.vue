<template>
	<div class="media notification-modal-media">
		<div class="media-left">
			<a href="#">
				<img class="media-object" src="images/default-img.png" alt="img tag">
			</a>
		</div>

		<div class="media-body">
			<span class="modal-date">
				<i class="fa fa-calendar-o" aria-hidden="true"></i> Jan 20 
				<i class="fa fa-clock-o" aria-hidden="true"></i> 2 days ago
			</span>
			<p>Enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip duis aute irure dolor in reprehenderit ex ea commodo
			consequat.</p>
		</div>
		
	</div>
	<button class="modal-close-btn" @click="$emit('close')">
		<i class="fa fa-times" aria-hidden="true"></i>
	</button>
</template>

<style type="text/css">
.modal-container {
	position: relative;
	width: 600px;
	margin: 0px auto;
	padding: 40px 90px 30px 30px;
	background-color: #fff;
	border-radius: 2px;
	box-shadow: 0 2px 8px rgba(0, 0, 0, .33);
	transition: all .3s ease;
	font-family: Helvetica, Arial, sans-serif;
}

.notification-modal-media .media-left {
	width: 100px;
	height: 100px;
	float: left;
	border-radius: 50%;
}

.notification-modal-media .media-left a {
	display: block;
}

.notification-modal-media .media-object {
	display: block;
	width: 100%;
	height: 100%;
	object-fit: contain;border-top: 
}


.modal-close-btn {
	position: absolute;
	top: 15px;
	right: 20px;
	background: #dedede;
	border: none;
	border-radius: 50%;
	width: 30px;
	height: 30px;
	cursor: pointer;
}

.modal-close-btn:hover {
	background: #363636;
}

.modal-close-btn:focus {
	outline: none;
}

.modal-close-btn .fa {
	color: #fff;
	font-size: 16px;
}

.modal-date {
	display: block;
	font-size: 12px;
	font-weight: 700;
	margin-bottom: 5px;
}

.modal-date i.fa.fa-clock-o {
	margin-left: 10px;
}
</style>