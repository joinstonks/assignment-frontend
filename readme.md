## Stonks frontend assignment

#### `Only use next/react library, tailwind is accepted for css.`

Your code must be clean and custom hooks are nice to have.

#### Data table: [Tanstack Table and Shadcn is accepted]

Create a CRUD that is SSR, you will use this endpoint
to fetch data `https://665621609f970b3b36c4625e.mockapi.io/users`
Docs is here for filters, pagination and limit https://github.com/mockapi-io/docs/wiki

- User can navigate from page 1 to 5.
- User can search by email / username
- Rewrite current url with current page and filters, can be multiple filters.

#### Chat

Simple message list of users, if someone tag you should add a light background to the message. If the message contain :emoji: should be replace by the correct image.

##### [CHAT] Emojis

In the message input if the user start writing an `:emoji:` a popup/tooltip or panel of emojis will popup and user can chose one by using his **keyboard and mouse**.

##### [CHAT] Tag a user

In the message input if the user start writing `@` will show a list of min 3 users.

Add a filter logic so if the user want to tag `@edeuxk` and writes `@edxk` the module should be smart enough to retrieve the `@edeuxk`

##### [CHAT] Commands

In the message input if the user start writing `/` we should provide a list of actions — for now we will only support the following actions :

- /mute @user
- /ban @user
- /title set a title to the current stream
- /description set a description to the current stream

### Bonus

`Modal` need to fit on every screen size - including resizing and scrolling inside, if user press escape need to close modal.

`Profile picture upload/edit` select a picture from disk file, resize and upload selected area. Compression is required and image should be less than 550kb. User don’t have to be restricted, it will be compressed by computer and saved as png. User can select svg/png/jpeg. Note that iOS store images as .heic be aware of that - [3rd library accepted]
