# ✅ STLC

![](<.gitbook/assets/image (4).png>)

1.Requirement Analysis-> Gathering all the necessary details about the product or the feature that you are requested to build.

2.Test Planning -> Very important phase in STLC.

#### :thinking:What is Test Plan and how to create Test plan?

1. Will be created by the Higher officials ie Test lead or some senior qa
2. Relates to all the testing activities and which needs to be done to deliver a quality product.

Notes:

1. What needs to be tested.
2. What cannot be tested.
3. Tools used for testing, Environments/Infrastructure needs for testing.
4. Staffing and Training needs
5. Testing Duration
6. Risks and contingencies plan

3.Test case development-> Create TCs in all aspects and also create test data eg. Login credentials.

4\. Test environment setup ->&#x20;

For example: Dev deploy code to Dev Environment, ie. Code is pushed into Dev server + database.&#x20;

When the user hits the url(which has one dedicated url) then the required data or page is displayed to the Dev.



Same in case of** QA Environment. **

For example: QA deploy code to QA Environment, ie. Code is pushed into QA server + database.&#x20;

When the user hits the url(which has one dedicated url) then the required data or page is displayed to the QA for testing purpose.



#### Drawbacks:

For example: 2 Dev are developing 2 different features

Dev A develop feature XYZ.

Dev B develop feature ABC.

Dev A completed and pushes its code to QA env.

Build is given to QA to test.

Now, Dev B completed and pushes his changes to QA env.

Which results in overlapping the code done by Dev A.

To avoid this multiple QA environments can be created.

#### Requirement Traceability Matrix (RTM)

Each TC that was developed should be mapped to the requirements of the feature. This is done during the TC development phase.

5.Test execution -> Once after getting the build, utilize the TCs designed and carryon the testing.

If bug is found, then inform the Dev.

6.Test closure -> This phase is done after the product is delivered.

* To check if all the TCs designed are executed successfully.
* Handover test artifacts (Waterfall model) -> In the case of Automation , to provide the necessary req. for the onsite people to run the app in order to check the maintenance.
* Project Retrospective
* Archive Test work products -> save the test plan/test data. Here TC plan means tomorrow for reference if to check what that particular feature was designed as per the requirement.

{% file src=".gitbook/assets/stlc-converted.pdf" %}
