@Test. Verify the title
- Open the home page - eBay.com(setup in config file)
- Get the title through the title() method
- Verify the title through the compareText method(custom assertion)

@Test. Search item
- Open the home page - eBay.com(setup in config file)
- Type some text into the search field, for example: 'Pixel 7'
- Click the search button
- Filtering through 'Storage Capacity' by the '256 GB' option
- Select the item by the index from the ribbon after filtering
- Verify through the compareText method(custom assertion) that the name of the item contains the search input text
  
@Launch against
- Windows 11. Chrome Desktop
- Android: Chrome mobile. Device Pixel 7
- IOS: Mobile Safari. Device iPhone 13 Pro Max

@Reporter
- Allure

@Auto-formatting tool
- ESLint

@Private properties
- Added
