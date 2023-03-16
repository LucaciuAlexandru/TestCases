# TestCases
Below are some Test Case samples that I wrote.

--------------

**Description:**
Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to site.com/login
2. Add correct user/pass
3. Click Login button

**Expected Result:**
User should be able to login.

**Test Data:**
User: test
Pass: 123


---------------

**Description:**
Test the login by using incorect credentials.

**Steps to reproduce:**
1. Go to site.com/login                                                       
2. Add incorrect user/pass
3. Click Login button

**Expected Result:**
User should not be able to login. An error message should appear.

**Test Data:**
User: test
Pass: 1234567


-----------------

**Description:**
Test the login without using credentials.

**Steps to reproduce:**
1. Go to site.com/login
2. Do not add credentials
3. Click Login button

**Expected Result:**
User should not be able to login. An error message should appear.


------------------

**Description:**
Test that the correct results are displayed.

**Steps to reproduce:**
1. Go to site.com/search
2. Type valid term: " professional services"
3. Press Enter button

**Expected Result:**
User should be able to see relevant items that match the keyword.


-------------------

**Description:**
Test if the search turns up any results when using an invalid term.

**Steps to reproduce:**
1. Go to site.com/search
2. Type invalid term: " zzzzzzzzz"
3. Press Enter button

**Expected Result:**
User should see an Error message.


---------------------

**Description:**
Test if autocomplete text added on search or not.

**Steps to reproduce:**
1. Go to site.com/search
2. Type keyword: " professional "
3. Observe if autocomplete text is shown

**Expected Result:**
User shoud see autocomplete text. 
