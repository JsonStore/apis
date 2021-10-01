# Senate Data
- Contains randomized US Senate speeches organized as blog posts with randomly generated comments.


## Collections

### 1. posts
> 500 documents
```typescript
interface Post {
    id: string
    body: string
    permalink: string
    author: string
    title: string
    [tags]: string
    [comments]: {
        body: string
        email: string
        author: string
    }
    date: {"$date": string}
}
```
