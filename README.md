Introduction of Invoice Extraction

Invoice data extraction and processing, a critical function of any company’s Accounts Payable department is the process of extracting relevant data from invoices such as invoice number, supplier name, address, amount, etc.; validating the extracted data, uploading it to an ERP software, determining a match (against receipts and POs), and finally initiating payments. 
A systematic invoice data extraction also known as Invoice data capture eliminates backlog and transaction errors, allowing you to close the books smoothly. Invoice data capture is the process of entering invoice information into an accounting system which can be as simple as a paper ledger that keeps track of outgoing payments, suppliers who received them, and payment dates. That would suffice for a small business, but imagine the turmoil such a system would cause in a major global organization.
Paper trails are and will always be necessary for transparency in reporting and auditing; thankfully, we no longer need to use the term “paper” literally in this regard. Instead, teams can now leverage invoice data extraction methods offering safe, dependable, and cost-effective digital paper trails. 

Git Files:
1.Code: It has the actual code to create invoice extracton using google gemini, we need to create our own google gemini api key to utilise their service.
Create your own google gemini api key using thogh this link--> https://aistudio.google.com/app/prompts/new_chat?utm_source=agd&utm_medium=referral&utm_campaign=core-cta&utm_content=
2. requirment.txt: file has all important libraries and packages which needs to be install in your python project to run this application.
3.Input: Which has multiple language input invoice files 
4.Output: Generated output based on input files

Common Challenges in Traditional Invoice Processing
•	Difficulty in managing suppliers beyond a specific scale
•	Payment delays brought on by the laborious vendor matching procedure
•	Poor communication between suppliers and vendors
•	An excessive amount of email and paper necessitates storing and organizing physical files
•	Communication gaps and issues between departments
•	The possibility of payment errors
•	Lack of visibility: Paper-based invoice management makes it difficult to share invoice information with colleagues inside or from other departments
•	Poor scalability: With the growth in scale of operations, manual management of invoices becomes difficult, if not impossible.
Evolution of Invoice Data Extraction Methods
There are three methods for collecting data from invoices: manual data entry, template-based OCR, and AI-enabled automated OCR solutions. All of these methods have their use cases, yet improvements in technological solutions and the evolution of google gemini best practices are leaving some methods obsolete. 
Extracting Data from Invoice or Bills
Consider a scenario where a business receives a multitude of invoices or bills in various formats. Extracting crucial information, such as vendor details, invoice amounts, and due dates, can be time-consuming. Leveraging a multimodal Large Language Model (LLM) like Gemini can streamline this process. By providing the model with image prompts of the invoices, it can intelligently recognize and extract relevant data, transforming the information into a structured format for easy integration into financial systems.
Applications
•	Retail: Extracting data from supplier invoices for inventory management and financial tracking. Streamlining procurement processes and ensuring accurate financial reporting.
•	Healthcare: Parsing medical bills to extract patient information, treatment costs, and insurance details. Enhancing billing accuracy, simplifying insurance claims processing, and improving patient financial management.
•	Manufacturing: Extracting data from supplier invoices for raw materials, labor costs, and logistics expenses. Optimizing cost analysis, inventory management, and supply chain operations.
•	Finance and Accounting Firms: Extracting transaction details and amounts from diverse invoices for auditing purposes. Increasing efficiency in auditing processes, reducing errors, and ensuring compliance.

What are Multimodal LLMs?
Current LLMs mainly focus on text-based interactions which means we are using only single mode of input and output. Multimodal LLMs are expanding the boundaries of current LLMs by allowing us to give inputs beyond text that is image, video, audio, etc. and we can get outputs not only text but image, video, or audio. 
In the past, distinct models were designed for specific media types, such as Imagen, DALL-E, and Stability Diffusion for generating images from text prompts. Simultaneously, dedicated audio models like OpenAI’s Whisper excelled at understanding audio content and generating concise summaries. The landscape has evolved, ushering in a new era of unified models capable of seamlessly handling diverse tasks across multiple mediums. Examples include OpenAI’s ChatGPT-4 and Google’s Gemini, marking a significant leap towards comprehensive AI frameworks that transcend traditional media-centric boundaries.

Gemini Model Series
Gemini, the revolutionary multimodal model family from Google, stands at the forefront of AI innovation. This cutting-edge series demonstrates remarkable progress in natural language understanding, code interpretation, image analysis, audio processing, and video comprehension. Crafted to redefine the limits of AI capabilities, Gemini sets its sights on achieving state-of-the-art performance across a spectrum of benchmarks. With versatility as its hallmark, Gemini seamlessly navigates through multiple modalities, establishing itself as a powerhouse in the realm of artificial intelligence.

Gemini Models 
Gemini is slated to be offered in 3 distinct model sizes as of now. They are – 
1. Gemini Nano: It is a compact version of model which can be run on edge devices. Currently, this model is being used by google on its Pixel Phone can read more about it here. It is Competent in various tasks, including natural language understanding, code interpretation, and basic image and audio comprehension.
2. Gemini Pro: It is the model version which has been made available to public by Google. It is medium scaled model similar to text bison of PaLM model but with several enhanced capabilities. The Gemini Pro model comes currently with 2 variants – one for text input – models/gemini-pro  and other for image-based input along with text – models/gemini-pro-vision.
3. Gemini Ultra: It is the largest model of the Gemini series with large-scale architecture. It can complexly handle video and audio processing tasks and rates high on human expert performance.
