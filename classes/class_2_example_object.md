# **Classes, Objects, Attributes and Methods**


**Object Name:**  MamaVivaldis

**Attributes:**

- locations ("Sheboygan", "Denver", "Montreal")
- menuItems ("Lobster", "Veal", "Lasagna")
- qualityRating (4.5)
- valetService (false)

**Method Results:**

- determineLocation (location)
==> Sheboygan
- haveLobster (menuItems.includes?)
==> true
- callValet (valetService == false)
==> false "Sorry, this service is not available"
- updateDailySpecial (menuItems << "Meatloaf")
==> "Lobster", "Veal", "Lasagna", "Meatloaf"
