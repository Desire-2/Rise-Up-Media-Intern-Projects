

---

### **1. Project 1: Personal Portfolio Website**  
**Repo**: `RiseUpMedia-Portfolio-[StudentName]`  
**Steps**:  
1. **Git & GitHub Setup**:  
   - Create a repo on GitHub.  
   - Initialize with `README.md`, `.gitignore`, and MIT License.  
   - First commit: "Initial setup for ResUpMedia portfolio project."  
2. **HTML Structure**:  
   - Build sections:  
     - Hero banner with Rise Up Media’s motto: *"Empowering Innovation, Transforming Ideas."*  
     - Skills grid (include courses from Res Up Media’s training center, e.g., "Filmmaking," "ICT Skills").  
     - Projects section (placeholder for future internships).  
   - Add company logo to the header.  
3. **CSS Styling**:  
   - Use Rise Up Media’s brand colors (define in `styles.css` as CSS variables).  
   - Add hover effects for buttons (e.g., "Enroll Now" linking to training programs).  
   - Ensure mobile responsiveness with media queries.  
4. **Deployment**:  
   - Deploy to githubpage with a direct link.  
   - Add a "Powered by Rise Up Media" footer.  
5. **SEO Optimization**:  
   - Add meta tags (description: "A portfolio project for Rise Up Media’s Software Development Internship").  
   - Generate a sitemap.  

---

### **2. Project 2: Todo List App (Frontend)**  
**Repo**: `RiseUpMedia-TodoApp-[StudentName]`  
**Steps**:  
1. **Project Setup**:  
   - Fork Rise Up Media’s starter template (includes branding guidelines).  
   - Create a `develop` branch for active work.  
2. **JavaScript Functionality**:  
   - Add tasks with due dates and priority levels (High/Medium/Low).  
   - Implement local storage to persist tasks.  
   - Add a "Theme Toggle" (light/dark mode) using CSS variables.  
3. **Advanced Git**:  
   - Use `git rebase` to clean up commit history.  
   - Create pull requests for peer code reviews.  
4. **Testing**:  
   - Write Jest tests for core functions (e.g., adding/deleting tasks).  
5. **Documentation**:  
   - Add a `CONTRIBUTING.md` file explaining Res Up Media’s coding standards.  

---

### **3. Project 3: Blog API (Backend + MySQL)**  
**Repo**: `RiseUpMedia-BlogAPI-[StudentName]`  
**Steps**:  
1. **Project Scaffolding**:  
   - Initialize a Node.js app with Express.js.  
   - Structure folders: `routes`, `controllers`, `models`, `config`.  
2. **Database Design**:  
   - Create a `blogs` table with fields: `id`, `title`, `content`, `author`, `created_at`.  
   - Seed the database with sample posts about Res Up Media’s services (e.g., "How We Built Our Training Center").  
3. **API Development**:  
   - Add endpoints:  
     - `GET /api/blogs`: Fetch all blogs.  
     - `POST /api/blogs`: Create a new blog (admin-only, JWT-protected).  
   - Validate inputs with `express-validator`.  
4. **Company Integration**:  
   - Add a "Related Services" field linking blogs to Res Up Media’s offerings (e.g., "Learn Web Design with Us").  
5. **Postman Collection**:  
   - Export API endpoints to a shared Postman collection named `ResUpMedia-BlogAPI`.  

---

### **4. Project 4: Task Manager (Full-Stack)**  
**Repo**: `RiseUpMedia-TaskManager-[StudentName]`  
**Steps**:  
1. **Frontend-API Connection**:  
   - Fetch tasks from the backend using Axios.  
   - Add loading spinners (use Rise Up Media’s brand colors).  
2. **User Roles**:  
   - Admins (Rise Up Media staff) can delete/edit all tasks.  
   - Regular users can only manage their own tasks.  
3. **Real-Time Updates**:  
   - Integrate Socket.io for live task updates.  
4. **Database Optimization**:  
   - Add indexes to the `tasks` table for faster queries.  
5. **Deployment**:  
   - Dockerize the app with a `docker-compose.yml` file.  
   - Deploy the project.  

---

### **5. Project 5: User Authentication System**  
**Repo**: `RiseUpMedia-AuthSystem-[StudentName]`  
**Steps**:  
1. **Database Security**:  
   - Hash passwords using `bcryptjs` (salt rounds: 12).  
   - Add a `last_login` field to the `users` table.  
2. **OAuth Integration**:  
   - Allow sign-in via Google (using Res Up Media’s Google Cloud credentials).  
3. **Password Reset Flow**:  
   - Send emails via Rise Up Media’s domain (e.g., `noreply@resupmedia.rw`) using Nodemailer.  
4. **Rate Limiting**:  
   - Block brute-force attacks with `express-rate-limit`.  
5. **Frontend UI**:  
   - Customize error/success messages to match company branding.  

---

### **6. Project 6: DevOps & Deployment**  
**Repo**: `RiseUpMedia-Deployment-[StudentName]`  
**Steps**:  
1. **CI/CD Pipeline**:  
   - Configure GitHub Actions to run tests on every push to `main`.  
   - Auto-deploy to AWS Elastic Beanstalk if tests pass.  
2. **Monitoring**:  
   - Set up Prometheus/Grafana dashboards to track API health.  
3. **Backup Strategy**:  
   - Schedule daily MySQL backups to Res Up Media’s S3 bucket.  
4. **Load Testing**:  
   - Use Apache JMeter to simulate 1,000 concurrent users.  

---

### **7. Capstone Project: Event Booking Platform**  
**Repo**: `RiseUpMedia-EventPlatform-[StudentName]`  
**Steps**:  
1. **Feature Set**:  
   - Event discovery page (filter by category: "Gospel," "Sports").  
   - Ticket booking with QR codes (generate using `qrcode` npm package).  
   - Admin dashboard for Res Up Media staff to manage events.  
2. **Payment Integration**:  
   - Demo Stripe integration with test cards.  
   - Add a "Powered by Rise Up Media" footer on payment pages.  
3. **Analytics**:  
   - Track user behavior with Google Analytics (Res Up Media’s account).  
4. **Final Presentation**:  
   - Demo the platform to Res Up Media’s CEO and training team.  

---

### **Workflow Best Practices**  
1. **Daily Standups**:  
   - Interns share progress in Res Up Media’s groups.  
2. **Code Reviews**:  
   - Senior developers leave feedback directly on GitHub PRs.  
3. **Documentation**:  
   - All repos must include:  
     - `README.md` with setup instructions.  
     - `API_DOCS.md` for backend projects.  
     - `STYLE_GUIDE.md` for frontend consistency.  

---

### **Company Branding Integration**  
- **All Projects**:  
  - Use Res Up Media’s fonts (e.g., Poppins), logo, and color palette.  
  - Include a footer: "Developed during Rise Up Media’s Software Development Internship."    

---

**Empowering Innovation, Transforming Ideas.**  
**Res Up Media** | Nyamirambo Kuri 40 | +250 795029019  
