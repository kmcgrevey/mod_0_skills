# **Classes, Objects, Attributes and Methods**

## **Restaurant**

**Object Name:**

- MamaVivaldis

**Attributes:**

- location ("Sheboygan", "Denver", "Montreal")
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
- dailySpecial (menuItems << "Meatloaf")
==> "Lobster", "Veal", "Lasagna", "Meatloaf"
