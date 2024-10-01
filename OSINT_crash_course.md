## **Using OSINT as a "Poor Man's CRM": Enhancing Your CRM Skillset with Open Source Intelligence**

**Introduction:**  
In the realm of Customer Relationship Management (CRM), access to high-quality, comprehensive information is crucial for success. While CRMs provide powerful tools for managing and analyzing customer data, **Open Source Intelligence (OSINT)** offers an alternative, cost-effective method of gathering actionable intelligence from publicly available sources. OSINT is often referred to as the "poor man's CRM" because it leverages freely accessible data to glean insights about prospects, competitors, and markets.

In this module, we will explore the fundamentals of OSINT, how it can be used to support CRM efforts, and essential techniques to gather information from the web. By understanding how to use OSINT effectively, you can enhance your CRM capabilities, improve lead generation, and perform in-depth research on your customer base.

---

### **1. Mastering the Basics: Performing a Google Search with Advanced Operators**  
One of the most straightforward yet powerful OSINT tools at your disposal is **Google Search**. By using advanced search operators, you can quickly locate specific information about people, companies, competitors, and more. Here’s a breakdown of some key Google search operators that will enhance your research capabilities:

#### **Essential Search Operators**  
| Operator | What it Does | Example |
| -------- | ------------ | ------- |
| " " | Search for an exact word or phrase. | "Steve Jobs" |
| OR | Search for results related to X or Y. | jobs OR gates |
| - | Exclude certain words or phrases. | jobs -apple |
| * | Wildcard matching any word or phrase. | Steve * Apple |
| site: | Search within a specific website. | site:apple.com |
| filetype: | Search for specific file types (e.g., PDFs). | apple filetype:pdf |
| related: | Find websites related to a given domain (competitors). | related:ahrefs.com |
| intitle: | Search for pages with a specific word in the title. | intitle:apple |


#### **Additional Search Operators**  
| Operator | What it Does | Example |
| -------- | ------------ | ------- |
| allintitle:   | Search for pages with multiple words in the title tag.      | allintitle:apple iphone      |
| inurl:        | Search for pages with a particular word in the URL.         | inurl:apple                  |
| allinurl:     | Search for pages with multiple words in the URL.            | allinurl:apple iphone        |
| intext:       | Search for pages with a particular word in their content.   | intext:apple iphone          |
| allintext:    | Search for pages with multiple words in their content.      | allintext:apple iphone       |
| weather:      | Search for the weather in a location.                       | weather:san francisco        |
| stocks:       | Search for stock information for a ticker.                  | stocks:aapl                  |
| map:          | Force Google to show map results.                          | map:silicon valley           |
| movie:        | Search for information about a movie.                       | movie:steve jobs             |
| in            | Convert one unit to another.                                | $329 in GBP                  |
| source:       | Search for results from a particular source in Google News. | apple source:the_verge       |
| before:       | Search for results from before a particular date.           | apple before:2007-06-29      |
| after:        | Search for results from after a particular date.            | apple after:2007-06-29       |

**Pro Tip:** Combining multiple operators can narrow down results to pinpoint exactly what you need. For example, use site:ultimaker.com filetype:pdf to find PDFs on a website that could contain valuable data.

#### **Use Case:** Identifying Competitors  
Use the related: operator to uncover websites related to yours, helping identify competitors and other industry players. Example: related:hubspot.com to find CRM competitors to HubSpot.

---

### **2. OSINT for CRM: Gathering Information with Note-Keeping Tools**  
Properly organizing and managing the information you collect is key to successful OSINT. Below are some open-source and free tools for managing your findings efficiently:

- **KeepNote**: [keepnote.org](http://keepnote.org/)
- **CherryTree**: [giuspen.com/cherrytree](https://www.giuspen.com/cherrytree/)
- **Joplin**: [joplinapp.org](https://joplinapp.org/)
- **Notion**: [notion.so](https://www.notion.so/)
- **OneNote**: [onenote.com](https://onenote.com/)
- **Greenshot**: [getgreenshot.org](https://getgreenshot.org/) – for quick screenshots and annotation.

---

### **3. Introduction to OSINT and Its Role in CRM**  
**What is OSINT?**  
OSINT (Open Source Intelligence) involves collecting and analyzing publicly available information to derive actionable insights. It's widely used in fields such as cybersecurity, law enforcement, and business research. In the context of CRM, OSINT helps gather customer data, monitor competitors, and enrich your knowledge base without breaching privacy or legal boundaries.

**Sources of OSINT**:
- **Internet**: Websites, blogs, forums, social media platforms.
- **Public Records**: Government databases, patents, and registries.
- **Academic Sources**: Open-access publications and research papers.
- **News and Media**: Articles, broadcasts, newspapers.
  
**Application in CRM**: By using OSINT tools and techniques, businesses can gain insights into market trends, customer behavior, and competitive positioning, supplementing the data managed within traditional CRM platforms.

---

### **4. Creating a "Sock Puppet": Fake Identities for OSINT**  
Sometimes, OSINT research requires the creation of a **"sock puppet"**—a fake online identity used to gather information covertly. This can be useful when investigating competitors or monitoring discussions in closed forums without revealing your true identity.

#### **Steps to Create a Fake Identity**:
1. **Generate Fake Personal Information**: Use [Fake Name Generator](https://www.fakenamegenerator.com/) to create a persona with a fake name, address, and more.
2. **Create a Profile Picture**: Use [This Person Does Not Exist](https://www.thispersondoesnotexist.com/) to generate a unique, AI-generated face.
3. **Set Up Email and Phone**: Use services like [Guerrilla Mail](https://www.guerrillamail.com) for temporary email and [TextNow](https://www.textnow.com) or [Google Voice](https://voice.google.com) for virtual phone numbers.
4. **Build an Online Presence**: Create social media profiles (LinkedIn, Facebook, Twitter) to make the identity seem legitimate.
5. **Creating a Fake Company**: [exali.com/e-residency](https://www.exali.com/e-residency-in-estonia/) – Provides a platform to create a digital identity and even start a company in Estonia. While this is a legitimate service, it can be exploited by bad actors to establish a false sense of credibility
6. **Generating a Phone Number**: To create a more convincing fake identity, scammers often generate temporary phone numbers to use for verification purposes. Here are some tools they might use:[Receive SMS Online](https://receive-smss.com), [textnow](https://www.textnow.com), [Twilio](https://www.twilio.com), [Google Voice](https://voice.google.com/u/0/about), [Burner](https://www.burnerapp.com).
7. **Generating a Credit Card**: You can go a step further and hide your financial identity using a proxy. [privacy.com](https://www.privacy.com), Allows users to generate virtual credit cards for online purchases. While the service is intended to protect real credit card information, scammers may use it to create fraudulent financial transactions or establish the appearance of a legitimate company. 
8. **Use VPNs and Proxy Servers**: Ensure that the fake identity’s IP address aligns with its supposed location. Use burner phones and different devices to avoid linking to your personal information.

**Note**: Always adhere to ethical guidelines and legal boundaries when using fake identities for information gathering.

---

### **5. Tools for Gathering and Verifying Information**  
#### **Discovering Email Addresses**:
- **Hunter.io**: Find valid email addresses related to a domain.
- **Phonebook.cz**: Search for a list of email addresses.
- **Clearbit Connect**: Find people and links related to a company site.

#### **Checking Email Validity**:
- Use [Verify Email Address](https://tools.verifyemailaddress.io) to check if an email exists.

#### **Hunting for Breached Credentials**:
Data breaches often expose personal information. You can use these resources to identify if potential leads or competitors have been compromised:
- **Have I Been Pwned**: [haveibeenpwned.com](https://haveibeenpwned.com)
- **DeHashed**: [dehashed.com](https://dehashed.com)

---

### **6. Finding People and Phone Numbers**  
For more targeted CRM efforts, identifying key personnel within organizations can be crucial. These tools help you search for contact information:
- **General**: [Webmii](https://webmii.com), [Epieos](https://epieos.com)
- **US-specific**: [WhitePages](https://www.whitepages.com), [TruePeopleSearch](https://www.truepeoplesearch.com)
- **Social Media**: Use advanced search techniques on LinkedIn, Twitter, and other platforms to find leads and gather background information.

---

### **7. Advanced Techniques: Reverse Image Search and Metadata**  
**Reverse Image Search**: Use profile pictures found online (e.g., LinkedIn) to search for related accounts and uncover additional information.

**Exif Data**: Use tools like [Exif.tools](https://exif.tools) to extract metadata from images. This can reveal information such as the location where a photo was taken, which may assist in geographically targeting prospects.

---

### **Conclusion: OSINT as a Strategic CRM Asset**  
While CRM tools are built to manage customer relationships, **OSINT techniques** empower you to go beyond structured data, enriching your CRM insights with information gleaned from open sources. This approach offers a cost-effective, strategic way to uncover opportunities, understand your market, and build a robust knowledge base for decision-making. Use OSINT wisely and ethically to enhance your CRM processes and achieve a competitive edge.
