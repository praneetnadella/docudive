Please populate backend/.env with the following:

`
export OPENAI_API_KEY={OPENAI_KEY}
export PINECONE_API_KEY={PINECONE_API_KEY}
`

Then to run use the following commands:

`docker-compose up`


To Add/Fix:

- Upstash: FastAPI Caching (store frequently accessed embeddings?)
- Improve RAG
- Create User Environment
    - Auth
    - Specific storage
- Create Workspace
    - Users can create separate workspaces (maybe by different topic)
        - Separated by the document the user uploads in that workspaces
- Ratelimit Queries (so server not overloaded)
- Suggested questions to ask
- Option to search the web for more information (and indicate that maybe have a button?)
- Implement a confidence score (how confident it is in the answer)
    - allow users to filter answers by confidence scores
- Encryption of sensitive documents
- Add user output feedback (to improve model answers)
- Suggest documents from public DB for user
- Previous question context


- host on URL
    - then do CI/CD
    - then implement Terraform once previous done
