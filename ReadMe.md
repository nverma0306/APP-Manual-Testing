# Assignment
N26 Manual Test Plan/Test Cases

### Objectives:
1. To write the TestPlan/Testcases for the Monify app on iOS Device. 
2. The test cases has to be written to achieve the aim of maximum coverage. 
3. The test cases have to be prioritized according to business impact

### Application Under Test:
Application Under test(AUT) is a app which is used for tracking the incomes & expenses. The app is available on both iOS & Android phones. We will test the app on iOS device iPhone 6S.

### TestPlan :
The Test Plan details out the different types of testing that would be performed for the AUT. Each type of testing is discussed in detail below. Each Testing type have test cases which are required to perform particular type of testing. Each test cases have priority in terms of business impact of the test case.

***NOTE: Testcases for features which are available only in Pro version of app are not written here except few security testcases.***

The different types of testing for which test cases are written are:-
1. Installation Testing
2. Interupt Testing
3. Network Testing
4. Performance Testing
5. APP Integration Testing
6. User Interface(UI) Testing
7. Usability Testing
8. Security Testing
9. Functional Testing

    A. Verification on Using Month & Cash filter
    B. Verification on Using Month & Payment card filter
    C. Verification on Using Month & All Accounts filter

    D. Verification on Using Week & Cash filter
    E. Verification on Using Week & Payment card filter
    F. Verification on Using Week & All Accounts filter

    G. Verification on Using Day & Cash filter
    H. Verification on Using Day & Payment card filter
    I. Verification on Using Day & All Accounts filter

    J. Verification on Using Year & Cash filter
    K. Verification on Using Year & Payment card filter
    L. Verification on Using Year & All Accounts filter

    M. Verification on Using Choose Date & Cash filter
    N. Verification on Using Choose Date & Payment card filter
    O. Verification on Using Choose Date & All Accounts filter

    P. Verification of trasfer functionaility from Cash to Payment Card
    Q. Verification of transfer functionality from Payment Card to Cash
    R. Verification of transfer functionality from Cash to Cash(Negative Scenario)
    S. Verification of transfer functionality from Payment card to Payment 
card(Negative Scenario)

    T. Verification of Settings functionalities

    U. Verification of Data backup functionalities

### 1. Installation Testing:
TC_01-->User should be able to install the app successfully (High Priority)
TC_02-->User should be able to uninstall the app successfully (High Priority)
TC_03-->User should be able to install & then uninstall and again install the app successfully (Low Priority)

### 2. Interupt Testing:
***A. Scenarios during incoming & outgoing calls***
TC_01-->Verify that the application should not freeze, when incoming call comes in when the app is being used and user should be able to continue using app after incoming call is completed (High Priority)
TC_02-->Verify that the application should not freeze, when outgoing call has to be made in between the app use and user should be able to continue using app after outgoing call is completed (High Priority)
TC_03-->Verify that the application data shouldn't be lost, when incoming call comes in when the app is being used and user should be able to continue using app after incoming call is completed (High Priority)
TC_04-->Verify that the application data shouldn't be lost, when outgoing call has to be made in between the app use and user should be able to continue using app after incoming call is completed (High Priority)

***B. Scenarios during incoming & outgoing messages***
TC_01-->Verify that the application should not freeze, when incoming message comes in when the app is being used and user should be able to continue using app after incoming message is recieved/read/replied (High Priority)
TC_02-->Verify that the application should not freeze, when outgoing message has to be sent in between the app use and user should be able to continue using app after outgoing message is sent (High Priority)
TC_03-->Verify that the application data shouldn't be lost, when incoming message comes in when the app is being used and user should be able to continue using app after incoming message is recieved/read/replied (High Priority)
TC_04-->Verify that the application data shouldn't be lost, when outgoing message has to be sent in between the app use and user should be able to continue using app after outgoing message is sent (High Priority)

***C. Scenarios during popup alerts***
TC_01-->Verify that the application should not freeze, when popup alert comes in when the app is being used and user should be able to continue using app after popup alert is handled (Medium Priority)
TC_02-->Verify that the application data shouldn't be lost, when pop up alert comes in when the app is being used and user should be able to continue using app after popup alert is handled (Medium Priority)

***D. Scenarios during notifications***
TC_01-->Verify that the application should not freeze, when notification comes in when the app is being used and user should be able to continue using app after notification is closed (Medium Priority)
TC_02-->Verify that the application data shouldnt be lost, when notificaion comes in when the app is being used and user should be able to continue using app after notification is closed (Medium Priority)

***E. Scenarios during low power***
TC_01-->Verify that the application should work as intended, when phone has low power (High Priority)
TC_02-->Verify that the application data shouldnt be lost, when phone has low power (Low Priority)
TC_03-->Verify that the application should work as intended, after the phone has switched off because of low power (High Priority)
TC_04-->Verify that the application data shouldnt be lost, when phone has restarted because of low power (High Priority)

***F. Scenarios during application automatic updates***
TC_01-->Verify that the application should not freeze, when app gets automatically updated when the app is being used and user should be able to continue using app after app is updated (Low Priority)
TC_02-->Verify that the application data shouldn't be lost,when app gets automatically updated when the app is being used and user should be able to continue using app after app is updated (Low Priority)

### 3. Network Testing
***A. Scenarios during poor network***
TC_01-->Verify that the application shouldn't become unresponsive and should behave as intended, when the internet network connectivity is low (High Priority)
TC_02-->Verify that the application data should save as usual,when the internet connectivity is low (High Priority)
TC_03-->Verify that the application shouldn't become unresponsive and should behave as intended, when the internet network connectivity fluctuates (Medium Priority)
TC_04-->Verify that the application data should save as usual,when the internet connectivity fluctuates (High Priority)

### 4. Performance Testing
***A. Responsiveness***
TC_01-->Verify that the application should be responsive as per SLAs (High Priority)
TC_02-->Verify that the application should open up quickly after being launched (Medium Priority)
***B. Speed***
TC_01-->Verify that the application can be accessed at good speed as per SLAs defined (High Priority)
TC_02-->Verify the speed of application on different devices with different memory parameters. (High Priority)
***C. Battery Utilization***
TC_01-->Verify that the application shouldn't exhaust phone battery at fast pace  (High Priority)
***D. CPU Utilization***
TC_01-->Verify that the application shouldn't overuse CPU (High Priority)

### 5. APP Integration Testing
***Application Integration***
TC_01-->Verify that the application should interact seamlessly with other applications on the phone or browser like banking apps when interacting with them (High Priority)

### 6. User Interface(UI) Testing
***A. Color & Logo***
TC_01-->Verify the logo or the name of the application is displayer correctly(High Priority)
TC_02-->Verify the color coding of the application(Low Priority)
a. Verify that New Expense icon is in red color.
b. Verify that New Income icon is in gree color.
c. Verify that base color of the application is light green color
TC_03-->Verify that the app filters, logo, transfer icon and right side panel icon doesn't overlap with phone inbuilt icons like battery, time, operator name, network strength etc.(Low Priority)
TC_04-->Verify that on selection of different filters the particular selected filter becomes green in color.(Low Priority)
TC_05-->Verify that on selection of accounts filters the particular selected filter becomes green in color.(Low Priority)
TC_06-->Verify that the balance if in positive is shown in green color.(Low Priority)
TC_07-->Verify that the balance if in negative is shown in red color. (Low Priority)
TC_08-->Verify that all categories on the wheel have different color than other categories(Medium Priority)

### 7. Usability Testing
***A. General usability Scenarios***
TC_01-->Verify that different categories can be clearly seen on low screen resolution(Low Priority)
TC_02-->Verify that the navigation is easy in the app between different filters and options(Medium Priority)
TC_03-->Verify that the application button, texts are readable and clearly visible(Medium Priority)
TC_04-->Verify that the application gives fast feedback to user if the feature is not available in free version(Low Priority)

***B. Graceful Exit***
TC_01-->Verify that application displays proper error message and should exits gracefully in case of any error situations (Medium Priority)

### 8. Security Testing
TC_01-->Verify that user payment data is kept secure when buying Pro version. (High Priority)
TC_02-->Verify that application requires authentication(in Pro version) (High Priority)
TC_03-->Verify that the application automatically gets locked upon continuously entering invalid credentials (in Pro version) (High Priority)

### 9. Functional Testing
***NOTE: In order to start with funtional testing, test data should be created so that different functionalities can be verified***

***NOTE: Below mentioned are the test scenarios or high level test scenario/usecase structure. This structure would be used to further write the Test cases.***

***A. Verification on Using Month & Cash filter***
***B. Verification on Using Month & Payment card filter***
***C. Verification on Using Month & All Accounts filter***

***D. Verification on Using Week & Cash filter***
***E. Verification on Using Week & Payment card filter***
***F. Verification on Using Week & All Accounts filter***

***G. Verification on Using Day & Cash filter***
***H. Verification on Using Day & Payment card filter***
***I. Verification on Using Day & All Accounts filter***

***J. Verification on Using Year & Cash filter***
***K. Verification on Using Year & Payment card filter***
***L. Verification on Using Year & All Accounts filter***

***M. Verification on Using Choose Date & Cash filter***
***N. Verification on Using Choose Date & Payment card filter***
***O. Verification on Using Choose Date & All Accounts filter***

***P. Verification of trasfer functionaility from Cash to Payment Card***
***Q. Verification of transfer functionality from Payment Card to Cash***
***R. Verification of transfer functionality from Cash to Cash(Negative Scenario)***
***S. Verification of transfer functionality from Payment card to Payment card(Negative Scenario)***

***T. Verification of Settings functionalities***

***U. Verification of Data backup functionalities***

***A. Verification on Using Month & Cash filter(Choose cash when adding income or expense***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and cash filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***B. Verification on Using Month & Payment card filte(Choose card when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***C. Verification on Using Month & All income filter(Choose payment card/cash when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***D. Verification on Using Week & Cash filter(Choose cash when adding income or expense***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and cash filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***E. Verification on Using Week & Payment card filte(Choose card when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***F. Verification on Using Week & All income filter(Choose payment card/cash when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***G. Verification on Using Day & Cash filter(Choose cash when adding income or expense***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and cash filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***H. Verification on Using Day & Payment card filter(Choose card when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***I. Verification on Using Day & All income filter(Choose payment card/cash when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***J. Verification on Using Year & Cash filter(Choose cash when adding income or expense***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and cash filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***K. Verification on Using Year & Payment card filter(Choose card when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***L. Verification on Using Year & All income filter(Choose payment card/cash when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***M. Verification on Using Choose Date & Cash filter(Choose cash when adding income or expense***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and cash filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***N. Verification on Using Choose Date & Payment card filter(Choose card when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***O. Verification on Using Choose Date & All income filter(Choose payment card/cash when adding expense or income***
TC_01-->Verify that user is able to select from ***left panel, the month filter  and payment card filter*** and income, expense and balance data are filtered accordingly on main page in circle and inside circle. Balance is clearly visible in balance field. Also month and balance type are clearly visible on top of main page(High Priority)

TC_02-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***income type as Salary***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_03-->On main page, click on  "New Income", user should ***NOT be able to add the negative amount  as new income amount*** by using subtract.(High Priority)

TC_04-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as Deposits***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_05-->On main page, click on  "New Income", user should be able to add the new income amount(net income amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to ***add the income type as savings***, and verify that income is added on main page inside the circle and balance is correctly shown inside the circle and in balance field.(High Priority)

TC_06-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Bills***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_07-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Car***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_08-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Clothes***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_09-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Communications***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_10-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Eating out***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_11-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Entertainment***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_12-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Food***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_13-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Gifts***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_14-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Health***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_15-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as House***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_16-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Pets***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_17-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as sports***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_18-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Taxi***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_19-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Toiletry***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_20-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add the ***expense type as Transport***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_21-->On main page, click on  "New Expense", user should be able to add the new expense amount(net expense amount added should be positive)by using add/subtract/multiply/division. User should be able to comment and user should be able to add more ***expense type in any category again***, and verify that expense, category and percentage of expense/income are clearly visible on circular chart and total expense, income, net balance amount are clearly visible inside the circle and balance is correctly shown inside the  balance field.(High Priority)

TC_22-->On main page, click on  ***summary icon on main page*** to see list of income and expense. Verify that correct income type and amount, correct expense type and amount are visible. Verify that expense are visible in red color and income in green color.(High Priority)

***P. Verification of trasfer functionaility from Cash to Payment Card***
TC_01->Verify that user is able to transfer the funds from cash to payment card and add note by using transfer icon on top right side.(High Priority)

TC_02->Verify that user is able to transfer the funds from cash to payment card and add note by using transfer icon from extreme right to icon(Others).(High Priority)
***Q. Verification of transfer functionality from Payment Card to Cash***
TC_01->Verify that user is able to transfer the funds from Payment card to cash and add note by using transfer icon on top right side.(High Priority)

TC_02->Verify that user is able to transfer the funds from payment card to cash and add note by using transfer icon from extreme right to icon(Others).(High Priority)

***R. Verification of transfer functionality from Cash to Cash(Negative Scenario)***
TC_01->Verify that user is NOT able to transfer the funds from cash to cash and add note by using transfer icon on top right side.(Low Priority)

TC_02->Verify that user is NOT able to transfer the funds from cash to cash and add note by using transfer icon from extreme right to icon(Others).(Low Priority)

***S. Verification of transfer functionality from Payment card to Payment card(Negative Scenario)***
TC_01->Verify that user is NOT able to transfer the funds from payment card to Payment card and add note by using transfer icon on top right side.(Low Priority)

TC_02->Verify that user is NOT able to transfer the funds from payment card to Payment card and add note by using transfer icon from extreme right to icon(Others).(Low Priority)

***T. Verification of Settings functionalities***
TC_01->Verify that user is able to select the ***First day of the week*** as particular day and same day appears when data is added/viewed using corresponding filter(High Priority)

TC_02->Verify that user is able to select the ***First day of Month*** as particular day and same day appears when data is added/viewed using corresponding filter(High Priority)

TC_03->Verify that user is able to click on ***review the application***. This should take user to app store and user should be able to review the application successfully(High Priority)

TC_04->Verify that user is able to click on ***export to file***. This should take user to Export to file page. User should be able to select ***Delimiter character as comma*** and ***decimal separator as decimal point*** and save the file to desired folder(High Priority)

TC_05->Verify that user is able to click on ***export to file***. This should take user to Export to file page. User should be able to select ***Delimiter character as semicolon*** and ***decimal separator as decimal point*** and save the file to desired folder(High Priority)

TC_06->Verify that user is able to click on ***export to file***. This should take user to Export to file page. User should be able to select ***Delimiter character as comma*** and ***decimal separator as decimal comma*** and save the file to desired folder(High Priority)

TC_07->Verify that user is able to click on ***export to file***. This should take user to Export to file page. User should be able to select ***Delimiter character as semicolon*** and ***decimal separator as decimal comma*** and save the file to desired folder(High Priority)

***U. Verification of Data backup functionalities***
TC_01->verify that user is able to click create the backup and save the back successfully and proper message should be shown to user(Medium Priority)

TC_02->verify that user is able to click restore data and save the data should be restored successfully and proper message should be shown to user(Medium Priority)

TC_03->verify that user is able to click clear data and data should be cleared successfully and all data should get resetted and proper message should be shown to user(Medium Priority)























