# exam-html
📄 Project Documentation: Cycle Website Wireframe
📘 Project Title:
Cycle Web Wireframe

👤 Developed By:
Sagar
BCA Final Year Student

🔧 Technologies Used
HTML5

Bootstrap Icons (CDN)

Embedded Media (YouTube iframe)

🧱 Project Structure Overview
The project is a static web page structured using <table> tags to lay out various sections of a cycle e-commerce website. It includes a header, hero image, featured bikes, categories, embedded video, promotional banners, and footer details.

🔍 Section-Wise Breakdown
1️⃣ Header Section
Code Block:

html
Copy
Edit
<table border="1" width="100%" style="text-align: center;">
    <thead bgcolor="black" style="color: aliceblue;">
        <tr>
            <th>PURE CYCLE <br><span>LOS ANGELES,CALF,</span></th>
            <th>SINGLE SPEED CITY BIKES ...</th>
            <th><i class="bi bi-search"></i> <i class="bi bi-cart"></i></th>
        </tr>
    </thead>
</table>
Description:

Displays the company name and location.

Provides a product category list.

Includes Bootstrap icons for search and cart.

2️⃣ Hero Image Section
Description:

Displays a full-width banner image of the website.

Draws user attention as the first visual.

3️⃣ Featured Bikes Section
Header Title:

html
Copy
Edit
<th colspan="3" style="font-size: 25px;" height="40px">FEATURED BIKES</th>
Product Layout:

4 bicycles shown with:

Image

Model Name

Brand (Pure Cycle)

Price in red

Call to Action:

html
Copy
Edit
<button>VIEW ALL</button>
4️⃣ Shop by Category Section
Header:

html
Copy
Edit
<td colspan="4" style="font-size: 25px;">Shop By Category</td>
Features:

Displays 4 product categories:

Locks

Helmets

Bags

Accessories

Issue Noted:

Typo in "SECURIT LOCKS" → Should be "SECURITY LOCKS"

"BYCLE HELMETES" → Should be "BICYCLE HELMETS"

5️⃣ Embedded YouTube Video
Code Block:

html
Copy
Edit
<iframe width="100%" height="700px" src="https://www.youtube.com/embed/..."></iframe>
Purpose:

Showcases product or brand promotional content via a video player.

6️⃣ Full-Width Promotional Image
Purpose:

Displays a marketing or branding image below the video section.

7️⃣ Footer Section
Four Columns:

Shop: Bikes, Accessories, placeholders (Test)

Contact: Support details, policies

About: Press, promotional info, warranty

Subscription Box:

Input for email

Social media icons via Bootstrap

Duplicate info for support and policies

Issues Noted:

"EAMIL" → Should be "EMAIL"

Repeated contact details in multiple sections

🛠️ Improvements & Suggestions
Area	Issue	Suggestion
Layout	Tables used for layout	Use semantic HTML (div, section) and CSS Grid/Flexbox
Accessibility	No alt text descriptions	Add meaningful alt attributes
Responsiveness	Static widths	Add responsive meta tags and use % or media queries
Typos	Many spelling errors	Proofread and fix: "CUMMTER" → "COMMUTER", "DEALR" → "DEALER", etc.
Code Structure	No CSS used	External CSS for styling and responsive design recommended

📌 Conclusion
This HTML wireframe serves as a static prototype of a cycle e-commerce site. While basic and functional, enhancements in semantic HTML, responsive design, and spelling accuracy will significantly improve quality and usability.

