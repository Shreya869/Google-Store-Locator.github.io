<!DOCTYPE html>
<html>
    <head>
        <title>Google Maps Store Locator</title>
        <script src="https://kit.fontawesome.com/c939d0e917.js"></script>
    <link rel="stylesheet" href="style/style.css"
    </head>
    <body>

<div class="title">Store Locator</div>
<div class="search-container">
    <div class="search">
        <input id="zip-code-input" type="text" placeholder="Enter zip">
        <i class="fas fa-search"></i>
    </div>
</div>
<div class="store-list-container">
    <div cass="store-list">
        <div class="store-container">
            <div class="store-container-background">
                <div class="store-address">
                   <span>257 S. La Cienega Blvd.</span>
                   <span>Beverly Hills, CA 90211</span>
                </div>        
            <div class="store-phone-number"></div>
            <div class="store-number-container">
                <div class="store-number ">1</div>
            </div>
            </div>
        </div>

    </div>
</div>
<!-- This div is whats going to store the actual Map-->      
<div id="map"></div>

<script src="js/store-data.js"></script>

<script src="js/index.js"></script>



<script async defer
src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCplOrBWSAYp9RDROfEgdfYHBDHGKKwPOg&callback=initMap">
</script>

    </body>
</html>
