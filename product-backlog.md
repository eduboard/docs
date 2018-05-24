# Product backlog

This is the product backlog for eduboard. It is split into frontend and backend and ordered descendingly by importance

## Backend
* The backend needs the following capabilities:
	* course creation/deletion/modification
	* provision of course information
	* user administration
	* user authentication
	* handling of access rights
	* live chat or forum
	* e-mail notifications for invitations and new contributions
* Implement an authentication based API for accessing the backend data.
* Implement access rights (incrementally):
	* users:
		* see pages of courses of which they are members
		* see visible content of courses of which they are members
		* participate in visible chats/forums of which they are members
	* teachers:
		* create, modify and delete courses of which they are owners
		* see and access all content of courses of which they are members
	* administrators:
		* moderate any content of any courses
		* create/modify/delete users
		* create/modify/delete courses
* Send e-mail notifications for new invitations.
* Send e-mail notifications for new chat/forum contributions.
* Implement a group matching tool based on private user preferences.

## Frontend
* Create course pages which contain:
	* an overview page containing the course material
	* a non-deletable course chat
* Create a per-course administrative interface
* Create an administrative interface that provides:
	* course administration
	* user administration
* Make paid courses only visible to participants by invitation.
* Give extra functionalities to administrators:
	* chat/forum and course moderation
* Give access to a group matching tool based on private user preferences.
