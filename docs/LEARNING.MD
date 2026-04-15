## PART 1
- define response and request as structs for stability
- rate limiting
- time.Duration
- go fiber package

-- learnt sth major here that as been affecting me

in go.mod 

```bash
## use like this when go mod is i root director
module github.com/bkoimett/url-shortener

## use this when go mod is in other directory like api/
## as in my case here
module github.com/bkoimett/url-shortener/api
```

## PART 2
- bodyParser - method from fiber object that parses json into struct 
- rate limiting : checks if in db and gives 30 mins 
- input validation
- check fo domain error
- 

## PART 3
- database creates connection to database and context
- resolve, resolves the shorten url into the real url
