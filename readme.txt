This plugin has been deprecated as it is a default feature in MyBB 1.8.



Name: Report Reputation
Description: Allows you to report reputation if it is spam/abuse etc.
Website: http://mattrogowski.co.uk
Author: MattRogowski
Authorsite: http://mattrogowski.co.uk
Version: 0.3.1
Compatibility: 1.6.x
Files: 3
Templates added: 8
Template changes: 4
Database changes: 1 new table.

To Install:
Upload ./inc/plugins/reportrep.php to ./inc/plugins/
Upload ./inc/languages/english/reportrep.lang.php to ./inc/languages/english/
Upload ./images/modcp/user_comment.png to ./images/modcp/
Open ./files/reportrep_css_additions.css and add the code inside to the bottom of modcp.css for your themes, by going to ACP > Templates & Style > **choose theme** > modcp.css > Edit Stylesheet: Advanced Mode > scroll down and add the CSS to the bottom.
Go to ACP > Plugins > Install and Activate

Information:
This plugin will enable your users to report reputations.

It works in the same way as reported posts, with a notice in the header and a list of reported reputations in the Mod CP.

Change Log:
06/12/10 - v0.1 -> Initial beta release.
09/12/10 - v0.1 -> v0.2 -> Fixed bug where guests could report reputations. Fixed bug where the notice of unread reports in the header would be shown to normal moderators who cannot delete reputations, so cannot act on any reputation reports. To upgrade, reupload ./inc/plugins/reportrep.php and ./inc/languages/english/reportrep.lang.php
07/02/11 - v0.2 -> v0.3 -> Added a Who's Online List location for when a user is reporting a reputation or viewing the list of reported reputations. Reputations can now not be reported more than once. If a reputation has been reported, a small image will show next to the link to report the reputation. To upgrade, deactivate Report Reputation, reupload ./inc/plugins/reportrep.php and ./inc/languages/english/reportrep.lang.php, activate Report Reputation.
07/02/11 - v0.3 -> v0.3.1 -> Fixed a bug where it would say a reputation had been reported already even if it hadn't, and fixed a bug where the icon showing a reputation had been reported would show after the report had been marked as read. To upgrade, reupload ./inc/plugins/reportrep.php

Copyright 2010 Matthew Rogowski

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at

 ** http://www.apache.org/licenses/LICENSE-2.0

 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.