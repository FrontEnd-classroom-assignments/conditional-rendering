
# Ehdollinen renderöinti
Use props and state to conditionally render components based on given boolean flags.

### 1. Luo ProfileCard komponentti
Luo React komponentti nimeltä `ProfileCard`.

Komponentti vastaanottaa seuraavat props:it:
```
name: string
age: number
showDetails: boolean
```
Komponentin toiminta:
- Komponentti näyttää aina `name` props:in arvon
- `age` props:in arvo näytetään vain jos `showDetails` arvo on `true`.

### 2. Display ProfileCard comp
`App` component renders two `ProfileCard` components:
- One with `showDetails` set to `true`.
- One with `showDetails` set to `false`.

**Example output:**

![Conditional render](./src/assets/conditional_render.png)
