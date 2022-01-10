# q2a-onlineplus

<b>Plugin Name:</b>  Online Plus <br>
<b>Price:</b> 20 USD (contact me to buy) <br>
<b>Plugin Description:</b> This is a premium-paid Q2A plugin that shows online users as a list page and a widget.<br>
<br>
<ul class="first">
	<b>Plugin Functionality:</b>
	<li>Plugin creates table at database to store data.</li>
	<li>Plugin checks user's status every 2 minutes using ajax polling. Whether they are still online or idle.</li>
	<li>Admin can set online/offline timeout in settings (Default: 3 minutes).</li>
	<li>If the plugin cannot get ajax signal from a user for this timeout (3 minutes), then user becomes offline.</li>
	<li>Admin can set idle state timeout in settings (Default: 5 minutes).</li>
	<li>If the user is online, but remains actionless for during this timeout (5 minutes) then its status goes to idle.</li>
	<li>If a user goes idle, then ajax polling check will run every 4 minutes. It is to mitigate unnecessary poll checks within a time interval.</li>
	<li>If a user logs out then s/he is deleted from the database table for online users immediately.</li>
	<li>If a user closes browser without logging out then s/he is deleted from the database table within online/offline timeout.</li>
	<li>The plugin has a widget for sidebar. In order to not mess up sidebar widget where number of online users are large, the admin can set a limit for displaying users in the widget. By default this limit is set to 10.</li>
	<li>And there will appear a link to "full list of online users" at the bottom of the widget once the number of online users exceeds the display limit. The link will redirect you to the plugins page where you can see all currently online users.</li>
	<li>Admin can set who can see online users.</li>
	<br/>
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/onlineplus/img-1.png" width="500px" height="auto" />
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/onlineplus/img-2.png" width="500px" height="auto" />
	<img src="https://ihlassovbetov.github.io/assets/plugin-ss/onlineplus/img-3.png" width="500px" height="auto" />
</ul>
<br/>
<ul class="first">	
	<b>TEST DEMO WEBSITE: <a href="https://gyzgyn.com/q2a-demo" target="_blank">LIVE DEMO</a></b>
	<li>Standard registered user (username: deneme_11 / pass: test1234)</li>
	<li>Moderator user (username: demo / pass: demo1234)</li>
</ul>

