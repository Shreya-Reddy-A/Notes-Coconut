# Notion Clone

This is a Notion clone, a collaborative workspace and note-taking application designed to help individuals and teams organize their tasks, projects, and ideas effectively.

# Output
![Screenshot (197)](https://github.com/Shreya-Reddy-A/Notion-Clone/assets/122392746/31a41cb9-f34a-4bdf-abd5-433dca89384c)

## Getting Started

To get started with the Notion clone, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.
   ```
   git clone https://github.com/Shreya-Reddy-A/Notion-Clone.git
   ```

2. **Install Dependencies**: Navigate into the cloned directory and install the necessary dependencies.
   ```
   cd notion-clone
   npm i
   ```

3. **Generate Keys**: 

- Clerk.com for CLERK_SECRET_KEY
  ```
  CONVEX_DEPLOYMENT=
   NEXT_PUBLIC_CONVEX_URL=
  ```
- EdgeStore for EDGE_STORE_ACCESS_KEY
  
   ```
  EDGE_STORE_ACCESS_KEY=
  EDGE_STORE_SECRET_KEY=
  ```
 
```js
# Deployment used by `npx convex dev`

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

```


1. **Run the Application**: Start the development server to run the application locally.
   
   Front-end:
   
   ```
   npm run dev
   ```
   Back-end:
   
   ```
   npx convex dev
   ```
2. **Access the Application**: Once the server is running, you can access the Notion clone by visiting `http://localhost:3000` in your web browser.
