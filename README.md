# Smart India Hackathon Workshop
# Date:28/09/2025
## Register Number:25015718
## Name:POORNIMA J
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
<ol> <li>For this app I would appreciate it to be Affordable, pen-drive–sized IoT “soil pods” distributed to clusters of farmers.</li>
<li>Farmers insert them in their soil once a week in which they measure moisture, pH, NPK levels and   sync data via Bluetooth to any nearby phone.</li>
<li>Instead of every farmer buying, cooperatives or villages can share one pod, making it ultra cost effective.</li>
<li>Advisory delivered in local language & different dialect voice-first system.</li>
<li>Farmers don’t need to read or type just speak on WhatsApp or phone.</li>
<li>Solves inclusivity for low-literate farmers.</li></ol>
<h1>INNOVATION AND UNIQUENESS OF THE SOLUTION</h1>
<ol><li>Not just another app , but soil to cloud network combining IoT  voice-first tech + trust layer.</li>
<li>IoT pods are shared, like community assets.Voice-first and peer validation removes literacy and trust barriers.</li>
<li>Farmers earn more crops than usual because it prevents crops before any catastrophe</li>
<li>For example ,if there is a weather imbalance ,weather would be sensored by those chipand indicates the farmer not to water the crops</li></ol>

## Technical Approach
<h2>PROGRAMIING LANGUAGES</h2>
<ol><li>Java  programming language would be best for multilingual, cross-platform Android-first development.</li>
<li>Text to Speech (Google TTS, Amazon Polly)
<li>Speech to Text (Google Speech API / Vosk offline engine for weak internet)</ol>
<h3>FRAMEWORK</h3>
<ol><li>FastAPI / Flask (for advisory microservices).</li>
<li>TensorFlow / PyTorch (for pest image recognition, crop disease models)</li>
<li>HuggingFace Transformers (for multilingual NLP + voice advisory).</li></ol>
<h4>STORAGE</h4>
<ol><h5>File Storage</h5>
<li>Farmer voice queries, pest/disease images → stored in AWS S3 / Google Cloud Storage.
<li>Offline cache in farmer’s phone → SQLite / Hive (for Flutter).</li>
<h6>Data Storage</h6>
<li>PostgreSQL/MySQL → farmer profiles, farm twin metadata, soil reports.</li>
<li>MongoDB → unstructured advisory logs, chat history.</li>
<li>TimescaleDB / InfluxDB → time-series sensor data from IoT pods.</li></ol>

![alt text](<uzhavan app.png>)

## Feasibility and Viability
<h7>POTENTIAL CHALLENGES AND RISKS</h7>
<ol><li>Economic Impact: Empowering farmers with data-driven advisory can increase productivity and reduce costs, directly improving livelihoods.</li>
<li>Sustainability: Promotes eco-friendly farming practices, reducing chemical misuse.</li>
<li>Food Security: Better yield supports India’s growing food demand.</li>
<li>Equity: Ensures small and marginal farmers—who make up the backbone of Indian agriculture—are not left behind in the digital revolution.</li>
<li>86% of Indian farmers are small or marginal (NABARD Report, 2022).</li>
<li>ICT-based advisories have been shown to increase crop yields by 20–30% in field studies.</li></ol>

<h8>ANALYSIS OF THE FEASIBILITY OF THE IDEA</h8>
<ol>
<li>Ease of Use: Big icons, local languages, voice commands → reduces digital literacy barrier.</li>
<li>Training Needs: Farmers may need short training/demos initially.</li>
<li>Maintenance: Requires a backend team to keep weather data, mandi prices, and advisory content updated.</li></ol>

<h9>STRATEGIES FOR OVERCOMING THESE CHALLENGES</h9>
<ol.>
<li>Government Endorsement: Partner with agriculture departments to certify advisories.</li>
<li>Local Leaders & Panchayats: Use trusted community figures to promote the app.</li>
<li>Farmer Champions: Highlight success stories from early adopters.</li>
<li>Integration with Subsidies: Link app usage with benefits (fertilizer subsidies, crop insurance, or schemes like PM-KISAN).</li></ol>


## Impact and Benefits

<h10>POTENTIAL IMPACTS</h10>
<ol>
<li>Higher Productivity: Better crop selection, sowing time, and pest control increase yields.</li>
<li>Cost Reduction: Optimized fertilizer/pesticide use reduces unnecessary expenses.</li>
<li>Market Awareness: Farmers can compare mandi prices and choose the best place to sell.</li></ol>

<h11>BENEFICIARIES AND BENEFITS</h11>
<ol>
<li>Higher Productivity: Better crop selection, sowing time, and pest control increase yields.</li>
<li>Cost Reduction: Optimized fertilizer/pesticide use reduces unnecessary expenses.</li>
<li>Market Awareness: Farmers can compare mandi prices and choose the best place to sell.</li>
<li>The app strengthens farmers’ livelihoods, saves resources, and protects the environment, while also bridging the digital divide in rural areas.</li></ol>


## Research and Reference
<ol>
<li>https://www.sciencedirect.com/science/article/pii/S2772375524001060</li>
<li>https://www.researchgate.net/publication/362869390_SMART_AGRICULTURE_BASED_IOT_AND_MOBILE_APPS</li>
<li>https://www.mdpi.com/2077-0472/12/10/1745</li></ol>




