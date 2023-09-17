# synonyms-backend
Go to frontend url: https://synonyms-tool.vercel.app/ to try the synonyms tool, or use postman to query the endpoints which is listed below.
## query endpoints
- search a synonyms GET request: `https://frantic-duck-waders.cyclic.cloud/api/synonyms?search=sisters` sister is the word you are searching, and it should return all the synonyms for word `sister` if they are stored in the system.
- add a synonyms POST request: `https://frantic-duck-waders.cyclic.cloud/api/synonyms`
an example json object: [
	"papa", "daughter", "son", "sisters", "family", "dog", "hound"
]
- edit a synonyms POST request: `https://frantic-duck-waders.cyclic.cloud/api/synonyms`
json object {word: "kid", synonymsList: ["child", "son"]}