# DTT project

DTT project is an online test application, written using Ruby on Rails

Submitted by: DTT team

URL: 

## User Stories

As a user,
  [Authentication]
    * [ ] User can sign in/up.
    * [ ] User can sign out.
    * [ ] User can sign in/up using Facebook (optional).
    * [ ] After signing up, user will recieve a welcome email (optional).
  
  [User profile]
    * [ ] Users can view their profile and other users' profile (excluding sensitive information in public view).
    * [ ] Users can see about how many tests they created.
    * [ ] Users can see about how many tests they took.
    * [ ] Users see all activities that they did in the system.
    * [ ] Users can see number of followings and followers, and see the list.
    * [ ] Edit personal information.
    * [ ] Change password.
  
  [Test]
    * [ ] User can see list of test in home page.
    * [ ] User can filter test using category.
    * [ ] User can filter test using level of difficulty.
    * [ ] User can filter test using tags (optional).
    * [ ] User can click on test title to go to test info page.
    * [ ] In test info page, user can see some information about this test including: title, category, level of difficulty, number of question, time, description, best scorers, "take this test" button.
    * [ ] User can click "take this test" button to go to test page listing test questions.
    * [ ] In test page, there is a count down timer and list of MCQ questions and answers and a "submit" button.
    * [ ] User can finish this test by click "submit" button.
    * [ ] When time passes, auto submit.
    * [ ] After submission, user is redirected to test result page.
    * [ ] In test result page, user can see his/her result, and his/her absolute ranking among those who take this test.
    * [ ] In test result page, user can see list of questions with correct answer and suggestions.
    * [ ] In test result page, there is a text input for user to give review about the test.
    * [ ] In test result page, user can share his/her result to Facebook.
    * [ ] User can follow other users.
    * [ ] User can follow tags. Tests having tags that user is following will be priotized when listing.
    * [ ] User can search for test in home page. Keyword will be searched in test title & description.
  
  [Contribution]
    * [ ] User can create test.
    * [ ] Add questions, options, correct answers, and suggestions (if needed).
    * [ ] User can see all test he/she contributed.

As a test,
  * [ ] Must belongs to a category.
  * [ ] Can has many tags (optional).
  * [ ] Has level of difficulty.
  * [ ] Some detail such as: number of question, time.

As a system,
  * [ ] List most active users in home page.
  * [ ] Automatically send email result of all tests user has done and has a criticize for each one every month (optional).
  * [ ] Send email notification to user if system has new test in the tag which user has followed before (optional).
  * [ ] May be send result to user after each test (optional).

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

![Video Walkthrough](walkthrough.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## License

    Copyright [2016] [DTT team]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.