# Dine NYC
- This database contains GeoJSON data about restaurants and neighborhoods of New York City.


## Collections

### 1. neighborhoods
> 195 documents
```typescript
interface Neighborhood {
    id: string
    geometry: { 
        [coordinates]: [number,number]
        type: string
    }
    name: string
}
```

### 2. restaurants
> 25,359 documents
```typescript
interface Restaurant {
    id: string
    address: {
        building: string
        coord: [number,number]
        street: string
        zipcode: string
    }
    borough: string
    cuisine: string
    [grades]: {
        date: {"$date":string}
        grade: string
        score: number
    }
    name: string
    restaurant_id: string
}
```
