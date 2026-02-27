# barebonesWP
Tools and strategies to minimise bloat on a block-based WordPress template site that's 2026 AI ready. Hopefully useful for other authors or writers with Author Profiles on the internet that they may nolonger control. SEO Framework is the gun but a little tailoring's required. BEST, friends. 


# Site Standards & Technical Documentation 
 
## 1. Infrastructure, Security & Hosting 
* **VentraIP:**  

High-performance Australian hosting providing PHP 8.2 stability and server-side management. 
* **Cloudflare:**  

Primary DNS and SSL management layer. Utilised as a Web Application Firewall (WAF) to block rogue AI behaviour and optimise global performance. 
* **Cloudflare Turnstile:**  

Privacy-first, WCAG-compliant bot defence for contact forms, ensuring a frictionless user experience without traditional CAPTCHAs. 
* **.htaccess Management:**  

Manually verified standard WordPress directives.   

* Handles Pretty Permalinks and passes Authorisation headers for REST API stability. 
* Custom rules must be placed above the `# BEGIN WordPress` marker to prevent overwriting. 
 
## 2. Creative & Visual Identity 
* **Affinity Workflow:**  

Hand-drawn sketches converted into digital assets.  

**Affinity**  

Used to convert logos to curves (pixels to vector) for professional scalability. 
* **Colour Space Optimisation:**  

Visual assets utilise a simplified colour space to ensure consistency and performance across web displays. 
* **Favicon Generator:**  

Utilised strictly to create the multi-platform site icon assets from the finalised branding. 
* **WebP Conversion:**  

Optimisation step for all photography assets to ensure fast mobile load times and browser compatibility. 
 
## 3. Media & Content Management 
* **FileBird:**  

Utilised for media library folder management. This ensures a logical, organised backend structure for photography and document assets, improving workflow efficiency. 
* **Semantic Navigation:**  

Leveraging WordPress tags for logical navigation that prioritises screen-reader logic. 
 

## 4. Technical SEO & GEO Strategy 
* **The SEO Framework (TSF):**  

Lightweight metadata management. 
* **Manual Control:**  
Automatic title generation is DISABLED to ensure 100% editorial control. 

* **Archive Control:**  
TSF handles "noindex" and "disallow" for tags to keep the index clean. 

 

* **JSON-LD (WPCode):**  

Surgical insertion of structured data to define "Entity" relationships (Person/Author) in the Header for Generative Engine Optimisation (GEO). 
Used WPCode to insert text the removed extra socials identities inserted by SEO Framework

* **KeySearch & AlsoAsked:**  

In-depth keyword analysis and intent mapping to inform content structure. 

* **Asset Package:**  

Articles require SEO Title, SEO sub-heads, URL slug, Meta description, Alt text options  

* **Organic Keyword Integration:**  

Keyword phrases and keywords are woven naturally into prose and sub-heads; they are NEVER included in meta keyword tags. 
 
 
## 5. Technical Auditing & Support 

* **SEOptimer:** 

Primary crawler support for technical audits and on-page SEO health checks. 
* **Google Search Console:** 

Real-time monitoring of indexing health and manual crawl requests. 
* **Manual robots.txt:**  

Requests well-behaved AI bots avoid specific sections while allowing full script access (JS/CSS) for accurate rendering. 
 
## 6. Accessibility & Strategic Partnership 
* **WCAG Compliance:**  
Core architecture "proofing" using the **WAVE Evaluation Tool** to ensure compliance. 
* **Strategic AI Partnership:** 
Gemini is utilised as a collaborator for building GEO and SEO assets, navigating technical roadblocks, and maintaining a "low-bloat" development methodology. 

 
