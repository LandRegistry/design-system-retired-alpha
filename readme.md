# concept prototype for casework

we currently have axure prototypes for application processing (aka casework - although that term should include other named applications / projects)

we want to have a coded prototype - that feels and acts like the built thing, with the abilty to easily add new ideas for testing.

this repo is to try our ideas for making a coded prototype - a concept repo, an alpha if you will.  This may turn into our actual prototype, or it may just inform what we actually want to make as a protoype.


# peoples needs

as a designer working on tools for caseworkers i want to be able to make a prototype that enables us to maximise learning from caseworkers

as a user researcher working with caseworkers i want to be able to maximise usability testing and learning

as a project team member i want to see ideas and designs for caseworker tools/system so i can ask questions, understand what we are building/thinking of building

as a new staff designer joining a casework project team i want to be able to create designs as quickly and robustly as possible using my existing skills

to enable quality assurance (head of design, design seniors, senior staff) i want to see what design work is happening / has happened for caseworker tools - so i can ask questions of the design/project team and answer questions other staff have



## repo background

this repo is a clone of HMLR GOV.UK Prototype Kit with form validation

which is a copy of the GOV.UK prototype kit, version 9.6.0, with form validation.

we are staring with this because - its a running node app that we are familiar with, and other staff designers should be familiar with.  So we can quickly test the ideas/what we need to do to make a coded proto, and discover if this would meet our needs, or if we should do something else.


## todo

### basics
- [x] move instructions / pages for how to do form validation - kept, but moved to sub folder
- [x] gov kit make template and style sheet (start with a copy of form validation code i have - although it needs fixing/improving)
- [ ] improve read me / user needs

### DJP
- [x] add the flat html files and screenshots 
- [x] wire a few flat pages into a basic flow
- [ ] set up folder structure - want each folder to be self contained version (think about style), so have includes, partials etc. be good if style sheet was always latest version - keep old versions
- [ ] get basic page in for:
- [ ] - start
- [ ] - task
- [ ] - finish
- [ ] make a page to show off each component - like style guide (so is a bit of doing the design system)
- [ ] get a register into json

- [ ] make a simple flow - start, task, end (no validation)
- [ ] add validation
- [ ] make a loop flow - can do x amount of cases. - parameterised.
- [ ] add - read data from json
- [ ] add store data to session - for each application (so top level of session is a number, then the structure below, like 
- [ ] add ability to set up data

###
- [ ] add RX1 page - see v5 proto.
- [ ] add autocomplete
- [ ] add (macro?) ability to set up questions form a json object (making it like prod) - enabling any cre to be picked
 



## About the GOV.UK Prototype Kit

If you need the latest kit

Go to the [GOV.UK Prototype Kit site](https://govuk-prototype-kit.herokuapp.com/docs) to download the latest version and read the documentation.

The Prototype Kit provides a simple way to make interactive prototypes that look like pages on GOV.UK. These prototypes can be used to show ideas to people you work with, and to do user research.

Read the [project principles](https://govuk-prototype-kit.herokuapp.com/docs/principles).

## Security

If you publish your prototypes online, they **must** be protected by a [username and password](https://govuk-prototype-kit.herokuapp.com/docs/publishing-on-heroku). This is to prevent members of the public finding prototypes and thinking they are real services.

You must protect user privacy at all times, even when using prototypes. Prototypes made with the kit look like GOV.UK, but do not have the same security provisions. Always make sure you are handling user data appropriately.

## Installation instructions

- [Installation guide for new users (non technical)](https://govuk-prototype-kit.herokuapp.com/docs/install/introduction)
- [Installation guide for developers (technical)](https://govuk-prototype-kit.herokuapp.com/docs/install/developer-install-instructions)

## Support

The GOV.UK Prototype Kit is maintained by the Government Digital Service. If you’ve got a question or need support you can:

* email [govuk-design-system-support@digital.cabinet-office.gov.uk](mailto:govuk-design-system-support@digital.cabinet-office.gov.uk) 
* [get in touch on Slack](https://ukgovernmentdigital.slack.com/messages/prototype-kit)([open in app](slack://channel?team=T04V6EBTR&amp;id=C0647LW4R)) 
* [view known issues on GitHub](https://github.com/alphagov/govuk-prototype-kit/issues)
        
## Contributing

If you’ve got an idea or suggestion you can:

* [get in touch on the developer Slack channel](https://ukgovernmentdigital.slack.com/messages/prototype-kit-dev)([open in app](slack://channel?team=T04V6EBTR&amp;id=C0E1063DW))
* [create a GitHub issue](https://github.com/alphagov/govuk-prototype-kit/issues)
