# V-Net-
Non-profits are often bogged down by administrative tasks like managing volunteer onboarding, donor agreements and compliance documents. These processes are typically time-consuming and disconnected, leaving organizations less time to focus on their mission.
# V-Net: Empowering Non-Profits with Seamless Document Management 

V-Net is an innovative platform designed to streamline workflows for non-profit organizations. By leveraging DocuSign's powerful APIs, V-Net provides a seamless end-to-end solution for managing documents such as volunteer onboarding forms, donor agreements and compliance records. Our mission is to help non-profits focus on what they do best—creating impact—while we handle the paperwork.

## Inspiration 
Non-profits often struggle with disconnected systems, manual workflows, and inefficient document management. Inspired by their challenges, we built V-Net to provide a centralized, automated platform that simplifies these processes, saving time and resources.

## What it Does 
- Volunteer Onboarding: Automates collection and signing of consent and registration forms. 
- Donor Management: Simplifies donation agreements with embedded signing capabilities. 
- Document Tracking: Provides real-time monitoring of document completion and submission statuses. 
- Data Integration: Unifies previously disconnected data systems into a single platform. 

## How We Built It 
1. Backend: 
   - Python with Flask for managing API integrations and server-side logic. 
   - SQLite for storing metadata and document logs. 

2. APIs: 
   - DocuSign eSignature API: For document preparation, sending and signing. 
   - Monitor API: To track document completion in real-time. 
   - Web Forms API: For simplified form creation and submission. 

3. Frontend: 
   - A responsive web interface using HTML, CSS, and JavaScript. 

4. File Validation: 
   - Integrated file validation for size (5MB max) and aspect ratio (3:2) using **Pillow**. 

## Challenges We Faced 
- Integrating multiple DocuSign APIs into a single platform. 
- Validating files for both size and aspect ratio while maintaining upload efficiency. 
- Designing a user-friendly interface for non-technical users. 

## Accomplishments 
- Delivered a scalable, functional solution within 1200hours. 
- Successfully integrated real-time document tracking using DocuSign Monitor API. 
- Created a user-friendly platform that simplifies workflows for non-profits. 

## What we Learned 
- The power of DocuSign’s ecosystem to solve real-world challenges. 
- Best practices for API integration and workflow optimization. 
- The importance of creating accessible technology for non-technical users. 

## Getting Started 

### Prerequisites 
- Python 3.9+ 
- Flask (`pip install flask`) 
- Pillow (`pip install pillow`) 
- A DocuSign developer account ((https://developers.docusign.com/)). 

### Installation 
1. Clone the repository: 
   ```bash
   git clone https://github.com/Salma-Dev-Ops/v-net.git
   cd v-net

