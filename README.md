# ej2-job-manager

- **What we will build**
  - a useful, functional full-stack MERN site which allows you to collect, save and display information about job leads
    - this is the beginning of a project which will become a site that managers your job seeking process
  - data will be saved in a database at your MongoDB Atlas database and will access your backend API at Heroku
  - frontend will be at Netlify and will access your API at Heroku
  - in this version, this site will be read-only
  - you will have one local directory for the project called **ejt-job-manager-project** where `ejt` are your initials (don't use `ejt` since those are my initials)
    - inside this folder you will have two projects:
      - **ejt-job-manager-backend**
        - this will also be the name of your
          - backend repository at GitHub
          - your app at Heroku
        - Heroku app names must be 30 characters or less
        - the URL to your backend API will be: `http://ejt-job-manager-backend.herokuapp.com`
      - **ejt-job-manager**
        - this will be the name of your
          - frontend repository at GitHub
          - your app at Netlify
        - your Netlify URL will be called http://ejt-job-manager.netlify.app
          - it doesn't have the word `frontend` in it since will be an outward-facing URL that you will give to other people in order for them to log into your site
- **What we will use:**
  - Node/Express and MongoDB Atlas will be used for the backend
  - React (Vite) will be used for the frontend
