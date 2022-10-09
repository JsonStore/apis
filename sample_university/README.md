# Sample University
- Contains student grade information on a given class, including scores on different assessments.
- Student Information includes id, student id, scores, classid of a student 

## Collections

### 1. grades
> 100,000 documents
```typescript
interface Grade {
    id: string
    student_id: number
    [scores]: {
        type: string
        score: number
    }
    class_id: number
}
```
