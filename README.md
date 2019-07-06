# SlaveHack2_cheat


# Dependencies:     
1.Python 3.6.X (or later)
2.Selenium      
3.numpy     
4.requests      
# Installation      
1.Install python 3.6.X (or later)      
2.Type in cmd pip3 install selenium       
3.Type in cmd pip3 install numpy             
4.Type in cmd pip3 install requests     
# Configuration       
1.Find line:      
options.add_argument("user-data-dir=data-dir");  

2.Change data-dir to your google chrome profile folder.     
(It should be in "Local\\Google\\Chrome\\User Data\\Default") 

4.Find line     
browser = webdriver.Chrome("chromedriver-dir",chrome_options=options)       
5.Change chromedriver-dir to the Directory of your newly installed chromedriver (Directory should end in '/chromedriver.exe')       
(please check chromedriver-install for more info)
# Usage       
1.Run bot_SL2.py      
2.Wait for chrome to open (wait for page to fully load) then login to SlaveHack2           
3.Once logged in, wait 30 seconds     
4.Select your preffered option in CMD (make sure all in-game windows are closed)     
# WARNING (READ THIS)    
1.Close all windows before selecting any option
2.After the bot finishes it's task please close all windows before selecting another one

# Common Issues
If you get a unicode escape error put an 'r' before the directories you placed. for example (r'C:/etc/etc/file.txt')
If you get a chromedriver related error make sure your directory is correct (to check you can drag and drop the chromedriver.exe file into CMD and copy the result)      
