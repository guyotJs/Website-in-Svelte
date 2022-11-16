<script>

</script>
<style>
	blue{
		color: blue;
	}
	.grid-container {
			display: grid;
			gap: 0px;
			grid-template-columns: auto auto;

			padding: 10px;
			width: 300px;
			height: 250px
	}

	.grid-item {
			margin: 10px;
			background-color: #0d161d;
			border: 0px solid #0d161d;
			padding: 20px;
/* 			font-size: 30px; */
			text-align: center;
			border-radius: 25px;
	}
	.grid-item-white {
			margin: 10px;
			background-color: #ffffff;
			border: 0px solid #0d161d;
			padding: 20px;
			font-size: 30px;
			text-align: center;
			border-radius: 25px;
	}
	.hv{
		background-color: #0d161d;
		transition: 0.3s; 
	}
	.hv:hover{
		background-color: #182835;
	}
	.hv-white{
		background-color: #ffffff;
		transition: 0.3s;
	}
	.hv-white:hover{
		background-color: #858585;
	}
	p{text-size: 10px;}
	h1{text-size: 30px;}
	div{text-size: 10px;}
	a{text-decoration: underline;color:#bfc2c7;}
</style>
<main>
	<div class="grid-container" style="margin-left: 80px;">
		<div class="grid-item hv"><blue><h1>12%</h1></blue>Complete<br/>Working on emulators!<br/><img src="./duck.png" alt="" height="0" width="200"/></div>
		<div class="grid-item-white hv-white"><img src="https://classicmc-studios.github.io/guyot/duck.png" alt="duck"/></div>
		<div class="grid-item hv">
			<p>
				Welcome to<br/><em>Guyot</em><br/>The plateau of the<br/><b>Chromebook</b><br/><img src="https://classicmc-studios.github.io/guyot/comp.png" alt="computer"/>
			</p>
		</div>
		<div class="grid-item hv"><h1>Info</h1><p>This website is open source!</p><p>Help us <a href="https://github.com/guyotJs/guyotJs.github.io">improve</a></p></div>
	</div>
</main>