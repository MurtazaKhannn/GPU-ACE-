# GPU Cost Optimizer & Recommender ⚡💰

video link : https://drive.google.com/file/d/10beDjq4KupwS2uJMG6w9g-JSCOkYG8E2/view?usp=drive_link

pptlink : https://www.canva.com/design/DAGmYSJHP4U/2i1EcfPmhEzsXoQJqP0kuA/edit?utm_content=DAGmYSJHP4U&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

*A cloud-native tool to recommend optimal GPU instances based on workload requirements and budget, powered by real-time pricing and AI explanations.*

---

## 🚀 **Features**
- **Workload-Aware Recommendations**: Input model type (LLM, CNN), dataset size, and budget to get tailored GPU suggestions.
- **Real-Time Pricing**: Fetches live GPU costs (on-demand/spot) from AceCloud API.
- **Cost Comparisons**: Side-by-side hourly/monthly pricing with savings highlights.
- **AI Explanations**: *(Optional)* Gemini/RAG-powered justifications for recommendations.
- **User-Friendly Dashboard**: Intuitive UI with dark/light mode and export options.

---

## 🛠️ **Tech Stack**
| Category       | Technologies                                                                 |
|----------------|-----------------------------------------------------------------------------|
| **Frontend**   | React.js/Next.js, TypeScript, Tailwind CSS, Chart.js                        |
| **Backend**    | Node.js (Express)        |
| **AI/ML**      | Google Gemini API, LangChain, LLMs                                |
| **DevOps**     | Docker, GitHub Actions (CI/CD)                                              |
| **Testing**    | Jest (backend), Cypress (frontend)                                          |

---

## 📦 **Installation**
1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/gpufe.git
   cd gpufe

## TO RUN THE MAIN.PY FROM FETCHING GPU , CPU AND RAM USAGE make sure to add image name in body using postman You must have docker install in you 
 ```bash
   pip install -r requirements.txt
   python main.py
```
## Set up environment variables:

1. Create .env files for frontend/backend (see .env.example).
2. Add AceCloud API key and Gemini API key (if using AI).

## Run with Docker:
docker-compose up --build

Access the app at http://localhost:3000.

## Usage
1. Input Workload Details:
Select model type, dataset size, and budget.
2. View Recommendations:
Compare GPUs by cost/performance.
Click "Explain" for AI-generated insights.

### **Summary and Highlights**:
1. **Modular Structure**: Clear sections for setup, usage, and customization.
2. **AI/ML Transparency**: Explains how Gemini/RAG works without exposing sensitive data.
3. **Visual Cues**: Icons (⚡, 🤖) and intuitive UI to improve readability. 

## License
MIT License. See LICENSE.

## Credits
Built for AceCloud RTDS Hackathon 2025.
