# TangleDex Discord Bot - Privacy policy

The following document explains what data is collected by TangleDex.

### Glossary

- "Application" or "Discord application" refers to the Discord bot user, its associated owners, and the servers that has
- "Data" refers to data stored by an individual instance, including personal data
- "Bot" or "instance" refers to the copy of the code running the Discord application, with its own data
- "Collectible" refers to any object that is meant to be collected, such as countryballs or other future means like virtual currency
- "Application owners" refers to the owners of the Discord application, meaning the one with any form of access to the application's authentication method and data belonging to the instance
- "TangleDex moderation team" or "moderation team" refers to the owners of the Discord application and the users they may choose to be part of the moderation team. You may find a list of these users on the [Discord server](https://discord.gg/HmSMT4WKKV).

## Open source

The code of TangleDex (BallsDex Instance) is open source under the MIT licence and available at https://github.com/laggron42/BallsDex-DiscordBot. A copy of the license can be found below.

<details>
  <summary>The MIT licence</summary>

  > Permission is hereby granted, free of charge, to any person obtaining a copy
  > of this software and associated documentation files (the "Software"), to deal
  > in the Software without restriction, including without limitation the rights
  > to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  > copies of the Software, and to permit persons to whom the Software is
  > furnished to do so, subject to the following conditions:

  > The above copyright notice and this permission notice shall be included in all
  > copies or substantial portions of the Software.

  > THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  > IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  > FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  > AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  > LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  > OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
  > SOFTWARE.

</details>

**The instance is guaranteed to be running an exact copy of the code made open source.** The version may not be the latest available (check `/about`), but no local changes will be made. This may change, but users should be notified in the [Discord server](https://discord.gg/HmSMT4WKKV) about such change.

You may check the source code and see how the data is managed, in addition to the following policy.

## What data is collected

TangleDex collects the following data from Discord:

- User IDs, this is used to identify you inside our database
- Server (or guild) IDs, this is used to store settings necessary to the bot's operation
- Channel IDs, this is used to know in which channel should the collectibles spawn

In addition, the following data proper to TangleDex is created and used:

- The list of collectibles owned by a user of the service
- A history of trades done on collectibles, including the users that once owned the said collectible but do not anymore

## How the data is stored

All data is stored on a PostgreSQL server, running on a Virtual Private Machine hosted by Oracle Corporation.

Interaction between the bot and the database server is exclusively local using [Tortoise ORM](https://github.com/tortoise/tortoise-orm).

## Access to the data

The only persons allowed to access the data are the application owners.

Any application owner may interact with the bot and the administrator interface. Only `reictangle` has direct access on the host machine.

The TangleDex moderation teams do not have access to the data.

The data may never be made available to the public, and its access must be secured accordingly.

## Your rights

You may request a copy or the deletion of your personal data held by the application by contacting the application owners. The recommended way is sending an email to "TangleDex (at) reichtangle (dot) gmail (dot) com ".

----

Last updated 9th October 2022
