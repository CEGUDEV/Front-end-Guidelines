
# Front-end Guidelines

Guidelines document for Front-end developers CEGU Indonesia


## Table of Contents

 - [Tech Stack](https://github.com/CEGUDEV/Front-end-Guidelines/tree/main?tab=readme-ov-file#tech-stack)
 - [Color References](https://github.com/CEGUDEV/Front-end-Guidelines/tree/main?tab=readme-ov-file#color-reference)
 - [Commit Message Standardization](https://github.com/CEGUDEV/Front-end-Guidelines/tree/main?tab=readme-ov-file#commit-message-standardization)


## Tech Stack

**HTML:** HTML 5

**Style:** Tailwindcss

**Script:** ES6

**Framework/Lib:** Next.js, Shadcn, Lucide-react


## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Primary | ![#3E4EA2](https://via.placeholder.com/10/3E4EA2?text=+) #3E4EA2 |
| Secondary | ![#FFC224](https://via.placeholder.com/10/FFC224?text=+) #FFC224 |



## Commit Message Standardization
```git
${Ticket} - {subject}

${body} //optional

${references} //optional
```

#### Ticket
This should be filled by number ticket of your task
- 1xxxx : add new feature
- 2xxxx : a bug fixing
- 3xxxx : update depencies or build configuration

#### Example

```
1022 - product review detail implementation

register new routes for review detail page,
add new pages component for review detail,
breakdown each content into smaller components (review info, review rating, review other product)
create interaction with lazy load component using intersection observer

https://app.zeplin.io/project/123123
https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API
https://stackoverflow.com/questions/43663665/what-is-the-use-case-of-intersectionobserver
```

```
2111 - fixing broken image in my review page if backend didn't return the correct image url

add default image if the image is not found 
```
## Authors

- [@mw](https://github.com/MlkyWayy)


## Feedback

If you have any feedback, please reach out to us at cegudev@gmail.com
