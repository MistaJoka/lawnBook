# Product Requirements Document

## 1. Product Summary

### Questions
- What is the product? AI first mobile app for a solo landscaper on the field. able to optimize jobs, organize customers, perform follow-ups, invoicing, and routing optimization. 
- Who is it for? Users are solo or small landscaping businesses looking for premium features and tools offered by the pros at a margin of the cost since it is being vibe coded.
- What primary job does it help the user complete? Save time, ease process and repetitive workflows. Scheduling jobs with gas efficient routing, collect leads and jobs to then measure ROI,  
- What is the simplest useful promise of the app? Makes things easier while on the job. No BS. AI fancy but where it counts. Won't scare with big tech but will still provide the same reach. 

## 2. Problem Statement

### Questions
- What problem exists today? Jobs can get scheduled far apart, causing long drives between. Customer also can forget to pay leading to manual communication.
- What makes the current process slow, expensive, annoying, or error-prone? Annoying to have to deal with customers directly at a large scale. Organizing payment collect after the job is complete. 
- What happens if this problem is not solved? Continued manual follow ups are a waste of time and causes friction. Lack of documentaion and accurate invoicing can be costly. 
- How often does the problem occur? There are some repeat offender like some elderly clients. And then there are the occasional slips. 

## 3. Target Users

### Questions
- Who is the primary user? Solo landscaper looking to make their small business more efficient. Allows them to make more money by collecting leads and organizing customers.
- Who is the secondary user, if any? Later in the development more users can be added with certain permissions than the account owner.
- Who should not be targeted yet? Medium to large landscaping businesses. 
- What skill level should the app assume? User can read simple short actions, phrases, instructions, and description. Needs a layout optimized to read the data easily as the user is on the app. 

## 4. User Stories

Format:

```txt
As a [user], I want to [action], so that [benefit].
```

### Questions
- What does the user need to create? customers, scheduled jobs, estimates, invoices, communications.
- What does the user need to view? Customer details, job instructions and details, invoice status, the days job route.
- What does the user need to update? Jobs status/phase, invoice status, customer errors.
- What does the user need to delete? Customers, jobs if no invoice attached, invoice if no payment attached.
- What does the user need to export, share, or send? End result photo of the lawn to their client. 

## 5. MVP Features

### Must Have
- [ ] Works offline. 
- [ ] Visual map display showing the days job route.
- [ ] Saves time, earns more money. 

### Should Have
- [ ] Kanban board style application adapted for mobile web application.
- [ ] Easy to read and see UI. Dark mode option. High tech feel.

### Later
- [ ] Signature request from in app to confirm clients authorization. 
- [ ] Integration with free third party api.

### Questions
- Which features are required for first real use? Able to create customer, job, send invoice and confirm status, log and document for analytics and reporting. 
- Which features are nice but not required? theme customization.
- Which features create unnecessary complexity now? Free marketing.

## 6. Acceptance Criteria

### Questions
- How do we know the MVP works? User is able to collect a lead on the spot or create a customer, send a offer and accept a job, see where and when the job is, collect payment on completion, generate and monthly report. 
- What must the user be able to complete without help? End to end days workflow. All steps to start and finish processes to save time and frustration.
- What should be tested manually before calling it done? The front end behavoiral errors. 
- What screenshots or demo flow prove completion? Completed customer object with its elements, jobs and its details, invoice and its status and logging. 

## 7. Non-Goals

### Questions
- What are we intentionally not building? Generic app flows that are boring and bring no joy to completing. 
- What platforms are excluded?
- What integrations are excluded?
- What advanced automation is excluded?

## 8. Risks

### Questions
- What could block development?
- What could confuse users? Non descriptive icons or fields. confusing user flow.
- What could cause data loss? If the offline data does not get succesffuly syncd to the data base when online. 
- What could make the app too expensive? User data needed for customer, jobs, and historical data. 
