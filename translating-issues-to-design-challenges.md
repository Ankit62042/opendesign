# Translating (developer) Issues to (design) Challenges

This is an activity that the Open Design team have been trialling during 2020 workshops across the different stakeholder groups of: Designers (all definitions and abilities), OSS maintainers/Owners, Humanitarian projects/organisations with an OSS.

You can find links to the working whiteboard that we used a tool Miro for below:


[Miro Workboard for Open Source 101:at home 2020](https://miro.com/app/board/o9J_luu3JGw=/?share_link_id=617301176692)

[Miro Workboard for UX Bristol 2020](https://miro.com/app/board/o9J_lq02e_8=/?share_link_id=695937082946)

[Miro Workboard for RighstCon 2020](https://miro.com/app/board/uXjVKM74nGY=/?share_link_id=247058537995)


-----
## How to change an issue into a design challenge

One key aspect of encouraging design participation in the humanitarian, human rights and open source space is being able to take an issue that is written 'for developers or techies' and finding a pathway for design to hold space in that place. This can take the form of 'translating' a developer focussed and written issue into a 'design brief of challenge' The tricky part, it still needs to make sense to and be clear for developers and not 'just the ones you can have a face to face chat with, but developers globally (yup OSS being global and open!)


**You can use the examples below if you prefer but we encourage you to use your real life projects.**

*Here you'll find some examples of Humanitarian OSS projects/issues. If you have your own project (whether it's online or not, please use that instead! a working example is always better!) 
The easy/hard level has been assessed by Eriol Fox and may or may not reflect your individual comfort levels. We have tried to pick and give examples that are accessible for varying levels of experience and understanding.*

| Easy-ish                                                                                                                                                                                                                                          |   | Hard-ish                                                                                                                                                                                                                                                                                                     |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| TenFour                                                                                                                                                                                                                                           |   | Hikaya                                                                                                                                                                                                                                                                                                       |
| https://github.com/ushahidi/tenfour                                                                                                                                                                                                               |   | https://github.com/hikaya-io/activity                                                                                                                                                                                                                                                                        |
| TenFour is an emergency check-in application for teams that unites multiple communication channels: SMS, email, desktop, mobile and chat. It's a team check-in system that gets answers when you need them most.                                  |   | A modern way for nonprofits to manage project activities and indicator results. Try out Activity using our hosted version at  hikaya.io .                                                                                                                                                                    |
| TenFour: Fire Marshall: user training and teaching                                                                                                                                                                                                |   | Hikaya: i18n: How to determine the language to display Activity in?                                                                                                                                                                                                                                          |
| https://github.com/ushahidi/tenfour/issues/203                                                                                                                                                                                                    |   | https://github.com/hikaya-io/activity/issues/484                                                                                                                                                                                                                                                             |
|                                                                                                                                                                                                                                                   |   |                                                                                                                                                                                                                                                                                                              |
| Pa11y                                                                                                                                                                                                                                             |   | Chayn - Little Window                                                                                                                                                                                                                                                                                        |
| https://github.com/pa11y/pa11y-dashboard                                                                                                                                                                                                          |   | https://github.com/chaynHQ/little-window                                                                                                                                                                                                                                                                     |
| Pa11y Dashboard is a web interface to the  Pa11y  accessibility reporter. Pa11y is your automated accessibility testing pal. It runs accessibility tests on your pages via the command line or Node.js, so you can automate your testing process. |   | Little window is a clever little cat chatbot that directs women to the information they are looking for as quickly as possible. Feminist tech project helping survivors of abuse get the information & support they need. Open-source. Volunteer-run. 'Design with, not for'.                                |
| Pa11y: Add Groupings to pages                                                                                                                                                                                                                     |   | Chayn: no guiding issue :( create one!                                                                                                                                                                                                                                                                       |
| https://github.com/pa11y/pa11y-dashboard/issues/254                                                                                                                                                                                               |   | https://github.com/chaynHQ/little-window                                                                                                                                                                                                                                                                     |
|                                                                                                                                                                                                                                                   |   |                                                                                                                                                                                                                                                                                                              |
| CHAOSS                                                                                                                                                                                                                                            |   | The New Sanctuary Coalition                                                                                                                                                                                                                                                                                  |
| https://github.com/chaoss                                                                                                                                                                                                                         |   | https://github.com/CZagrobelny/new_sanctuary_asylum                                                                                                                                                                                                                                                          |
| This repository is part of the CHAOSS Community, a Linux Foundation project focused on creating analytics and metrics to help define community health.                                                                                            |   | The New Sanctuary Coalition is a network of congregations, organizations, and individuals standing publicly in solidarity with families and communities resisting detention and deportation. This internal database software facilitates NSC's core programs and allows them to operate at increasing scale. |
| Interview campaign with underrepresented groups in Open Source                                                                                                                                                                                    |   | Admins can bulk invite users                                                                                                                                                                                                                                                                                 |
| https://github.com/chaoss/wg-diversity-inclusion/issues/294                                                                                                                                                                                       |   | https://github.com/CZagrobelny/new_sanctuary_asylum/issues/247                                                                                                                                                                                                                                               |



It's best to form groups for this challenge, around 4 -5 people involved in product creation, but be cautious of  'developers' being the dominant voice in this activity or prioritising 'technology' and 'code' over the problem definition.

Here's an example of what I would call a 'translated design challenge' 

From this [original issue](https://github.com/ushahidi/tenfour/issues/119)

### Push alert after a configurable time that someone has not responded to a check-in

Is your feature request related to a problem? Please describe.
I'm frustrated when I have to check for myself whether someone has responded to a check-in on TenFour.

**Describe the solution you'd like**
As a user that has constructed a check-in and send it to my team I want to receive an in-app push alert after a configurable time that someone has not responded to a check-in. This should also display in a ‘history’ or notifications section.

To this design challenge:

### Push alert after a configurable time that someone has not responded to a check-in

**Please describe the problem from at least one ‘users’ point of view:**

As a person responsible for other people in TenFour it worries me when I don’t get a quick answer back from a team member about whether they are ok or not. When there is a crisis, knowing how much time has gone by without a response is important and knowing who hasn’t replied yet helps me to set up fall-back plans for a worst case scenario. But crisis is complicated and I might have other things that I need to concentrate on. That’s why I’d like some way of TenFour telling me when someone hasn’t replied in a certain time.

One way we thought of doing this is through configurable, push alerts on a persons device.


The event that triggered this issue was a recent terrorist attack in Nairobi: https://www.bbc.co.uk/news/world-africa-46880375

We are designing for at least two user groups primarily after a disaster, but they may be many more users.

**User 1 -** NGO Leads or people managing a TenFour domain. Typically have the role types of Owner and Admin in TenFour.

The owner of the TenFour organization could be the teacher of a class looking after students in a crisis. These users often pre-create groups in TenFour based off certain criteria but also want groups to be flexible.

**User 2 -** The people in the TenFour domain that receive a TenFour check-in and have been asked to reply. They may be moving from location to location in order to be safe. They may not have their phone immediately to hand.


**What is success for our user/s?**
Admin is notified who has not responded in a time frame that works for them
TenFour users are able to respond when/if they can. Seeing alerts may not be useful for these users.


**What are our design constraints?**

Requires: 
Mobile telecom connection or internet connection. Users are on the TenFour system as a ‘person’.
Must be developable within existing tech stack functionality
Will be completed by OSS developers


### Remember, writing this isn't just for your own benefit it's for all people who will see and learn from it's benefit. 

That's developers, other designers, users, researcher and the OSS community can look to examples like this for good practice. Set a good example :)


