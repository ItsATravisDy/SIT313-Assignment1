# SIT313-Assignment1
Hello this is awesome!
<!DOCTYPE html>
<html>
	<head>
		<meta name="viewport" content="width=device-width,height=device-height,initial-scale=1.0"/>
		<title>Fratelli Pizza e Pasta</title>    
		<link rel="stylesheet" href="themes/mytheme.min.css" />
		<link rel="stylesheet" href="themes/jquery.mobile.icons.min.css" />
		<link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" />
		<script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
		<script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
		<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
		<script src="https://maps.googleapis.com/maps/api/js?v=3.exp&sensor=false"></script>	
		<script>
			function initialize() {
				var mapProp = {
					center:new google.maps.LatLng(-38.151738, 145.152225),
					zoom:16,
					mapTypeId:google.maps.MapTypeId.ROADMAP
				};
				var map=new google.maps.Map(document.getElementById("googleMap"), mapProp);
			}
			google.maps.event.addDomListener(window, 'load', initialize);
		</script>
		
	</head>
	<body>
		<!--Start of First Page-->
		<div data-role = "page" id = "homepage"  data-theme = "c">
			<div data-role = "header">
				<h1>Fratelli Piiza e Pasta</h1>
			</div>
			<div data-role = "content" class = "content">
				<h2 align = "center">To navigate this website, please click on the following buttons.</h2>
				<a href = "#aboutpage" data-role = "button" data-icon = "arrow-r"
					data-iconpos = "right">About</a>
				<a href = "#menupage" data-role = "button" data-icon = "arrow-r"
					data-iconpos = "right">Menu</a>
				<a href = "#locationpage" data-role = "button" data-icon = "arrow-r"
					data-iconpos = "right">Location</a>
				<a href = "#developerpage" data-role = "button" data-icon = "arrow-r"
					data-iconpos = "right">Developer</a>
				<a href = "#feedbackpage" data-role = "button" data-icon = "info"
					data-iconpos = "left" data-rel = "dialog">Feedback</a>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		<!--End of first page-->
		
		<!--Start of Second Page-->
		<div data-role = "page" id = "aboutpage" data-theme = "c">
			<div data-role = "header">
				<a href = "#homepage" data-role = "button" data-icon = "home"></a>
				<h1>Fratelli Pizza e Pasta</h1>
			</div>
			<div data-role = "content">
				<img src = "images/fratelli.jpg" align = "right" height = "300" width = "375" />
				<b>Welcome to Fratelli Pizza e Pasta!</b>
				<p>We are a family owned resteraunt in Frankston Victoria who pride ourselves<br /> 
				in our fantastic food, reliable server and great prices!</p>
				
				<p><b><u>Opening Hours:</u></b><br />
				Monday: 11:00 - 22:00<br />
				Tuesday: 11:00 - 22:00<br />
				Wednesday: 11:00 - 22:00<br />
				Thursday: 11:00 - 22:00<br />
				Friday: 11:00 - 22:00<br />
				Saturday: 11:00 - 22:00<br />
				Sunday: 11:00 - 22:00</p>
				
				<p><b><u>Specials:</u></b><br />
				Monday - Friday: $10 Lunch Special<br />
				Monday: $10 Parma Night<br />
				Tuesday: $10 Steak Night<br />
				Wednesday: Kids Eat Free Night<br />
				Thursday: Seafood Night<br />
				
				<p>Feel free to get social with us!<br /></p>
				<a href = "https://www.facebook.com/FratelliPizzaPasta"><img src = "images/facebook.png" height = "25" width = "25" /></a>
				<a href = "https://www.twitter.com/FratelliPasta"><img src = "images/twitter.png" height = "25" width = "25" /></a>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		<!--End of Second page-->
		
		<!--Start of Third Page-->
		<div data-role = "page" id = "menupage" data-theme = "c">
			<div data-role = "header">
				<a href = "#homepage" data-role = "button" data-icon = "home"></a>
				<h1>Fratelli Pizza e Pasta</h1>
			</div>
			<div data-role = "content">
				<h2 align = "center">Menu</h2>
				<ul data-role = "listview">
					<li>
						<a href = "#appetisers" data-rel = "dialog">Appetisers</a>
					</li>
					<li>
						<a href = "#mains" align = "center" data-rel = "dialog">Mains</a>
					</li>
					<li>
						<a href = "#kids" align = "center" data-rel = "dialog">Kids</a>
					</li>
					<li>
						<a href = "#dessert" align = "center" data-rel = "dialog">Dessrts</a>
					</li>
					<li>
						<a href = "#drinks" align = "center" data-rel = "dialog">Drinks</a>
					</li>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		<!--End of third page-->
		
		<div data-role = "page" id = "appetisers" data-theme = "c">
			<div data-role = "header">
				<h1>Appetisers</h1>
			</div>
			<div data-role = "content">
				<ul data-role = "listview">
					<li>Garlic Bread</li>
					<li>Potato Wedges</li>
					<li>Bruschetta</li>
					<li>Oysters Natural</li>
					<li>Oysters Kilpatrick</li>
				</ul>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		
		<div data-role = "page" id = "mains" data-theme = "c">
			<div data-role = "header">
				<h1>Mains</h1>
			</div>
			<div data-role = "content">
				<ul data-role = "listview">
					<li data-role = "list-divider">Chicken</li>
						<li>Chicken Schnitzel</li>
						<li>Chicken Parmagiana</li>
						<li>Chicken Kiev</li>
						<li>Chicken and Mushroom Crepe</li>
						<li>Stuffed Chicken Breast</li>
						<li>Atlantic Pollo</li>
					<li data-role = "list-divider">Veal</li>
						<li>Veal Schnitzel</li>
						<li>Veal Parmagiana</li>
						<li>Veal Scallopine</li>
					<li data-role = "list-divider">Off The Grill</li>
						<li>Porherhouse Steak</li>
						<li>Rump Steak</li>
						<li>Reef 'n' Beef</li>
						<li>Greek Style Lamb</li>
						<li> Marinated Ribs</li>
					<li data-role = "list-divider">Seafood</li>
						<li>Beer Battered Flathead</li>
						<li>Garlic or Chilli Prawns</li>
						<li>Mornay Scallops</li>
						<li>Seafood Crepe</li>
						<li>Fishermans Basket</li>
				</ul>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		
		<div data-role = "page" id = "kids" data-theme = "c">
			<div data-role = "header">
				<h1>Kids</h1>
			</div>
			<div data-role = "content">
				<ul data-role = "listview">
					<li>Spaghetti Bolognese</li>
					<li>Chicken Nuggets and Chips</li>
					<li>Chicken Schnitzel and Chips</li>
					<li>Chicken Parmagiana and Chips</li>
					<li>Battered Fish and Chips</li>
				</ul>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		
		<div data-role = "page" id = "dessert" data-theme = "c">
			<div data-role = "header">
				<h1>Dessert</h1>
			</div>
			<div data-role = "content">
				<ul data-role = "listview">
					<li data-role = "list-divider">Cakes</li>
						<li>Please enquire about cakes that are available</li>
					<li data-role = "list-divider">Italian Ice Creams</li>
						<li>Baci</li>
						<li>Cassata</li>
						<li>Murray Mud</li>
						<li>Giandiuotto</li>
						<li>Tartufo</li>
						<li>Ice Cream Paw</li>
					<li data-role = "list-divider">From the Kitchen</li>
						<li>Chocolate Crepes</li>
						<li>Mixed Berry Crepes</li>
						<li>Chocolate Spring Rolls</li>
						<li>Nutella Pizza</li>
					<li data-role = "list-divider">Other Desserts</li>
						<li>Ice Cream Cone</li>
						<li>Waffle Cone</li>
						<li>Ice Cream Small Bowl</li>
						<li>Ice Cream Large Bowl</li>
						<li>Banana Split</li>
						<li>Chocolate Mousse</li>
				</ul>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		
		<div data-role = "page" id = "drinks" data-theme = "c">
			<div data-role = "header">
				<h1>Drinks</h1>
			</div>
			<div data-role = "content">
				<ul data-role = "listview">
					<li>
						<ul data-role = "listview">
							<li data-role = "list-divider">Red Wine</li>
								<li>Oxford Landing Shiraz</li>
								<li>Oxford Landing Merlot</li>
								<li>Oxford Landing Cabernet Sauvignon Shiraz</li>
								<li>Rymill MC2 Merlot</li>
								<li>Vasse Felix Shiraz</li>
								<li>Opawa Pinot Noir</li>
							<li data-role = "list-divider">White Wine</li>
								<li>Oxford Landing Chadonnay</li>
								<li>Oxford Landing Sauvignon Blanc</li>
								<li>Oxford Landing Pinot Grigio</li>
								<li>Opawa Sauvignon Blanc</li>
								<li>Angas Moscato</li>
								<li>Torres Moscato</li>
						</ul>
					</li>
					<li>
						<ul data-role = "listview">
							<li data-role = "list-divider">Beer - Local</li>
								<li>Broo</li>
								<li>Cascade Premium Light</li>
								<li>Carlton Draught</li>
								<li>Carlton Cold</li>
								<li>Crown Lager</li>
								<li>James Boags</li>
								<li>Pure Blonde</li>
								<li>Victoria Bitter</li>
							<li data-role = "list-divider">Beer - Imported</li>
								<li>Coors</li>
								<li>Heineken</li>
								<li>Peroni Nastro Azzuro</li>
								<li>Sapporo</li>
								<li>Stella Artois</li>
						</ul>
					</li>
				</ul>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		
		<!--Start of Fifth Page-->
		<div data-role = "page" id = "locationpage" data-theme = "c">
			<div data-role = "header">
				<a href = "#homepage" data-role = "button" data-icon = "home"></a>
				<h1>Fratelli Pizza e Pasta</h1>
			</div>
			<div data-role = "content">
				Note: If you are trying to load this page on a computer. It might not be able to load.
				<div id = "googleMap" style="width:500px;height:380px;"></div>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		<!--End of Fifth page-->
		
		<!--Start of Sixth Page-->
		<div data-role = "page" id = "developerpage" data-theme = "c">
			<div data-role = "header">
				<a href = "#homepage" data-role = "button" data-icon = "home"></a>
				<h1>Fratelli Pizza e Pasta</h1>
			</div>
			<div data-role = "content">
				<h1 align = "center">About the Developer</h1>
				<p>
					The developers name is Travis Dennington.<br />
					He is an IT student From Deakin University completing his Bachelor of IT degree.<br />
					He works part time at a Restaurant as well as Bunnings Carrum Downs.<br />
					His hobbies include:<br />
					Gaming<br />
					Coding<br />
					Anything IT related<br />
					
					If you wish to get into contact with him, please click <a href = "mailto:tdenning@deakin.edu.au">here</a>.
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		<!--End of Sixth page-->
		
		<!--Start of Seventh Page-->
		
		<div data-role = "page" id = "feedbackpage" data-theme = "c">
			<div data-role = "header">
				<h1>Feedback</h1>
			</div>
			<div data-role = "content">
				<form name="htmlform" method="post" action="contact_us.php">
					<label for="first_name">First Name *</label>
					<input  type="text" name="first_name" maxlength="50" size="30">
					<label for="last_name">Last Name *</label>
					<input  type="text" name="last_name" maxlength="50" size="30">
					<label for="email">Email Address *</label>
					<input  type="text" name="email" maxlength="80" size="30">
					<label for="telephone">Telephone Number</label>
					<input  type="text" name="telephone" maxlength="30" size="30">
					<label for="comments">Comments *</label>
					<textarea  name="comments" maxlength="1000" cols="25" rows="6"></textarea>
					<input type="submit" value="Submit">
				</form>
			</div>
			<div data-role = "footer">
				<h1><a href = "#developerpage">&copy; Travis Dennington</a></h1>
			</div>
		</div>
		<!--End of Seventh page-->
	</body>
</html>
