# ReleaseNotes
Mendix module to maintain and publish release notes

This module can be used to inform users about the latest release.

= Functionality =
- Info page with all releases, option to define different changes (fix, improvement, new feature)
- One-time popup for users after a new release

= Roles =
- User
- Admin

= Installation =
== Releases ==
- Create boolean (default false) ShowReleaseNotes in Administration.Account
- Create boolean (default true) FirstTime in Administration.Account
- Add ApplicationHelp to navigation for all users
- Add ReleaseNote_Overview to navigation for admins
- Add ShowReleaseNote to homepage microflow

== Manuals ==
- Add Manual_Admin to navigation for admins
- Create page with snippet Manuals for users

== FAQ ==
- Add FAQ_Admin to navigation for admins
- Create page with snippet FAQ for users

= Configuration =
- To automatically create Youtube (YT) videos after startup use the title and YT code in your AfterStartUp (ASU) microflow (see ASU_Video_Create in _USEME/Example as an example)
