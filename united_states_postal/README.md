# United States Postal
- Contains United States general cities postal/zip code data.


## Collections

### 1. postalCodes
> 29,470 documents
```typescript
interface PostalCode {
    id: string
    city: string
    zip: string
    loc: {
        y: number
        x: number
    }
    pop: number
    state: string
}
```
