# Spider_Emptor

# Spider_Emptor  Description:
For the following site: https://www.federalreserve.gov/start-job-search.htm create a spider that can be executed from command line, takes an input, returns all items and can accept the following arguments: 1) No argument 2) Keyword 3) Job category   
# Example:  
           $ scrapy crawl fed_reserve_jobs -a keywords=”python” -a category=”Security”  

# Requirements:  
1) Python3 : https://www.python.org/download/releases/3.0/ 
2) scrapy : https://doc.scrapy.org/en/latest/index.html 
3) selenium : https://www.seleniumhq.org/ 
4) chromedriver : https://sites.google.com/a/chromium.org/chromedriver/downloads (I have included it in the github repository) 
5) chrome browser :  https://www.google.com/chrome/?brand=CHBD&amp;gclid=Cj0KCQjwqsHWBRDsARIsALPWMEP8-46FmPDLE9gBiYsTppV9xIV1Btf0DetnKEcKTY9KiwxMei08d0QaArEeEALw_wcB  

# How to run: 
1) install latest Chrome Browser 
2) install python3 and the modules required: scrapy and selenium 
3) open the terminal in the location "*\emptor\tutorial\spiders"
4) run the spider using " scrapy crawl fed_reserve_jobs *...* "

# Note[1]: 
The ChromeDriver should work on it's own, if the error - " PATH NOT FOUND" comes then please follow the steps given below:
1) download the chrome driver using the above link, and copy it's path to the "chrome_path" variable and retry!
2) if that still does not work, add the path of the Chrome Browser and the chromeDriver to the environments path variable.
https://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/amp/
https://www.windows-commandline.com/set-path-command-line/
# please restart the system after doing so and then re-run!

# Note[2]:
If the program gives incorrect output:
1) re-run the program and check again.
2) if it still gives you the incorrect output, then delete the pycache folder present in emptor\tutorial\spiders

# Note[3]: 
3 Files are added in the locaton : emptor\tutorial\spiders as soon as you run the program. 
1) search_queries.txt: stores the input details and the result line.
2) iframe_src.html: the final html response
3) output_data.txt: stores the scraped data in an orderly manner. 
