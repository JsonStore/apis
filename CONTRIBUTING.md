## Guidelines
- contribute an entire directory representing a mock database
- should contain at least one collection with appropriate data
- add a README.md file within the directory according to [Repo Structure](https://github.com/JsonStore/apis/blob/main/CONTRIBUTING.md#readme-structure) 
- do not create a PR changing directories & collection files thats are not contributed by you
- only create PRs with significant changes


## Naming Conventions  

- Main directory: snake case ` eg: sample_database`
- Collection files: camel case `eg: sampleCollection.json`
- Document keys: camel case `eg: {"sampleKey": "some value"}`


### README Structure
```markdown
# database name
- brief about the database and consisting collections

## Collections

### 1. firstCollection
> n documents
{ typescript interface for document }

### 2. secondCollection
> m documents
{ typescript interface for document }

...

...

```
> refer this [example](./dynalist/README.md)