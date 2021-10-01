# Dynalist
- To-do tasks and users database


## Collections

### 1. todos
> 200 documents
```typescript
interface Todo {
    userId: number
    id: number
    title: string
    completed: boolean
}
```

### 2. users
> 10 documents
```typescript
interface User {
  id: number,
  name: string,
  username: string,
  email: string,
  address: {
    street: string,
    suite: string
    city: string
    zipcode: string
    geo: {
      lat: string,
      lng: string
    }
  },
  phone: string,
  website: string,
  company: {
    name: string,
    catchPhrase: string,
    bs: string
  }
}
```
