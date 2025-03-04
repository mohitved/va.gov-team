# Team Development Processes

## Stand Up / Daily Scrum
- Team Member will
    - Raise your virtual hand when you enter Stand up and take it down after you have given your update
    - Answer the following questions
        - What is your Balance score?
        - What did you do yesterday towards our Sprint goals?
        - What are you doing today towards our Sprint goals?
        - Do you have any blockers?
    - Discuss who is responsible for reviewing any tickets that need validation and a timeframe for completion

## Refinement 
- Team will 
    - Answer & document in the Epic/Ticket the following questions for each Epic/Ticket
        - How will we release the work for this Epic/Ticket? 
            - Scheduled & Coordinated - will we use a Feature Flag or Feature Branch? 
                - All Epics should be scheduled and coordinated
            - Upon Completion & Approval
                - Bugs not related to an Epic plus Tech Debt can be released upon completion & approval
        - Is this in the Planned Releases list yet or does it not need to be?
            - Pick a release date that is at least 2 weeks from the day it is added to the Planned Releases list    
        - Does this Ticket need a release note?
   - Discuss and modify Acceptance Criteria, as necessary
   - Estimate/Point each Ticket (or apply a time box)
   - Understand the work that is necessary (high level) for each Ticket and how it is being released
   - Ensure tickets (using the following templates) are created, as necessary, and added to each Epic based on what work is needed
        - DESIGN
            - check-in-experience-create-prototype.md
            - check-in-experience-design-create-final-wireframes.md
        - DEVELOPMENT
            - check-in-experience-development-risk-register.md
            - check-in-experience-development-backend.md
            - check-in-experience-development-create-feature-flag.md
            - check-in-experience-development-frontend.md
            - check-in-experience-release-to-production.md
            - check-in-experience-release-update-atifacts.md
        - METRICS
            - check-in-experience-metrics-decide.md    
            - check-in-experience-metrics-create.md            
            - check-in-experience-metrics-monitor.md
        - RESEARCH
            - check-in-experience-research-assets-task.md
            - check-in-experience-research-plan-and-convo-guide-task.md
            - check-in-experience-research-interview.md
            - check-in-experience-research-conduct-study.md
            - check-in-experience-research-remote-study.md
            - check-in-experience-research-synthesis-task.md
            - check-in-experience-research-study-report-task.md            
        - TRANSLATIONS
            - check-in-experience-translations-add-to-spreadsheet.md
            - check-in-experience-translations-submit-to-SD.md
            - check-in-experience-translations-add-content.md             
            - check-in-experience-translations-submit-workflows.md      
 
 ## Planning
 - Epics 
    - Product will 
        - Add an Epic to the [Planned Releases](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/release-plan/check-in-planned-releases.md) list as soon as it enters our Product Backlog
        - Create pre-release notes for each item in the Planned Releases list
        - Include a release date or range with each Planned Release item (can be TBD)
        - Update the estimated release date in Planned Releases when one has been agreed upon by the Team
        - Notify Training, Contact Center, & Comms of updates to Planned Releases (see [Notifications of Releases & Updates to Planned Releases](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/team/processes.md#notifications-of-releases--updates-to-planned-releases)) 
        - **NOT** put **Tech Debt & Bug** items on the Planned Releases list   
    - Team will 
        - Determine an estimated release date that is at least 2 weeks from the date it was decided for scheduled & coordinated releases      
        - Estimate team's capacity for the Sprint using the [Sprint Capacity Calculator](https://github.com/department-of-veterans-affairs/va.gov-team/files/9105212/VASprintCapacityCalculator.xlsx)
        - Pull tickets into the Sprint
        - Agree on the Sprint goals
        - Agree on the Sprint content
    - Product will assign the current sprint to each ticket in the Sprint
 
 ## Validating
- Upon completion of a ticket (i.e. no more changes are expected and PR is done)
    - Ticket owner will
        - Move the ticket to the Validate column                 
        - Attach at least 1 of the following to the ticket per ticket type
            - For design/wireframe tickets
                - Screenshots of wireframes
                - Links to section in Abstract with relevant wireframes
            - For content tickets (TBD)
                - Link to spreadsheet with content
                - Actual content
            - For research tickets
                - Links to relevant files
            - For development tickets
                - Screenshots of completed work 
                - Link to Review Environment
                - Link to video demonstrating the feature
                - Do a quick Zoom call
        - Notify approvers in the UX or Engineering channels that the ticket is ready to be validated
        - Close the ticket once all reviews have been completed
    - Reviewer will
        - Add a comment to the ticket when their review is complete
        - Post in the thread, if there is one, that their review is complete

## Releasing
- Epics 
    - Team will 
        - Coordinate the release using the [check-in-release-planning](https://dsva.slack.com/archives/C03KQAUFVT6) channel
            - Changes to product guides et. al. (UX)
            - Merging of code or flipping of feature flag (Engineering)
            - Updating of release notes (Product)
            - Merging wireframes to Abstract main branch & updating VA Sketch cloud (Design)
            - Notification of Training & Contact Center et. al. (Product)
            - Closing of all tickets & the Epic (Engineering & Product)
    - Product will 
        - Post a release note to the [Release Notes](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/release-plan/check-in-release-notes.md) page and to the [check-in-release-planning](https://dsva.slack.com/archives/C03KQAUFVT6) channel for review by Engineering
        - Remove the Epic from the Planned Releases list 
        - Notify Training, Contact Center, & Comms of the release (see [Notifications of Releases & Updates to Planned Releases](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/team/processes.md#notifications-of-releases--updates-to-planned-releases))
- Tech debt & Bugs & stand-alone tickets that are pushed as soon as approved  
    - Engineering will 
        - Post a notice in the [check-in-release-planning](https://dsva.slack.com/archives/C03KQAUFVT6) channel on the day an item has been merged and is expected to go to production
    - Product will 
        - Create a release note, if needed, and post it after 3 pm when the item gets pushed to production 
        - Post a release note to the [Release Notes](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/release-plan/check-in-release-notes.md) page and to the [check-in-release-planning](https://dsva.slack.com/archives/C03KQAUFVT6) channel for review by Engineering
        - Notify Training, Contact Center, & Comms of the release (see [Notifications of Releases & Updates to Planned Releases](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/team/processes.md#notifications-of-releases--updates-to-planned-releases))


## Notifications of Releases & Updates to Planned Releases
- Notification of updates to Planned Releases
    - Modernized Check-in team has updated their Planned Releases. (include the link to the [Planned Releases](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/release-plan/check-in-planned-releases.md) page)
- Notification of production releases
    - Modernized Check-in team released to production on <mm/dd/yyyy>. Release notes can be found here. (include link to [Release Notes](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/health-care/checkin/release-plan/check-in-release-notes.md))
- Notify the following people via Slack and email
    -   [check-in-releases](https://dsva.slack.com/archives/C03E5FEBTLH) channel - Patrick Bateman, Stephen Barrs, Shawn Adams, Jason Woodman
    -   VA email - Patrick Bateman, Stephen Barrs, Shawn Adams, Jason Woodman, Dore Mobley


## Diagram of All Team Processes

![CIE Development Process - BPMN process flow (1)](https://user-images.githubusercontent.com/86678742/174146999-201947c6-33b6-4564-bb64-a1bce22631df.jpeg)



