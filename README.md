# GSoC Mentor

## Project I Mentored

[coala Language Server](https://summerofcode.withgoogle.com/projects/#4971369184362496)

> coala as a linting and code fixing tool can be far more useful when its power can be directly leveraged from within the code editor. Since all the major IDE's and code editors are now starting to support the standard Microsoft Language Server protocol it is now possible to expose coala's capabilities via the one said protocol and support a wide range of code editors. This proposal outlines the project where I intend to build one such server loosely based upon the proof of concept implementation built for vs-code. It should see noticeable performance improvements, feature upgrades to support actions such as didChange, didSave etc, customization of bears from within the LSP, support for all languages coala supports and be a fully standards confirming general language server.

## Tools I Used

- [band.us](https://band.us/) for the calendar.
- [Trello](https://trello.com) for process management.
- [GitHub](https://github.com) for code hosting service.
- [zoom.us](https://zoom.us) for online audio chat.
- [gitter](https://gitter.im) for IRC.

## Process (China Standard Time)

**2018.04.26 22:00** First Meeting

> First, we need to setup a dev blog, we have some discussions before.
Second, coala needs us to write a description for the idea coala language server and they will post it to twitter. Maybe we could ask them to mention your name in that post.

Dev Blog: https://ksdme.github.io/

About the development plan:

> The first evaluation, I think we could refactor the structure of the current design. You are already doing it.
The coala-vs-code is designed and implemented in about 10 days, thus the structure is not very clear.
And, of course we need to keep 100% coverage from the beginning.
In evaluation two, I think your proposal works for me.
But I am not sure what is bears configuration using LS protocol.
In evaluation three, we need to do some performance improvement work.
This is a brief picture for the whole project, and if you have any idea, we could discuss about it.

About the meeting:

We decided to have 2 meetings every week at the beginning.

**2018.05.02 22:00** Second Meeting

We come to an agreement on the schedule:

- Evaluation 1: Refactor and Improve test
- Evaluation 2: Release GA
- Evaluation 3: Performance improvement

And we decided to use Trello to manage the progress: [coala Language Server in Trello](https://trello.com/b/yHuWxRlu/coala-language-server)
