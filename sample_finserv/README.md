# Sample Finserv
- This database contains collections for a typical financial services application.


## Collections

### 1. accounts
> 1,746 documents
```typescript
interface Account {
    id: string
    account_id: number
    limit: number
    [products]: string
}
```

### 2. customers
> 500 documents
```typescript
interface Account {
    id: string
    username: string
    name: string
    address: string
    birthdate: {"$date": string}
    email: string
    active: boolean
    [accounts]: number
}
```
