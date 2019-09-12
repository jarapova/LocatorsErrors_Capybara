# LocatorsErrors_Capybara
https://docs.google.com/spreadsheets/d/1x2mwodQNhiS3vL5xeYL1rC5IAwLQVHuj1Gb53y89Buc/edit#gid=0



# TA locator is invalid.	"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Capybara-RSpec.git""
2. Run ""rspec spec/test_scenario/initial_locator_with_invalid_TAname.rb"""	
* Expected error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names.	
* Actual error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names.
#Element was not found on the page by initial locator.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Capybara-RSpec.git""
2. Run ""rspec spec/test_scenario/initial_locator_not_exist_on_use_page.rb"""	
* Expected error: NOT_FOUND	
* Actual error: Element 'Zachet:Zachet_Div_Initial' was not found in database. Please provide a selector to find and initialize element.
# Initial locator is invalid.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Capybara-RSpec.git""
2. Rub ""rspec spec/test_scenario/ta_locator_with_invalid_initial_locator.rb"""	"
* Expected error:
1) Expected error: Unable to find visible css ""span[@class='RveJvd snByac']__ta__taName__ta__""
2) Expected error: Unable to find visible css "".RveJvd snBya__ta__taName__ta__""
3) Expected error: Unable to find visible css ""//identifierId__ta__taName__ta__""
4) Expected error: Unable to find visible css ""//Справка__ta__taName__ta__"""	"
* Actual error:
1) Actual error: Unable to find visible css ""span[@class='RveJvd snByac']__ta__taName__ta__""
2) Actual error: Unable to find visible css "".RveJvd snBya__ta__taName__ta__""
3) Actual error: Unable to find visible css ""//identifierId__ta__taName__ta__""
4) Actual error: Unable to find visible css ""//Справка__ta__taName__ta__"""
# Element was not found on the page by TA locator.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Capybara-RSpec.git""
2. Run ""rspec spec/test_scenario/ta_locator_in_database.rb"""	
* Expected error: NOT_FOUND	
* Actual error: Element 'Translate:Rus1' was not found in database. Please provide a selector to find and initialize element.
# TA locator was not found in database.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_Capybara-RSpec.git""
2. Run ""rspec spec/test_scenario/ta_locator_not_in_database.rb"""	
* Expected error: NOT_FOUND	
* Actual error: Element 'SmartLocator:Not_in_the_database' was not found in database. Please provide a selector to find and initialize element.
