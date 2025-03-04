# Product outline: Military information in the VA.gov profile

Last Updated: July 1, 2022

### Communications

- **Github labels**: vsa-authenticated-exp
- **Slack channel**: [#accountexp-authexp](https://dsva.slack.com/channels/accountexp-authexp); [#va-profile](https://dsva.slack.com/channels/va-profile)

### Roles  
  
[This is currently managed by the VA.gov profile team](https://github.com/department-of-veterans-affairs/va.gov-team/blob/master/products/identity-personalization/profile/README.md#roles).

---

### Table of Contents

- [Overview](#overview)
- [User problem statements](#user-problem-statements)
- [Measuring success](#measuring-success)
- [Projects](#projects)
- [How to access and test](#how-to-access-and-test)
- [Backend](#backend)
- [Design](#design--ux)

---

## Overview

We pull in a small amount of military information to the VA.gov profile. This information is read-only and uneditable, as it is offical government record.

Currently, we show:

- Branch(es) of service
- Period start dates
- Period end dates
- Multple periods of service, if applicable

## User problem statements

- As a Veteran, I want to see what service history information the VA has on file for me to validate that it's correct.

## Measuring success

Need link to GET/POST data in Google Analytics.

## Projects

- [Integrate military information through VA Profile](https://github.com/department-of-veterans-affairs/va.gov-team/tree/master/products/identity-personalization/profile/military-information/vaprofile-integration#readme)

## Backend

Military currently integrates through [eMIS](https://depo-platform-documentation.scrollhelp.site/developer-docs/EMIS.1887174669.html) but will soon be moving to [VA Profile](https://depo-platform-documentation.scrollhelp.site/developer-docs/VA-Profile.1885602002.html).

Backend documentation can be found [here](https://github.com/department-of-veterans-affairs/va.gov-team-sensitive/blob/master/products/identity-personalization/profile/military_info/backend_documentation.md).

## Design 

- [Military Information sketch files](https://www.sketch.com/s/fc96664a-1c62-40ed-9fcd-90218c54e775).
- Use case documentation is needed.
