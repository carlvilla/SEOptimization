# SEOptimization
Website in which it was used Search engine optimization techniques

I. Our mini-site

We created a fictitious local business (Bagpipes Symphony) that manufactures different kinds of bagpipes, and offers other services such as bagpipe repairing or visits. This local business has a mini-site we used in this assignment: https://people.dsv.su.se/~cavi5720/bagpipes_symphony.html.

II. Page to optimize and search phrase
At the very beginning, we wanted to optimise the webpage https://people.dsv.su.se/~cavi5720/index.html  (after the optimization we changed it to https://people.dsv.su.se/~cavi5720/bagpipes_symphony.html ), and we wanted to do it for the search phrase “Scottish handmade bagpipes”. We evaluated each keyword separately on the website “ http://www.wordtracker.com/ ” by dividing the volume of each keyword by its competition. This is the result:

bagpipes  : 577 / 7,22 =  79.916897507 handmade  : 12443 / 19,41 =  641.061308604 Scottish  : 1196 / 21.14 =  56.575212867 Scotland  : 10150 / 31,18 =  325,529

As we said, we wanted to use the phrase “Scottish handmade bagpipes”. But we found out that the keyword “Scottish” is not as good as the keyword “Scotland”. Therefore, our final search phrase is “Handmade bagpipes Scotland”

III. Initial ranking
After finding the phrase we want to optimize our site for, we used SiteSeeker to index our pages. Given that our website doesn’t have a lot of pages, we index websites of our competitors. These are the used websites of our competitors:
- www.dunfion-bagpipes.co.uk
- www.gellaitrybagpipes.com
- www.ianmurray-bagpipes.co.uk
- www.bagpipebags.co.uk
Then we ran our phrase, and we found the page that we want to optimise in the position number 10 (“Home”).
        
IV. Optimization
A. Text optimization
In order to optimize our webpage, we started by using text optimization methods. These are the steps we followed :
1. First of all, we replaced the filename of the main page by “bagpipes_symphony”. We tried to do it by using a .htaccess, so when we search for  https://people.dsv.su.se/~cavi5720 , we would be redirected to the page bagpipes_symphony.html. However, we couldn’t do it because we always got the error message “Internal Server Error”, maybe due to the DSV server configuration. At the end, we simply changed the name of index.html to bagpipes_symphony.html.
2. The title of the page was changed to “Handmade Bagpipes from Scotland - Bagpipes Symphony”. We included in the title the keywords and the name of our fictitious business.
3. We added a few more keywords in the body of the HTML.
4. We changed the filenames and ALT-tag of the images:
a. The filename of the first image was renamed to “bagpiper_scotland” and its ALT-tag to
“Bagpiper in Scotland”.
b. The filename of the second image was changed to “black_hangmade_bagpipe” and its ALT-tag
to “Black handmade bagpipe”.
c. The filename of the third image was changed to “red_handmade_bagpipe” and its ALT-tag to
“Red handmade bagpipe”.
 
5. We did not change the heading because we considered that it was good enough (“Welcome to Bagpipe Symphony”).
6. We included some bold words and meta-description. This is the meta-description included :
<meta name="description" content="This is the website of Bagpipes Symphony. A handmade bagpipes company in Scotland since 1957">

B. Link optimization
To perform link optimization, we followed these steps:
1. We have a navigation bar in all the webpages of our mini-site where there is a link to our target page.
2. There is one page of our website that was ranked before the one that we want to optimise. In order not to pass Page Rank to that page, we used the attribute  rel=”nofollow” in the links to it.
3. We used Spamdexing to try to improve the ranking of our page. We have two options to perform this task. By hiding the text with the attribute  style=”visibility:hidden”, or we can also  put an image over the text , so the human visitors cannot see the text, but the crawler would take it into account. We decided to use the latter approach.
This is the list of keywords that we used, and we put them in a <div> tag with the attribute class=”Info”:  bagpipes, Scotland, Scottish, handmade, craftsman, England, pipe, bagpipe, Spain, Asturias, Germany,music,
quality, wood, orchestra, kilt, Scotland, bagpipes, handmade, UK, traditional, chanters, Gaita, smallpipes, säckpipa, Sweden We also added an image with  class=”handmade_bagpipe”, and the following lines in the file style.css to
cover the keywords with the image:
.info {position:absolute; top: 900px; z-index:1} .handmade_bagpipe {position:absolute; top: 900px; z-index:2}
4. Our mini website uses a navigation bar to move from one page to another. In the case of our target page, the link is called Home. To perform optimize link reputation we have to replace name of the link in the navigation bar in the other webpages by our search phrase (although, we wouldn’t do it in a real-life website for obvious esthetic reasons).

C. Connection to and from the outside world 1. From the outside world
We would like to obtain link from local business and from companies that could provide us the necessary materials for the bagpipes. For example, a local business that gives bagpipe lessons. So we search on Google “Bagpipe courses” and the first result was the website
http://www.thepipingcentre.co.uk/bagpipe-education . It would be really beneficial for our webpage a link from that website.
We also want links from material providers. For example, we found the website http://www.prosono.co.za/en/bagpipes-folkloric-instruments.shtml  by using the keywords “bagpiper wood provider”. At the time that we searched these keywords, the page was ranked third. So, it would be really beneficial for the Page Rank of our web page.
Given that we organise visits of our factory, we could have links from tourism agencies of Scotland (for example  https://scotland.nordicvisitor.com/  ) . Even if the website is not directly related to bagpipes, it's a trusted website.
The main goal is to obtain many links from as many different domains as possible (link diversity) that point deeply in our website, not only the main page (deep linking).

2. To the outside world
It’s good to link outside world website but these should be preferably be trusted website, deal with the same subject as our, has a top level domain...
We linked the Royal Scottish Pipe Band Association ( http://www.rspba.org/  ). A famous association that organises events related to bagpipes and we are their supposed providers.
We also added a link to a tourism of Scotland website ( https://www.visitscotland.com/about/uniquely-scottish/bagpipes-traditional-music-ceilidhs/  ) that deals with bagpipes events (concerts, festivals...) in Scotland.

V. Final indexing
After optimization, our website was ranked first in the SiteSeeker Search engine for the phrase “handmade bagpipes Scotland”. This not really surprising because, unintentionally, we chose a niche subject. Bagpipes are not common music instruments, therefore there are few manufacturers and sellers. Thus the competition is much less tough than with other subjects such as football for instance.
Now, our target website is in the first position of the list. Also the page “About” that was positioned above our target page disappeared. This is due to the attribute rel=”nofollow” that we used in the links to that page.
We can also see that the ranking of other pages of our website improved too (Positions 4, 5 and 6). This is because we created a link in each of those pages by using our search phrase. But we didn’t optimise those as much as our target page, so there are still pages of the competitors above them.
