# sitemap-generator
A simple python script to generate sitemap.xml

<h1>
  Web Crawling With Python
</h1>
<h3>
  Web crawling is a powerful technique to collect data from the web by finding all the URLs for one or multiple domains. Python has several popular web crawling libraries and frameworks.
</h3>

<p>
This is a Python script that generates a sitemap for a given website. A sitemap is an XML file that lists all the URLs for a website and is used by search engines to understand the structure of a website and how to crawl its pages.
<br>
The code imports the sys and logging modules and the crawler function from the pysitemap library.
<br>
The main logic of the script is contained within an if __name__ == '__main__': block, which specifies that this code should only be executed if the script is run as the main program (and not imported as a module).
<br>
The first step in the main block is to check if the command line argument --iocp is present. If it is, the script imports the events and windows_events modules from the asyncio library, removes the --iocp argument from sys.argv, and sets up the ProactorEventLoop to be used with the asyncio library.
<br>
Next, the script sets the root_url variable to 'https://example-website.com'. This URL is passed as the first argument to the crawler function, along with the out_file argument, which specifies that the sitemap should be saved to a file named sitemap.xml in the current working directory.
<br>
The crawler function generates the sitemap and saves it to the specified file, and the script terminates.
</p>


