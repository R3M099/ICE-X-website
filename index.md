<html>

<head>
	
<style>
	
	.button{
		 border: none;
  		 color: white;
  		 padding: 16px 32px;
  		 text-align: center;
  		 text-decoration: none;
  		 display: inline-block;
  		 font-size: 16px;
  		 margin: 4px 2px;
  		 transition-duration: 0.4s;
  		 cursor: pointer;
			}

	.button1{
		background-color: white;
		color: black;
		border: 2px solid #219edc;
			}

	.button1:hover{
		background-color: #219edc;
		color: white;
	}

	.button2{
		background-color: white;
		color: black;
		border: 2px solid #0ebcea;
			}

	.button2:hover{
		background-color: #0ebcea;
		color: white;
	}

	.button3{
		background-color: white;
		color: black;
		border: 2px solid #21c81e;
			}

	.button3:hover{
		background-color: #21c81e;
		color: white;
	}

	.button4{
		background-color: white;
		color: black;
		border: 2px solid #dd3a1d;
			}

	.button4:hover{
		background-color: #dd3a1d;
		color: white;
	}

	table, th, td{
		border: 1px solid black;
		border-collapse: collapse
	}

	th, td{
		padding: 5px;
	}

	th{
		text-align: left;
	}

</style>	

</head>

<body>

	<h1 style = "text-align:center;color:#0ebcea"><ins>ICE X</ins></h1>
	<p style = "text-align:center;">ICE X is a bot made for Discord using the Discord.py framework</p>
	<h3 style = "color:#0ac134"><ins>Specifications</ins></h3>
	<h4><ins>Bot Owner</ins> :</h4>
	<p><b>Remo</b> (Discord tag - <em>℟ʓϺ𝞱#0522)</em></p>
	<h4><ins>Python Version</ins> :</h4>
	<p>3.8.3</p>
	<h4><ins>Discord.py Version</ins> :</h4>
	<p>1.4.1</p>
	<hr>

	<h3 style = "color:#0ac134"><ins>Useful Links</ins></h3>
	<p>Here are some useful links related to the bot.</p>
	<button onclick = "document.location = 'https://github.com/R3M099'" class = "button button1">Github</button>
	<button onclick = "document.location = 'https://github.com/R3M099/ICE-X'" class = "button button2">ICE X</button>
	<button onclick = "document.location = 'https://discord.com/api/oauth2/authorize?client_id=723380957343907911&permissions=8&scope=bot'" class = "button button3">Invite bot</button>
	<button onclick = "document.location = 'https://discord.com/'" class = "button button4">Discord</button>
	<hr>

	<h2 style = "color:#0ebcea"><b>What is Discord?</b></h2>
	<p><a href = "https://discord.com/">Discord</a> is an American VoIP, instant messaging and digital distribution platform designed for creating communities. Users communicate with voice calls, video calls, text messaging, media and files in private chats or as part of communities called "servers".</p>
	<p>With that being said lets get into some information on ICE X.</p>

	<h3> Commands available </h3>

	<ul>

		<li> Moderation Commands </li>

		<table style= "width : 50%">
			<tr>
				<th>Command name</th>
				<th>Description</th>
			</tr>
			<tr>
				<td>purge</td>
				<td>purges the given number of messages from the channel</td>
			</tr>
			<tr>
				<td>kick</td>
				<td>kicks a specified member/members from the server</td>
			</tr>
			<tr>
				<td>ban</td>
				<td>bans a specified member/members from the server</td>
			</tr>
			<tr>
				<td>unban</td>
				<td>unbans a specified member from the server</td>
			</tr>
			<tr>
				<td>mute</td>
				<td>mutes a specified member from the server</td>
			</tr>
			<tr>
				<td>unmute</td>
				<td>unmutes a specified member from the server</td>
			</tr>
			<tr>
				<td>addrole</td>
				<td>add a role to the specified member</td>
			</tr>
			<tr>
				<td>removerole</td>
				<td>removes a role from the specified member</td>
			</tr>

		</table>

		<li> Fun Commands </li>

		<table style = "width: 50%">
			<tr>
				<th>Command name</th>
				<th>Description</th>
			</tr>
			<tr>
				<td>hello</td>
				<td>greets the user with a message</td>
			</tr>
			<tr>
				<td>8ball</td>
				<td>ask any question to the magic 8ball</td>
			</tr>
			<tr>
				<td>ping</td>
				<td>returns the latency of the bot</td>
			</tr>
			<tr>
				<td>say</td>
				<td>let the bot say what is in your mind</td>
			</tr>
			<tr>
				<td>fact</td>
				<td>gives a fact about the specified animal</td>
			</tr>
			<tr>
				<td>meme</td>
				<td>gives a random meme</td>
			</tr>
			<tr>
				<td>joke</td>
				<td>gives a random joke</td>
			</tr>
			<tr>
				<td>pjoke</td>
				<td>gives a random programming joke</td>
			</tr>
			<tr>
				<td>cnjoke</td>
				<td>gives a random Chuck Norris joke</td>
			</tr>
			<tr>
				<td>xkcd</td>
				<td>gives a random xkcd comic(a webcomic)</td>
			</tr>
			
		</table>

		<li> Utility Commands </li>

		<table style = "width: 50%">
			<tr>
				<th>Command name</th>
				<th>Description</th>
			</tr>
			<tr>
				<td>serverinfo</td>
				<td>gives the information about the server</td>
			</tr>
			<tr>
				<td>userinfo</td>
				<td>gives the information about the specified user</td>
			</tr>
			<tr>
				<td>avatar</td>
				<td>gives the avatar of the member</td>
			</tr>
			<tr>
				<td>afk</td>
				<td>sets the member to afk for the given time</td>
			</tr>
			<tr>
				<td>botinfo</td>
				<td>gives the information about the bot</td>
			</tr>
			<tr>
				<td>createpoll</td>
				<td>start a vote on a topic of your choice</td>
			</tr>
			<tr>
				<td>prefix</td>
				<td>changes the prefix of the server(admin only command)</td>
			</tr>
			
		</table>

		<li> Astronomy Commands </li>

		<table style = "width: 50%">
			<tr>
				<th>Command name</th>
				<th>Description</th>
			</tr>
			<tr>
				<td>apod</td>
				<td>gives the Astronomy Picture Of Day</td>
			</tr>
			
		</table>

		<li> Support Commands </li>

		<table style = "width: 50%">
			<tr>
				<th>Command name</th>
				<th>Description</th>
			</tr>
			<tr>
				<td>invite</td>
				<td>sends the invite link of the bot</td>
			</tr>
			
		</table>

	</ul>
	<hr>

	<h2 style = "color:#0ebcea"><ins>License</ins></h2>

	<p><a href = "https://github.com/R3M099/ICE-X">ICE X</a> is licensed under <a href = "https://github.com/R3M099/ICE-X/blob/master/LICENSE">MIT</a>.</p>

</body>

</html>
