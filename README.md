# Notion Clone

This is a Notion clone, a collaborative workspace and note-taking application designed to help individuals and teams organize their tasks, projects, and ideas effectively.

# Outputs
![Screenshot (197)](https://github.com/Shreya-Reddy-A/Notion-Clone/assets/122392746/31a41cb9-f34a-4bdf-abd5-433dca89384c)
![Screenshot (238)](https://github.com/user-attachments/assets/ff7e7113-769d-4773-aa63-e149dcf02c7e)
![Screenshot (239)](https://github.com/user-attachments/assets/92525084-f943-40f1-b9e9-43282f6aa852)


## Getting Started

To get started with the Notion clone, follow these steps:

1. **Clone the Repository**:
   - Clone this repository to your local machine.
     ```
     git clone https://github.com/Shreya-Reddy-A/Notion-Clone.git
     ```

2. **Install Dependencies**:
   - Navigate into the cloned directory and install the necessary dependencies.
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
   - Deployment used by `npx convex dev`
     ```
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
     CLERK_SECRET_KEY=
     ```

4. **Run the Application**:
   - Start the development server to run the application locally.
     
     Front-end:
     ```
     npm run dev
     ```
     Back-end:
     ```
     npx convex dev
     ```
5. **Access the Application**:
   - Once the server is running, you can access the Notion clone by visiting `http://localhost:3000` in your web browser.

Tutorial followed from : (https://www.youtube.com/watch?v=0OaDyjB9Ib8&t=27288s)
