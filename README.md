# Rugby-Super-League-Scrape
Scraping Rugby Super League data from superleague.com using Python

The Python script is in two sections, the first section should be run as normal. The second section needs to be edited for your own use using these steps:

  1. Find the load_match_stats.php from inspecting the element for a given match report

  2. Right-click on the file and select copy as cURL (if there are two options for copy as cURL, use copy as cURL bash)

  3. Go to https://curlconverter.com/ and paste into the box to return an output

  4. Copy the cookies section from the curl converter website and replace the cookies section in the python script using the copied section

  5. Copy the headers section from the curl converter website and replace the headers section in the python script using the copied section, but remove the referrer line as well as the things in #

  6. Everything should run smoothly from now on

The output from the second section was cleaned in Alteryx for personal use.

