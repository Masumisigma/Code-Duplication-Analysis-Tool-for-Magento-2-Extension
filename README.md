
# Marketplace Content for How to Use Code Duplication Analysis Tool for Magento® 2 

<h2>Introduction</h2>

Magento Official Marketplace is always trying to keep high standards of the quality of the products uploaded there and follow the best practices to keep it intact.
In due course, it follows EQP program strictly. Checking the quality of code of the products uploaded in the marketplace is one of the guidelines that Magento platform religiously follows.
Code duplication is one of the violations of the quality parameters, and Magento 2 extension developers are scrappy to know how to save from error generation notification and subsequent rejection of Magento 2 extension submission with following email content:

Code quality issues: CPD: This extension contains duplicated code.

<h6>Additional Comments:<h6>
UI/Component/Listing/Columns.php duplicates Magento 2's (module-catalog) version of the same file -- use ClassPreferences to avoid duplicating Magento's code.


Our Magento 2 extension development team also has faced the same issue several times. It has compelled us to find out a code duplication analysis program. Thus, we can find all instances of the duplicated code in the code documents of the Magento 2 extensions in question.
Unfortunately, the market was devoid of ready to use the script. Therefore, our hard working Magento 2 developers have developed a user-friendly tailor-made program to find the traces of any duplicate code existing in the Magento 2 extension, module, or code snippets uploaded along with extension package.
Our duplicate code analysis tool for Magento 2 extension is a highly simplified interface available 
<strong>A - Online</strong> as well as 
<strong>B - Working</strong> on your site / your server 
Anyone can use including tech-savvy Magento 2 extension owners as well as Magento 2 extension developers.

<h2>A. How to Use Tool Online</h2>

We have made the Code Duplication Analysis Tool for Magento 2 available online at:
http://codeanalysis.labs.mconnectmedia.com/
Please, visit our online/web interface and follow the required steps to get your Magento 2 extension code duplication analysis done.

<h4>Steps to Follow on Online Interface</h4>

<strong>Step – 1</strong>
Select Your Magento Version:
The tool is comparing the code of core Magento matching with your Magento version. Therefore, it is imperative for us to know your Magento version at first place.
So please provide exact Magento version for that you have developed the extension.

<strong>Step – 2a</strong>
After the selection of your Magento version, the next field input is uploading of extension zip that you want to check for the code duplication analysis using our interface.
Now, choose the zip file from your local machine and upload it to our server to run comparative analysis to find out the trace of any duplicate content in it.

<strong>Note:</strong> Remember, we have configured our server such a way that it avoids saving your extension file permanently and automatically delete it once the code duplication analysis process is accomplishing. 
Therefore, you need not worrying about misuse or theft of your precious extension code or any document belonging to the zip file. Thanks.

<img src="http://codeanalysis.labs.mconnectmedia.com/github/Step–2a.png" />
 
Or
<strong>Step – 2b</strong>
For those developers who would like to check the code of their extension directly, we have made provision in our online user interface to copy-paste the code and get an analysis done.

<strong>Note:</strong> Remember, it requires minimum 13 lines of code to run the module. Moreover, the developer needs to insert the code that begins with PHP tag and only PHP file is allowed, not .phtml or .html files.
In some cases, you may not find individual function. Therefore, for accurate results in analysis, the developer needs to insert the complete file code. Otherwise, uploading of the entire extension zip file is the best alternative.

<img src="http://codeanalysis.labs.mconnectmedia.com/github/Step–2b.png" />
 
Once you have done, please click on “BEGIN CODE AUDIT” button below it.

<strong>Examples of Expected Results</strong>
For the sake of comprehensibility, we have produced an example of expected results that may display in the format given below.

<img src="http://codeanalysis.labs.mconnectmedia.com/github/reports.png" />

If you face any issue using the tool online, please contact us for immediate help. Thanks.

<h4>B. How to Use Tool on Your Site</h4>
For frequent users and who would like to install the tools on own server, we have made provision for them too.
You can download the tool from GitHub repository.

GitHub repository link

<strong>Prerequisites </strong>
We have set following prerequisites to install the tool locally on your site or server, and those are:
1.	It needs PHP CPD installed on your server.
2.	It requires minimum Magento 2.x.x vanilla codebase to match with your current code.
Now, anyone can download it from the link given below.
Magento version download link

<h4>C. How to Install the Tool</h4>

Download the "Code Duplication Analysis Tool" source code to your local machine. You may find folder structure, as depicted below.

<img src="http://codeanalysis.labs.mconnectmedia.com/github/folder.png" />

<strong>Steps:</strong>
1.	First, download any Magento 2 version from - https://magento.com/tech-resources/download
2.	Now, extract it in the folder, and we suggest to use Magento 2 latest version. 
3.	In the extracted folder, create one more folder with name "codeduplication." 
4.	Now, place the "Code Duplication Analysis Tool" files in "codeduplication" folder.
 
Now you need to Magento 2 all versions zip file to run the tool. Thus, you must download all version zip file from here only - http://codeanalysis.labs.mconnectmedia.com/download.php
Or
You can download specific version zip only. Now, place the file in "Magento-versions" folder.
The next step is to assign 0777 permission to following folders 
<ul><li>"Magento-versions"</li>
<li>"reports" </li>
<li>	"vendor"</li></ul>
 
Navigate to the web browser and access the folder. 
You may have a display of the screen, as depicted in the above “Results” screenshot. 

Finally, you need to follow the same steps described for the online tool to find duplication in your Magento module.
If you face any issue using the tool offline/on-site, please <a href="https://www.mconnectmedia.com/contact">contact us</a> for immediate help. Thanks.

<h4>D. Services Come with the Tool</h4>
Apart from round-the-clock support by our technical and marketing teams, we provide additional services for personalization to offer exceptional user experiences and augment your branding.
<ul><li>	90 Days Free Support for Upgrade</li></ul>

<strong>Help Center<strong>
<ul><li>	Support team available for 24X7/365 to respond your queries regarding extension and our other products</li>
<li>	For faster responses to your queries and issues, we welcome you to take assistant of our ticketing system and get personalized solutions to your bespoke problem</li>
<li>	Please submit your tickets at https://support.mconnectmedia.com/hc/en-us.</li></ul>

<strong>Installation Support<strong>
It is our humble duty to enable you to accomplish extension installation successfully. In due course,
<ul><li>	We have provided a complete installation guideline using textual and visual content for better and quick comprehension. </li></ul>

<strong>Contact Us<strong>
M-Connect Media is one of the reputed and award-winning Magento development companies, and it is providing end-to-end ecommerce solutions on Magento® platform.
We have accumulated a pool of highly expert and experienced Magento talents in the form of ecommerce designers, programmers, QA team, and excellent marketers to provide full-cycle Magento ecommerce development services. 
If you are interested in our Magento extension products, please check it with a full range of various Magento versions including <a href="http://site.dev.mconnectmedia.com/magento-extensions">Magento® 1 Extensions</a> & <a href="http://site.dev.mconnectmedia.com/magento-2-extensions">Magento 2® Extensions</a> and many things more.
With around 700+ websites designed, and approx. 70+ Extensions developed in Magento® platform; we are a <a href="https://www.mconnectmedia.com/magento-extension-development/">leading Magento extension development company.</a>

<strong>Address:</strong> 353 McCook Cir NW, Kennesaw, Georgia 30144, United States

<strong>Web:</strong> www.mconnectmedia.com | <strong>E-Mail:</strong> cs@mconnectmedia.com 

<strong>Phone:</strong> +1 319 804-8627








