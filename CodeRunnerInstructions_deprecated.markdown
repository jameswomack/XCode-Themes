#CodeRunner custom theme instructions

##I've requested Krill move the themes to the library folder but until that happens you'll need to go into the app bundle


* Right-click CodeRunner in the dock and select Options->Show In Finder
* Right-click CodeRunner in Finder and select Show Package Contents
* Navigate to Contents->Resources->Themes
* chmod Themes so that your user account can write to it. Command-I on the folder and change it in the info panel if you'd like
* Duplicate Coda.theme in the Themes folder and rename it whatever you'd like. Mine's called Darkolor.theme
* Open YOUR_FILE_NAME.theme in Property List Editor and change the HEX colors as desired. 
* Open or Restart CodeRunner
* Go to Preferences->General->Color Theme and select your new theme
* ???
* Oh yeah!