# timechain-web
timechain academy website

## About

Buit with Nuxt3 js with tailwindcss and Content v2.0 plugin. 
Dependencies kept to a minimum.

## Commands

```
$ git clone https://github.com/timechain-academy/timechain-web
$ yarn install      (installs dependencies)
$ yarn dev -o       (starts local dev server at localhost:3000)
```


## Todo List: 

- replace lorem ipsum placeholder text with real content at [todo]
    - blog page
    - library site (timechain-docs)
- update Discord link 
- update Donate link

### Refactoring

- replace <a href> links with <NuxtLink/> [todo]
- Refactor tailwindcss into reusable components [todo]
- integrate cal.com, btc/ln payments for sessions [future]


### Plugins

- Plugins to be used at a minimum. 
- We need to make sure that version locking happens in package.json [todo]
- Keep as low maintenance as possible. any user can edit pages via markdown on github


### CSS styling

- tailwindcss
- @tailwindcss/typography
- @tailwindcss/forms
- hyperUI front page layout
