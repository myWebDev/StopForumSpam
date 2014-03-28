## esoTalk – StopForumSpam plugin

- Suspends a member if the member is listed in StopForumSpam. 

### Installation

Browse to your esoTalk plugin directory:
```
cd WEB_ROOT_DIR/addons/plugins/
```

Clone the StopForumSpam plugin repo into the plugin directory:
```
git clone git@github.com:esoTalk-plugins/StopForumSpam.git StopForumSpam
```

Chown the StopForumSpam plugin folder to the right web user:
```
chown -R apache:apache StopForumSpam/
```
