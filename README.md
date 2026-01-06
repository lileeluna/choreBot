# Chores Bot (Work in Progress!!)

A Discord bot that can send chore reminders to an apartment group server after setting up a chores rotation and chores list.

## (Temporary) Installation instructions:

- The chorebot depends on the chore_rotation.json and chores.json file, which should be created automatically. If not, create a chore_rotation.json file containing only "[]" and a chores.json file containing only "{}". The bot will then work as intended.
- A .env file containing your Discord bot token is also needed (this version's .env file is in the .gitignore for security reasons).

## Implemented features:

- Can add daily, weekly, and monthly chores, as well as any chores that repeat over a set number of days.
- Can modify the chores list after creation.
- Can add a chore rotation, which can be modified after creation easily.
- Chores list and chores rotation can be displayed.

### Current feature goals:

- Can handle chores of varying frequencies, such as daily, weekly, monthly, or as-needed chores.
- Optionally, can automatically assign chores to the next person, or if one chore is handled by only one specific person, can be set to a reoccurring chore assignment.
- If a person does not mark their chore as complete, the bot reminds the person once per day until it is complete.
- Saves the "last-done" date of each chore.
