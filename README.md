# SENG365 SoapUI Tests

Simple tests for the SENG365 assignment using SoapUI

## Description

Hopefully fairly comprehensive tests for the SENG assignment.
Note that this doesn't test the photos endpoints at all, you'll have to manually test that yourself.
I take no responsibility for any tests the grading checks that I don't ;)

## Getting Started

### Dependencies

* SoapUI or SoapUI Pro, download [here](https://www.soapui.org/downloads/latest-release.html) for any platform
* The tests file in the base directory of this repo

### Running tests

* Install SoapUI
* Launch SoapUI
* File -> Import Project. Select the test file
* In the navigator sidebar, right click the AuctionAPI tests (the one with the four squares for an icon)
* Select Show TestSuite Editor
* Ensure your server is running locally on port 4941
* Click the green run. This will execute all tests

## Check failed tests

If a test fails, double click the endpoint to open the specific tests for that endpoint.
You can now see each test. Double click again any red test steps to open that test.
Expand the lower portion of the new window that shows the Assertions.
You can see exactly what failed in the assertions there.
You can re run a specific endpoint by clicking the run button within that endpoint specifically, but you should not re run a single test, as it may rely on a cleared database, which is only done at the start of each endpoint.

## Authors

Jack Steel - jes143

## Version History

* 0.1
    * Initial Release