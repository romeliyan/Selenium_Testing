Using Chrome or Firefox extension (The Selenium-IDE), Create a new project by specifying a project name. (Ex. ProjectAssignment4). Link to the https://gtmetrix.com/ URL and write the
test scripts using collection of test cases according to the below requirements.

1.When you are in record mode, navigate to https://gtmetrix.com/

  On the Web Application do the following:
  Click on Blog link
  Assert the Text “GTmetrix Performance Blog”.
  Verify the Text “New SSL Timing in Waterfall Chart, Capacity Upgrades, and Other Updates”
  Stop the record and run the Test Script, Save the test case as TestCase_001.

  Edit above recorded script according client requirements (SRS), “Whew! A lot of general improvements a maintenance was completed in this release.” Text should be changed as “General improvements and
  maintenance were completed in this release.”

  Open the above recorded script and record next test step as assert fail for above text series
  and change value according to the client request.

  After that Verify element present GTmetrix logo is present.

  Run the Test Script and see the execution. After that save the script.

2.Open new TestCase_002

  When you are in record mode, navigate to https://gtmetrix.com/ . Click on Blog link, Assert the Text “GTmetrix Performance Blog” and Stop the record and run the Test Script, Save the test
  case as TestCase_002.

  According client requirements (SRS), id=post-8769 post missing under the id=post-8768.

  Open the above recorded script and record next test step as verify element fail for id=post-8769.

  After that Verify element present GTmetrix logo is present. Run the Test Script and see the execution. After that save the script.


3.Open new TestCase_003

 Link to the http://book.theautomatedtester.co.uk/ and move to the Chapter 1 page on the site.

 Click on one of the elements on the page that has the text Click this link to launch another window. This will cause a small window to appear.

 Verify the text in the popup by right-clicking and selecting VerifyText id=popup Text within the popup window.

 Once the window has loaded, click on the Close the Window text inside it.
 
 Add a verify command for Beginners Guide title on the page. Save the test case.