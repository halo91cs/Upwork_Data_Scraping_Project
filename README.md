# Upwork_Data_Scraping_Project
Data Scraping and Manipulation

<p>I want to create a database of physicians in Florida, divided into different specialties.</p>
<p>All of the data that I want to include is available, but not from one document.</p>
<p>Two lists will be extracted and merged into one document at the end.</p>

<p>All of the licensed physicians in Florida are listed on the Department of Health’s website. (https://appsmqa.doh.state.fl.us/MQASearchServices/HealthCareProviders) It includes the Name, Address, and Personal Email Address for each doctor.</p>

<p>The major insurance companies’ list their providers by specialty. (https://provider.bcbs.com/app/public/#/one/city=&state=&postalCode=&country=&insurerCode=BCBSA_I&brandCode=BCBSANDHF&alphaPrefix=&bcbsaProductId) They list the doctor’s name, address, phone, fax, and usually the website. The only thing missing is the doc's personal email. That resides in the first list.</p>

<p>Scrape_DOH folder contains the exported data from DOH website along with the code for getting practitioners' profiles links and appends those links to the exported data.</p>

<p>Data_Cleaning folder contains some json files which has all information about practitioners in a specific specialty. Currently we have info for Endicronology, Internal Medicine, Otolaryngology, Pulmonology, and Urology specialists. Code basically extracts relevant information that we need from raw Json files and stores them in a csv files for each specialty. .csv files are the output files of the code.</p>

