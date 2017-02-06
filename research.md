# RESEARCH

You need to be logged in to the app to follow this! Your event co-ordinators should have given you instructions about how to get an invite; or look in your event-specific repo (usually named "DataRescuePLACENAME") within this github organization.

## Step 1: Claiming a dataset to research

As soon as they're seeded by the seeding group, URL's get added to the [Data rescue Archivers App](https://www.archivers.space). "Research" is the first phase of this process. Scroll or search through the list for a URL that seems appropriate (to your area of expertise, topical focus of the day's event, etc.). Make sure the URL has not been "checked out" by anyone else -- the `user` field should be blank.

Click on the `URL` field to inspect the URL & learn enough about it to answer the questions in this section. Click on the `UUID` field to be brought to the app's record page for that URL, click the large blue `Checkout this URL` button, and begin working.

## Step 2: Doing the research!

1. `Purpose/Significance of data`. Use this field to describe, as best you can, what the data on this page is for, and what makes it significant. If you don't know that much about the topic area, do your best. You should at lest be able to broadly describe the kind of dataset it is. 
1. `Do not harvest`. Check this box if you think the seeder made an error, and that the data on this page is easily crawlable by the Internet Archive, **and also** has no particular intrinsiv calue as a separate collection. See [these](https://docs.google.com/document/d/1PeWefW2toThs-Pbw0CMv2us7wxQI0gRrP1LGuwMp_UQ/edit)
and
[two documents](https://docs.google.com/document/d/1qpuNCmBmu4KcsS_hE2srewcCiP4f9P5cCyDfHmsSAVU/edit) for more info on the IA webcrawler. 
1. `Page contains dynamic content (e.g., links loaded by JavaScript).` Click this box if page content is generated within the browser environment by some kind of web application.  
1. `Page contains interactive visualizations.` Click this box for complex UI such as maps, etc.
1. `Data is accessible in structured file(s) that can be directly downloaded.` Click this box for document collections, etc.
1. `Data is accessible over FTP.` Click this box to remove the URL from the workflow, and send it to the Internet Archive for their FTP crawl.
1. `Data is accessible using a documented public API.` Describe API parameters if you can easily do so
1. `Data is only accessible using search queries in a web form.` Self-explanatory...
1. `Recommended Approach for Harvesting Data`. Add any recommendations for harvesting methods; see [the harvesting tools repo](https://github.com/edgi-govdata-archiving/harvesting-tools/) for some examples. 
1. `File Formats`. Self-explanatory
1. `Estimated size in MB` If you can estimate, do so.
1. `Link Url`. This is cool. Sometimes a few, or even a large number, of URL's have been nominated spearately, but are really windows onto the same dataset. We want to scrape *all* of this data, and do it *exactly one time*. The `Link URL` field lets uou add a pattern to match on; all matching uRL's will now become part of a single record.

## Step 3: Marking Done, Saving the Record, Checking out

when you'refinished, mark the research as complete by clicking the grey checkbox on the same line as the "Research" section heading. Press the blue `Save` button at the bottom, and if you are not proceeding to harvest the data, the blue `Checkin this URL` button near the top of the page.
