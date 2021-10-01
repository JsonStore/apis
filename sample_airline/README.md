# Sample Airline
- Contains information of airline routes, with source and destination airports, the service airline and the type of airplane.


## Collections

### 1. routes
> 66,985 documents
```typescript
interface Route {
    id: string
    airline: {
        id: number
        name: string
        alias: string
        iata: string
    }
    src_airport: string
    dst_airport: string
    codeshare: string
    stops: number
    airplane: string
}
```
