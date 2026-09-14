# 14-Day Software Engineering End-to-End Study Plan

## Day 1: Arrays & Strings (4 hours)
- **Theory**: Arrays basics, Strings manipulation (30 min)
  - Resource: https://github.com/yangshun/tech-interview-handbook/blob/master/README.md#array-and-string
- **Coding Problems** (2 hours):
  - LeetCode 26. Remove Duplicates from Sorted Array
  - LeetCode 27. Remove Element
  - LeetCode 28. Find the Index of the First Occurrence in a String
  - LeetCode 58. Length of Last Word
  - LeetCode 125. Valid Palindrome
  - LeetCode 283. Move Zeroes
  - LeetCode 344. Reverse String
  - LeetCode 387. First Unique Character in a String
  - LeetCode 412. Fizz Buzz
  - LeetCode 415. Add Strings
- **MCQs** (30 min): 10 MCQs from Tech Interview Handbook Arrays & Strings section
- **Mock Interview** (30 min): Peer mock interview focusing on array/string problems (use Pramp)

## Day 2: Linked Lists (4 hours)
- **Theory**: Singly, doubly linked lists, pointer manipulation (30 min)
  - Resource: https://github.com/yangshun/tech-interview-handbook/blob/master/README.md#linked-list
- **Coding Problems** (2 hours):
  - LeetCode 203. Remove Linked List Elements
  - LeetCode 206. Reverse Linked List
  - LeetCode 21. Merge Two Sorted Lists
  - LeetCode 141. Linked List Cycle
  - LeetCode 142. Linked List Cycle II
  - LeetCode 160. Intersection of Two Linked Lists
  - LeetCode 19. Remove Nth Node From End of List
  - LeetCode 234. Palindrome Linked List
  - LeetCode 25. Reverse Nodes in k-Group
  - LeetCode 148. Sort List
- **MCQs** (30 min): 10 MCQs from Tech Interview Handbook Linked List section
- **Mock Interview** (30 min): Peer mock interview focusing on linked list problems

## Day 3: Trees (4 hours)
- **Theory**: Binary trees, BST, traversal (30 min)
  - Resource: https://github.com/yangshun/tech-interview-handbook/blob/master/README.md#tree
- **Coding Problems** (2 hours):
  - LeetCode 104. Maximum Depth of Binary Tree
  - LeetCode 101. Symmetric Tree
  - LeetCode 100. Same Tree
  - LeetCode 226. Invert Binary Tree
  - LeetCode 112. Path Sum
  - LeetCode 113. Path Sum II
  - LeetCode 257. Binary Tree Paths
  - LeetCode 404. Sum of Left Leaves
  - LeetCode 513. Find Bottom Left Tree Value
  - LeetCode 543. Diameter of Binary Tree
- **MCQs** (30 min): 10 MCQs from Tech Interview Handbook Tree section
- **Mock Interview** (30 min): Peer mock interview focusing on tree problems

## Day 4: Graphs (4 hours)
- **Theory**: Graph representation, BFS, DFS (30 min)
  - Resource: https://github.com/yangshun/tech-interview-handbook/blob/master/README.md#graph
- **Coding Problems** (2 hours):
  - LeetCode 200. Number of Islands
  - LeetCode 207. Course Schedule
  - LeetCode 210. Course Schedule II
  - LeetCode 133. Clone Graph
  - LeetCode 127. Word Ladder
  - LeetCode 785. Is Graph Bipartite?
  - LeetCode 1192. Critical Connections in a Network
  - LeetCode 841. Keys and Rooms
  - LeetCode 994. Rotting Oranges
  - LeetCode 130. Surrounded Regions
- **MCQs** (30 min): 10 MCQs from Tech Interview Handbook Graph section
- **Mock Interview** (30 min): Peer mock interview focusing on graph problems

## Day 5: Dynamic Programming (4 hours)
- **Theory**: DP principles, memoization, tabulation (30 min)
  - Resource: https://github.com/yangshun/tech-interview-handbook/blob/master/README.md#dynamic-programming
- **Coding Problems** (2 hours):
  - LeetCode 70. Climbing Stairs
  - LeetCode 53. Maximum Subarray
  - LeetCode 322. Coin Change
  - LeetCode 198. House Robber
  - LeetCode 213. House Robber II
  - LeetCode 121. Best Time to Buy and Sell Stock
  - LeetCode 122. Best Time to Buy and Sell Stock II
  - LeetCode 300. Longest Increasing Subsequence
  - LeetCode 64. Minimum Path Sum
  - LeetCode 1143. Longest Common Subsequence
- **MCQs** (30 min): 10 MCQs from Tech Interview Handbook DP section
- **Mock Interview** (30 min): Peer mock interview focusing on DP problems

## Day 6: System Design Basics (4 hours)
- **Theory**: Scalability, load balancing, caching, databases (1 hour)
  - Resources:
    - https://github.com/donnemartin/system-design-primer
    - https://www.youtube.com/watch?v=-W9F__D3oY4 (System Design Interview - Insider's Guide)
- **Coding Problems** (1 hour): System design problems (no coding, but think through)
  - Design a URL shortener (like bit.ly)
  - Design a rate limiter
  - Design Twitter timeline
- **MCQs** (30 min): 10 MCQs from System Design Primer (flashcards)
- **Mock Interview** (1.5 hours): Mock system design interview with peer (use Pramp or interviewing.io)

## Day 7: Python FastAPI + SQL (4 hours)
- **Theory**: FastAPI basics, Pydantic, SQLAlchemy ORM (1 hour)
  - Resources:
    - https://fastapi.tiangolo.com/tutorial/
    - https://docs.sqlalchemy.org/en/20/tutorial/
- **Coding Problems** (2 hours): Build a simple CRUD API for a blog
  - Create endpoints: GET /posts, POST /posts, GET /posts/{id}, PUT /posts/{id}, DELETE /posts/{id}
  - Use SQLite for simplicity
- **MCQs** (30 min): 10 MCQs on Python/FastAPI/SQL (from online quizzes)
- **Mock Interview** (30 min): Peer code review of the API

## Day 8: React TypeScript (4 hours)
- **Theory**: React hooks, TypeScript basics (1 hour)
  - Resource: https://www.youtube.com/watch?v=DxqiBrERv6o (provided)
- **Coding Problems** (2 hours): Build a todo app with React + TypeScript
  - Features: add, remove, mark complete, filter
  - Use functional components and hooks
- **MCQs** (30 min): 10 MCQs on React/TypeScript (from online quizzes)
- **Mock Interview** (30 min): Peer code review of the todo app

## Day 9: Docker (4 hours)
- **Theory**: Docker basics, images, containers, Dockerfile (1 hour)
  - Resource: https://docs.docker.com/get-started/
- **Coding Problems** (2 hours): Containerize the FastAPI app from Day 7
  - Write Dockerfile for FastAPI
  - Write docker-compose.yml to run FastAPI and PostgreSQL
  - Run the containerized app
- **MCQs** (30 min): 10 MCQs on Docker (from online quizzes)
- **Mock Interview** (30 min): Peer review of Dockerfile and docker-compose

## Day 10: CI-CD (GitHub Actions) (4 hours)
- **Theory**: GitHub Actions basics, workflows, CI/CD pipelines (1 hour)
  - Resource: https://docs.github.com/en/actions/quickstart
- **Coding Problems** (2 hours): Set up CI/CD for the React + FastAPI app
  - Create GitHub Actions workflow to:
    - Run tests on push
    - Build Docker images
    - Push to Docker Hub (or GitHub Packages)
- **MCQs** (30 min): 10 MCQs on GitHub Actions (from online quizzes)
- **Mock Interview** (30 min): Peer review of the workflow files

## Day 11: AI RAG LLMs Basics (4 hours)
- **Theory**: Introduction to LLMs, embeddings, vector stores, RAG (1 hour)
  - Resources:
    - https://huggingface.co/docs/transformers/index
    - https://www.pinecone.io/learn/rag/
- **Coding Problems** (2 hours): Build a simple RAG pipeline
  - Use Hugging Face transformers for embeddings
  - Use FAISS or Pinecone for vector store
  - Create a chatbot that answers questions from a given text
- **MCQs** (30 min): 10 MCQs on AI/RAG/LLMs (from online quizzes)
- **Mock Interview** (30 min): Peer discussion on the RAG implementation

## Day 12: Integrated Project Part 1 (Backend) (4 hours)
- **Theory**: Connecting backend and frontend (30 min)
- **Coding Problems** (3.5 hours): 
  - Extend the FastAPI API to include user authentication (JWT)
  - Add endpoints for user registration and login
  - Protect the blog endpoints with authentication
  - Use SQLAlchemy with PostgreSQL (via Docker)
- **MCQs** (30 min): 10 MCQs on authentication and security
- **Mock Interview** (30 min): Peer review of the auth implementation

## Day 13: Integrated Project Part 2 (Frontend) (4 hours)
- **Theory**: React state management, API consumption (30 min)
- **Coding Problems** (3.5 hours):
  - Build a frontend for the blog app using React + TypeScript
  - Features: view posts, create post (authenticated), edit/delete own posts
  - Use React Router for navigation
  - Use Axios or fetch to communicate with the FastAPI backend
- **MCQs** (30 min): 10 MCQs on React state management and API calls
- **Mock Interview** (30 min): Peer review of the frontend code

## Day 14: Final Review & Practice (4 hours)
- **Theory**: Review weak areas (1 hour)
- **Coding Problems** (2 hours): 
  - Solve 5 mixed LeetCode problems (from any topic)
  - Take a full-length mock interview (using Pramp or interviewing.io)
- **MCQs** (30 min): 20 MCQs mixed (from all sections)
- **Mock Interview** (1 hour): Final mock interview and feedback

## Resources Summary
- Tech Interview Handbook: https://github.com/yangshun/tech-interview-handbook
- NeetCode Top 150: https://leetcode.com/discuss/post/5808617/heres-the-list-of-neetcodes-top-150-ques-rydm
- LeetCode TOP 100: https://leetcode.com/problem-list/arw5ns9e
- FastAPI tutorial: https://fastapi.tiangolo.com/tutorial/
- SQLAlchemy tutorial: https://docs.sqlalchemy.org/en/20/tutorial/
- React TypeScript tutorial: https://www.youtube.com/watch?v=DxqiBrERv6o
- Docker docs: https://docs.docker.com/get-started/
- GitHub Actions CI/CD: https://docs.github.com/en/actions/quickstart
- Hugging Face Transformers: https://huggingface.co/docs/transformers/index
- Pinecone RAG: https://www.pinecone.io/learn/rag/
- System Design Primer: https://github.com/donnemartin/system-design-primer

## Notes
- Adjust hours based on your pace; the total is approximately 4 hours per day.
- For mock interviews, try to find a peer or use platforms like Pramp (free) or interviewing.io.
- MCQs can be found on sites like GeeksforGeeks, LeetCode discuss, or handmade from the resources.
- Always try to understand the solution, not just memorize.