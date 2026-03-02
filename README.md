# barebonesWP
Tools and strategies to minimise bloat on a block-based WordPress template site that's 2026 AI ready. I used WordPress' Twenty-Twenty-Four template that offers blog functionality. Hopefully useful for other authors or writers with Author Profiles on the internet that they may nolonger control. 
The SEO Framework is the gun but a little tailoring's required. BEST, friends. 

# Site Standards & Technical Documentation 
 
## 1. Infrastructure, Security & Hosting 
* **VentraIP:**  
[VentraIP](https://ventraip.com.au) High-performance Australian hosting providing PHP 8.3 (since updated, to suit Contact Form 7 plugin) stability and server-side management. 

* [**Removed Cloudflare** - overactive honeypot app trapped my own site. Also discovered CF issued 418 errors when robots.txt was called by bots and crawlers]
** Cloudflare:  
[CloudFlare](http://cloudflare.com) Primary DNS and SSL management layer. Utilised as a Web Application Firewall (WAF) to block rogue AI behaviour and optimise global performance. -- turned off this crazy honeypot app after it trapped my own site :O  
** **Cloudflare Turnstile:**  
Privacy-first, WCAG-compliant bot defence for contact forms, ensuring a frictionless user experience without traditional CAPTCHAs. 

* **.htaccess Management:**  
Manually verified standard WordPress directives. Edited within CPanel, via VentraIP.   
* Handles Pretty Permalinks and passes Authorisation headers for REST API stability. 
* Custom rules must be placed above the `# BEGIN WordPress` marker to prevent overwriting. 
* [Security Headers](https://securityheaders.com/) Testing platform for modern security
 
## 2. Creative & Visual Identity 
* **Favicon/icon Workflow:**  
Hand-drawn sketches converted into digital assets.  

**Affinity**  
[Affinity](https://www.affinity.studio/) Used to convert logos to curves (pixels to vector) for professional scalability. 

* **Favicon Generator:**  
[https://favicon.io/](https://favicon.io/) Used to create the multi-platform site icon assets from the finalised branding.

* **Image Optimisation:**  
Reduce image size, main: long-side 2100; post assets: long-side 1500
Visual assets utilise a simplified colour space to ensure consistency and performance across web displays.

* **WebP Conversion:**  
Optimisation step for photography assets to ensure fast mobile load times and browser compatibility.

* **Forms:**
[Contact Form 7](https://wordpress.org/plugins/contact-form-7/) Forms that support WCAG accessibility. Helpful for creating a bridge to the Substack link

* **Email database:**
[substack.com](https://substack.com/@rachaelwritesforreal) Easy and free solution for creating a secure and legal email database on an external server.
 
## 3. Media & Content Management 
* **FileBird plugin WordPress plugin:**  
[FileBird](https://wordpress.org/plugins/filebird/) Utilised for media library folder management. This ensures a logical, organised backend structure for photography and document assets, improving workflow efficiency. 

* **Semantic Navigation:**  
Leveraging WordPress tags for logical navigation that prioritises screen-reader logic. 
 
## 4. Technical SEO & GEO Strategy 
* **The SEO Framework (TSF) WordPress plugin:**  
[The SEO Framework](https://wordpress.org/plugins/autodescription/) Lightweight metadata management & canonical priorities.
* **Manual Control:**  
Automatic title generation is DISABLED to ensure 100% editorial control. 
* **Archive Control:**  
TSF handles "noindex" and "disallow" for tags to keep the index clean. 

* **JSON-LD (WPCode WordPress plugin):**  
[WPCode](https://wordpress.org/plugins/insert-headers-and-footers/) Insert structured daa to define "Entity" relationships (Person/Author) in the Header for Generative Engine Optimisation (GEO).
Used WPCode to insert instructions to removed extra socials identities automatically inserted by SEO Framework.

* **KeySearch & AlsoAsked:**  
[KeySearch](https://www.keysearch.co/) In-depth keyword analysis and intent mapping to inform content structure. [AlsoAsked](https://alsoasked.com/) Assist with search intent.

* **Test JSON-LD structure: **
[Schema Org](https://validator.schema.org/)) Site for testing your JSON-LD structure.

* **Asset Package:**
Articles require SEO Title, Title,  SEO sub-heads, URL slug, Meta description, image file names, Alt text options  

* **Organic Keyword Integration:**  
Keyword phrases and keywords are woven naturally into prose and sub-heads; they are NEVER included in meta keyword tags. 
 
## 5. Technical Auditing & Support 
* **SEOoptimer:** 
[SEOoptimer](seoptimer.com) Primary crawler support for technical audits and on-page SEO health checks. 

* **Google Search Console:**
[Google Search Console](https://search.google.com/search-console/about)
Real-time monitoring of indexing health and manual crawl requests. 

* **Manual robots.txt:**  
Requests well-behaved AI bots avoid specific sections while allowing full script access (JS/CSS) for accurate rendering. Note on manual robots.txt. The SEO Framework typically renders a robots.txt but will respect a physical file.

* **Testing how Crawlers see the site**
[CrawlerCheck](https://crawlercheck.com/) Ensuring the correct robots.txt is visible to crawlers and that instructions to bots are clear

* **Mobile & Desktop rendering**
[MobileMoxie](https://mobilemoxie.com/tools/mobile-page-test/) Up to three checks daily on two devices, with Australia's most popular devices included.
 
## 6. Accessibility & Strategic Partnership 
* **WCAG Compliance:**
[WAVE Evaluation Tool](https://wave.webaim.org/)Core architecture "proofing" using the **WAVE Evaluation Tool** to ensure compliance.

* **Strategic AI Partnership:** 
[Gemini](https://gemini.google.com/app)Using Gemini to assist with GEO and SEO assets, navigating technical roadblocks, writing code and maintaining a "low-bloat" development methodology. 
