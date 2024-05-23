Components added:
Classes -  
  fetchClass - controller class for taskmanager which retrieves and updates the task owned by current user
  WeatherAppController - controller class for WeatherApp which dynamically retrieves the real time weather condition based on longitude and latitude of location - selct location field
flexipages-
  Location record page - added the weatherapp component on location record page
  Sales home page- added the taskmanager component on home page for sales app
LWC-
  weatherApp - retreives the longitude and latitude of location object record and displays the weather
  taskManager- displays the task owned by the currently logged in user and allows them to update inline for status field
Objetcs-
  Location__c - newly created object for saving the location
RemoteSiteSettings-
  weatherApp remote site - contains the URL for openweatheapp api
Static Resource-
  weatherAppIcons - used in weatherApp
