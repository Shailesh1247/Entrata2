It is maven project having base, configuration, pages and utilities pakages in src/main/java
Testcases package in src/test/java
testng.xml file is in src/test/resources
Testcases having two classes: Home page and Take the tour page.
8 test cases in home page, 2nd test cases is set enabled=false (It is for broken links).
10 test cases in Take the tour page.
Project is able to run by "Run as TestNG Suite" as well as "mvn verify" both.

In a home page: Test 1 verify home page url of entrata.
Test 2  verify broken links (which is set enabled=false).
Test 3 verify product list.
Test 4 verify products range.
Test 5 verify property management products.
Test 6 verify marketing and leasing products.
Test 7 verify Accunting.
Test 8 verify Utilities.
Test 9 verify All Solutions.

In a Take the tour page: Test 1 verify take the tour button which open new url.
Test 2 verify entered data in first name text field.
Test 3 verify entered data in last name text field.
Test 4 verify entered data in email text field.
Test 5 verify entered data in company name text field.
Test 6 verify entered data in phone text field.
Test 7 verify selected data from unit count dropdown field.
Test 8 verify entered data in title text field.
Test 9 verify selected data in demo request dropdown field.
Test 10 verify watch demo button click functionality.

For test data, i used methods in dummytestdata class in utilities package. It creates new data each and every time, while execution. Test data is not repeated.
Extent report is used for reporting part. It attached screenshot for failed test case along with test case.
Screen recorder is also used to capture complete video.
WebDriverListener and ITestListener is used in utilities.
Browser factory is used in utilities.

