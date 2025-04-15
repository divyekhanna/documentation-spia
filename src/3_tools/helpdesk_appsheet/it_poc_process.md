# IT POC Process

## Definitions:
* Helpdesk - an internal tool used by Sadhanapada Indian Applications for managing requests between the team members.
* IT POC – nodal person in the Sadhanapada Indian Applications team responsible for interacting with the Sadhanapada tech team and backend IT team for tech issues.
* Sadhanapada Tech team – facilitation team for Sadhanapada Indian Applications and backend IT team
* Backend IT team – IT team responsible for making any backend changes, fixes or enhancements.
* Applicant Nurturing Team – The representatives responsible for receiving incoming calls and emails as well as making outgoing reminder calls to the participants in the Sadhanapada Indian Applications team.

## Process 1 - Email ID Update Post All-set

This process is used when a participant wants to update their Sadhanapada registered primary email address in Sadhaka after their profile is marked all-set.

1.	Go to: <https://ishaprofile.ishafoundation.org/support/tickets/new>
2.	Raise an Email Change ticket
3.	Before submitting the ticket, take a screenshot.
4.	After submitting the ticket, You will receive a ticket number in your email.
5.	Please wait for 2 working days for the request to get processed.
6.	If it is unresolved, please share the ticket number and screenshot with us.

## Process 2 – Applications IT Requirements - Login Issues

This process addresses any issues being faced by individual participants concerning not being able to log in to their SP Portal.

1.	The participant calls the Sadhanapada Helpline or writes an email to sadhanapada@sadhguru.org explaining the login issues that they are facing.
2.	The incoming calls or emails representative shares the relevant set of standard troubleshooting instructions with the participant. These can include trying incognito mode, explicitly typing URLs instead of clicking the email links, trying to log in via email instead of phone number, etc.
3.	If the issue persists, the Nurturing team raises a ticket on Helpdesk.
4.	The IT POC updates the relevant details on the “Applications IT Requirements 24-25” Google Sheet “Login issues” tab. These include a Summary (including the participant’s SPID), expected behaviour, and current behaviour.
5.	Once the backend IT team fixes the issue, they update the status in the Sheet. Otherwise, if there is a follow-up instruction for the participant, the IT team updates it in the Sheet for necessary action by the IT POC and onward action by the Applicant Nurturing Team.

## Process 3 – Applications IT Requirements – Bugs

This process addresses issues which are typically faced by multiple participants, such as not being able to watch the webinar, or getting an error while opening the Health assessment form, etc.

1.	When one or more participants are facing an IT issue, they call on Sadhanapada helpline or write to sadhanapada@sadhguru.org.
2.	The incoming calls or emails representative tries to resolve the issue with the participant with common troubleshooting steps. These can include using the Chrome browser, clearing the browser cache, making sure to log in with correct credentials, or using incognito mode.
3.	If the issue persists, the nurturing team raises a ticket on Helpdesk with a screenshot or recording proof as well as the date and time of the issue.
4.	The IT POC updates the details in the “Applications IT Requirements 24-25” Google Sheet “other bugs” tab, along with a Google Drive link to the screenshot/recordings and the date/time of the error. The Google Drive link has open access to “Anyone with the link”. The details include a summary with SPID(s) of participant(s) facing the issue, expected behaviour, current behaviour, attachment link(s), process hindrance and other details, if any.
5.	The IT team may raise a JIRA ticket for their process purposes and update the ticket link in the Sheet for downstream visibility.
6.	In case the IT team or the Sadhanapada tech team requires additional information or clarification, or wants to issue instructions for the participant, they drop a comment in the Google Sheet against the issue.
7.	The IT POC responds to the query by dropping a “follow-up comment”.
8.	Once the issue is fixed, the Sadhanapada tech team representative informs the IT POC of the Applications team about it.

## Process 4 - Applications IT Requirements – Enhancements

This process is used for requesting new features or enhancements to existing features in Sadhaka.

1.	When the Sadhanapada Indian Applications team wants to request an enhancement, the IT POC enters the details in the “Applications IT Requirements 24-25” sheet, in the “Enhancements” tab. Details include category, ask, problem statement, current workaround being used, possible solution, priority and anticipated impact.
2.	Once the enhancement is implemented by the backend IT team, the Sadhanapada tech team informs the IT POC about it.

# Troubleshooting

In case participant faces technical issues, the caller / troubleshooter should first try the following steps before escalating the issue to the IT POC:

## 404 Error
In case the participant recives 404 Error while trying to access Full Profile form or Health Assessment Form on Sadhaka, please check if they are logged in via the correct email ID using the following steps:

* Ask the participant to visit the following URL - <https://ishalogin.sadhguru.org/profile>
* Note the email ID shown on the page that opens
* Make sure that this email ID is the same as the one provided by them in their Sadhanapada Interest Form. It will be mentioned under "Personal Info" in their Sadhaka profile page.

In case of Health Assessment Form, please go to their profile in Sadhaka interview page and re-send the health assessment form using the button shown in the screenshot below. There is a bug in Sadhaka where the first time the email is sent, the Health Assessment tab is not enabled in SP Portal. Second time it works (using this button).

![HA Form Re-send Button](/images/it_troubleshooting/ha_404_button_screenshot.png)
