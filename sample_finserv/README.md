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
