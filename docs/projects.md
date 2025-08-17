# Projects

## Generator Screaming Bones
**React + TypeScript Project Generator**

Yeoman generator implementing Screaming Architecture principles with opinionated tooling setup including Vite, ESLint, Prettier, and optional Tailwind CSS integration. Organizes code by business domain rather than technical layers, creating self-documenting project structures.

**Challenge Solved**

- Eliminated repetitive project setup and enforced consistent architecture patterns across React + TypeScript projects
- Maintained flexibility for different use cases while standardizing development workflow
- Reduced project initialization time from manual hours to automated minutes

**Architecture Decision**

- Implemented domain-driven folder structure where folder organization communicates application purpose
- Replaced traditional technical layer organization with business domain focus
- Improved code maintainability and developer onboarding efficiency

![Screaming-Bones Process Flow](assets/images/screaming-bones-flow.png)
*CLI scaffolding tool process flow showing initialization, user input validation, configuration assembly, and project generation stages.*

**Technical Implementation**

- Performance: 30-90 second generation time with 2-3 second cold start, ~500ms template processing per file
- Technologies: Node.js, Yeoman, TypeScript, Vite, ESLint 9, Prettier 3.x
- Key Features: Interactive CLI validation, EJS templating, conditional feature setup, Git initialization
- Repository: [github.com/AngelCodes95/generator-screaming-bones](https://github.com/AngelCodes95/generator-screaming-bones)
- NPM Package: [npmjs.com/package/generator-screaming-bones](https://www.npmjs.com/package/generator-screaming-bones)

---

## Together, A Calendar App for 100Devs
**Open Source MERN Stack Contributions**

Contributed critical bug fixes to open source group calendar application for the 100Devs community. Resolved production OAuth authentication failures affecting user login in Fly.io deployment environment and restored essential session management functionality. Successfully merged multiple pull requests to production.

**Challenge Solved**

- Diagnosed and fixed OAuth authentication failures in production environment
- Deployed local Fly.io instance with MongoDB cluster and Discord authentication to replicate production conditions
- Accurately tested fixes before production deployment to prevent further service disruption

**Technical Implementation**

- Built local production environment replica using Fly.io CLI
- Configured MongoDB Atlas connection strings and implemented Discord OAuth flow debugging
- Isolated session persistence issues in containerized deployment environment
- Collaborated with maintainers to ensure code quality and testing standards

**Technical Details**

- Technologies: MongoDB, Express.js, React, Node.js, OAuth, Fly.io
- Key Features: Production debugging, OAuth implementation, session management, deployment troubleshooting
- Repository: [github.com/AngelCodes95/together](https://github.com/AngelCodes95/together)

---

## StayingInLJ - Social Commerce Platform
**Full-Stack E-Commerce Application**

Vintage furniture marketplace combining social media engagement with e-commerce functionality. Serves San Diego vintage business with nationwide reach through online sales and physical retail presence at Sea Hive Station.

**Challenge Solved**

- Transformed exclusively offline vintage business operation into digital-first marketplace
- Enabled nationwide customer reach while preserving intimate browsing experience
- Created unique platform combining Instagram-style social interactions with full e-commerce functionality
- Maintained brand identity and customer experience during digital transformation

**Business Impact**

- Complete marketplace solution with automated order processing and multi-channel fulfillment
- Stripe payment integration with guest checkout and shopping cart functionality
- Shipping automation via Shippo API supporting pickup, local delivery, and nationwide shipping
- Achieved enterprise functionality at minimal monthly infrastructure cost
- Scalable architecture designed to support premium tier integrations as business grows

![Portion of About page](assets/images/silj-main-feed.jpg)

**Technical Architecture**

- Backend: Node.js/Express.js with MongoDB Atlas for scalable data management
- Payments: Stripe API with comprehensive checkout and shopping cart functionality
- Media: Cloudinary integration with owner-controlled crop positioning and optimization
- Security: Helmet.js implementation, rate limiting, and authentication management
- Infrastructure: Render hosting with health monitoring and automated scaling capabilities

**Key Features**

- Polaroid-style social feed with interactive engagement system
- Individual like system and right-sliding comment panels for enhanced user experience
- Google OAuth 2.0 and local authentication for flexible user access
- Owner dashboard with business analytics and inventory management
- Mobile-responsive glassmorphism design optimized for all devices

![Main Feed Example](assets/images/silj-about.jpg)

## Interactive Portfolio
**3D Wireframe Pyramid Portfolio**

Unique portfolio experience featuring 3D wireframe pyramids with physics-based animations, SVG rendering, and responsive touch controls. Demonstrates advanced mathematical concepts and interactive web development techniques.

**Challenge Solved**

- Created memorable, interactive portfolio showcasing technical creativity and mathematical proficiency
- Maintained professional presentation while implementing complex 3D animations
- Achieved optimal performance across desktop and mobile devices without external libraries
- Demonstrated advanced JavaScript capabilities through custom physics implementations

**Technical Implementation**

- Built custom 3D rendering engine using vanilla JavaScript and SVG
- Implemented physics-based rotation and animation systems from mathematical fundamentals
- Developed responsive touch control system for mobile device interaction
- Optimized performance through efficient rendering loops and memory management

**Technical Details**

- Technologies: JavaScript, SVG, 3D Mathematics, CSS Animations
- Key Features: Physics simulations, mobile touch controls, color-changing animations, responsive design
- Live Demo: [angel-vazquez.com](https://angel-vazquez.com)
- Repository: [github.com/AngelCodes95/angel-vazquez-com](https://github.com/AngelCodes95/angel-vazquez-com)

---

**Technical Focus Areas**

- Architecture patterns and code organization over framework dependency
- Developer experience optimization and tooling
- Interactive web experiences and animation techniques
- Modern JavaScript ecosystem and build automation

**Interests & Currently learning**

- CI/CD workflows
- Yaml
- Rust
- Python

---

[Click to go to the Skills Section](skills.md)