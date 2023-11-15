<template>
    <header>
		<div class="flex">
			<img src="@/assets/imgs/icon_wb.gif" />

			<img src="@/assets/imgs/default/back.jpg" />

			<button type="button"><img src="@/assets/imgs/theatre_lights_icon.png" />Administration</button>
		</div>
		<nav>
			<ul class="flex justify-center">
				<li>
					<a href="#"><img src="@/assets/imgs/user.png" /><span>Home</span></a>
				</li>
				<div>
					<!-- Déroulant, à tester avec cette structure -->
					<li>
						<img src="@/assets/imgs/commu.png" /><span>Communauté</span>
					</li>
					<ul class="hidden">
						<li>Articles</li>
						<li>Équipe</li>
					</ul>
				</div>
				<li>
					<a href="#"><img src="@/assets/imgs/topme.gif" /><span>Sécurité</span></a>
				</li>
				<li>
					<a href="#"><img src="@/assets/imgs/support.gif" /><span>Support</span></a>
				</li>
			</ul>
		</nav>
	</header>
</template>