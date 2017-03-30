# CHANGELOG YellOwBot [BETA]

## Command Register User:

**Features**

> STATUS

- [x] Verify that `id` already has some data in the database; [3]

- [] Verify that the `user` entered in the command / register` [user] `already exists in the database; [2]

- [] Do not allow to register with user having special characters, only letters and numbers; [4]

- [x] Send private message `return` with details of the registration. Containing the following details:
(I.e.
💬 Group:
🕐 Validity:

🖥 IP:
👤 User:
🔑 Password:

> Attach the button to delete the register at any time, at the user's option.
(I.e.

- [x] Send to group `return messages`:

** Return Messages **
> `Registration completed successfully. Start a conversation with me so I can send you your registration details.`

> `Sorry, but the informed user already exists.`

> `You already have a registration in our system.`

> `Only letters and numbers.`

- [x] Add button in the group's return message, so that the user can initiate a conversation with the bot.

> Allow group use only.

## GROUPS AND ADMINISTRATORS> SERVERS ##

- [] Command to add group IDs that can use BOT features;

- [] Command to add user IDs that can use the command to add the Server

- [] Command to add data from the server to the database.

> After the server is added, display a return message with the server data.

** Return Messages **

[MESSAGE DISPLAYED FOR THE MASTER]

> `Registered user successfully .`

[MESSAGE DISPLAYED FOR NON-SIGNED MEMBERS THAT TRY TO USE THE ADD SERVER COMMAND]

> `Sorry, but you do not have any privileges to add servers.`
