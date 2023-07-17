# escapehatch-tracker

![image](https://github.com/JakeStrang1/escapehatch/assets/16689756/7f70f0ad-3d0a-4187-8856-86bf6a6d268d)

### Try it
The project is alive and well at [escapehatch.ca](https://escapehatch.ca)!

### Overview
Escapehatch is a platform where users track and share their favorite books and shows. The site is built and operated by me (hi!) and launched for early users in June 2023. We are in active development towards our v1 milestone.

- Join the [r/escapehatch Reddit community](https://www.reddit.com/r/escapehatch/) where I post regular progress updates.
- Submit bugs and features to the [dedicated issue tracker](https://github.com/JakeStrang1/escapehatch-tracker/issues)

### Tech specs
Escapehatch is a monorepo project where the backend is built using Go and MongoDB and the frontend is built using React. The backend is hosted on Google App Engine and deployed on each commit using Google Cloud Build. The frontend is hosted on Vercel and deployed on each commit. MongoDB Atlas hosts our database. Static assets are stored in a Google Cloud Storage bucket. SendGrid is used for email integration.

### The Ideal User
You love reading, watching shows, and diving into the worlds that others have created. You feel a sense of achievement when you finish a new book or show. You think that the content you consume says something about who you are and you want to showcase this to others. You can even think of recent conversations where having a list of your favorites on hand would have come in handy. 

You're methodical, you like seeing your achievements and progress laid out in front of you, especially if you can organize them. You like making lists and the time you spend organizing your hobbies feels like a hobby itself. You aren't daunted that most of your content needs to be added manually by you to the site, in fact you feel excited. You're a completionist and the goal of being the one to contribute entries that others will see and find useful is a thrill. You could sit for hours just filling in missing content on the site if it means your contributions will gain you recognition across the platform.

## Roadmap
**Current phase**: Building v1

### V1
The bare minimum feature set for the ideal user to find value:

- [x] Passwordless login
- [x] Account setup wizard
- [x] Profile page displays user's shelves (Movies, TV Shows, Books)
- [x] Search page to find items to add to shelves
- [x] Followers page to view followers, following, and search for users
- [ ] Item details page with additional action buttons (remove from shelf)
- [x] Form to add new items to the DB
- [ ] Form to edit or remove item from DB

### V2
Features to increase delight and stickiness for the ideal user:

- [ ] Create/edit/delete custom shelves
- [ ] Set additional item attributes (read/unread, progress tracking, dates) 
- [ ] View shelf as full page
- [ ] Rearrange items on shelves (drag)
- [ ] New follower notification
- [ ] Publish leaderboard of user contributions
...
