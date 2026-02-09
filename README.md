# Advanced Prompt Engineering Training

A comprehensive hands-on training program for mastering prompt engineering fundamentals and advanced techniques, with a focus on Banking, Financial Services, and Insurance (BFSI) applications.

## 📚 Project Overview

This repository contains lab exercises, lecture materials, and sample data for an advanced prompt engineering course. The labs progressively build skills from baseline assessment through debugging, optimization, and advanced context engineering techniques.

## 🎯 Purpose

- **Skill Development**: Hands-on labs for systematic prompt engineering learning
- **Best Practices**: Industry-standard methodologies for AI/LLM integration
- **BFSI Focus**: Real-world scenarios from fraud detection, credit risk, and compliance
- **Production Ready**: Emphasis on reliability, consistency, and auditability

## 📁 Project Structure

```
.
├── notebooks/                    # Jupyter notebooks for interactive labs
│   ├── Lab_1.1_Baseline_Assessment.ipynb
│   ├── Lab_1.2_Prompt_Debugging_Optimization.ipynb
│   ├── Lab_1.3_Advanced_Few_Shot_Learning.ipynb
│   ├── Lab_1.4_Building_Prompt_Template_Libraries.ipynb
│   ├── Lab_1.5_Cross_LLM_Portability.ipynb
│   ├── Lab_2.1_Context_Window_Optimization.ipynb
│   ├── Lab_2.2_Stateful_Conversation_System.ipynb
│   ├── Lab_2.3_Multi_Document_Context_Management.ipynb
│   ├── Lab_2.4_Dynamic_Context_Injection.ipynb
│   ├── Lab_2.5_Advanced_Prompt_Chaining.ipynb
│   └── Lab_2.6_Context_Aware_QA_System_Capstone.ipynb
│
├── data/                       # Sample datasets for labs
│   └── credit_applications.json
│
├── requirements.txt            # Python dependencies
├── .gitignore                 # Git ignore rules
├── LICENSE                    # MIT License
└── README.md                  # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- OpenAI API key with GPT-4 access
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd References
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv env
   ```

3. **Activate the virtual environment**
   - Windows:
     ```bash
     .\env\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source env/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Set up environment variables**
   
   Create a `.env` file in the project root:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

### Running the Labs

1. **Start Jupyter**
   ```bash
   jupyter notebook
   ```

2. **Navigate to the notebooks folder**
   
   Open any lab notebook (e.g., `Lab_1.1_Baseline_Assessment.ipynb`)

3. **Run cells sequentially**
   
   Each lab is self-contained with setup, exercises, and solutions

## 📖 Lab Overview

### Lab 1.1: Baseline Assessment
- **Duration**: 45 minutes
- **Difficulty**: ⭐⭐☆☆☆
- **Topics**: 
  - Current prompt engineering capabilities assessment
  - BFSI credit risk scenario analysis
  - Few-shot learning patterns
  - Structured output generation

### Lab 1.2: Prompt Debugging and Optimization
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐☆☆
- **Topics**:
  - Systematic debugging methodology
  - Common failure patterns (vague outputs, hallucinations)
  - A/B testing framework
  - Performance optimization (cost, latency, accuracy)
  - Context-aware prompt design

### Lab 1.3: Advanced Few-Shot Learning
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐⭐☆
- **Topics**:
  - Few-shot learning fundamentals
  - Example selection strategies (random, balanced, diverse)
  - Contrastive learning with positive and negative examples
  - Dynamic example selection using embeddings
  - Quality vs. quantity optimization
  - Building domain-specific example libraries

### Lab 1.4: Building Prompt Template Libraries
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐☆☆
- **Topics**:
  - Designing reusable prompt templates
  - Variable substitution and validation
  - Composable templates from modular components
  - Template versioning and documentation
  - Production-ready template libraries
  - Searchable template management systems

### Lab 1.5: Cross-LLM Prompt Portability
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐⭐☆
- **Topics**:
  - Model-specific behavior differences
  - Prompt adaptation strategies for multiple providers
  - Provider abstraction layers
  - Testing & validation frameworks
  - Multi-provider fallback systems
  - Cost optimization across providers

### Lab 2.1: Context Window Optimization
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐☆☆
- **Topics**:
  - Token counting and budget management with tiktoken
  - Identifying and eliminating token waste
  - Information density optimization (JSON, tables, key-value)
  - Progressive detail loading strategies
  - Extractive summarization techniques
  - Hierarchical context compression systems

### Lab 2.2: Stateful Conversation Systems
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐⭐☆
- **Topics**:
  - Sliding window buffer memory implementation
  - Conversation summary generation and compression
  - Entity extraction and tracking across conversations
  - Hybrid memory strategies (buffer + summary + entity)
  - Production-ready conversation state managers
  - Token-efficient multi-turn conversation handling

### Lab 2.3: Multi-Document Context Management
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐⭐☆
- **Topics**:
  - Document chunking strategies (fixed-size, semantic)
  - Cross-document entity tracking and linking
  - Document relevance ranking (keyword + semantic)
  - Multi-source answer synthesis
  - Citation and source attribution
  - Production document management systems

### Lab 2.4: Dynamic Context Injection
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐⭐☆
- **Topics**:
  - Query analysis and classification
  - Semantic similarity matching with embeddings
  - Hybrid retrieval (semantic + keyword)
  - Re-ranking and relevance scoring
  - Production context injection pipelines
  - Query caching and optimization

### Lab 2.5: Advanced Prompt Chaining
- **Duration**: 50 minutes
- **Difficulty**: ⭐⭐⭐⭐⭐
- **Topics**:
  - Sequential chain patterns (multi-step workflows)
  - Parallel chain execution (concurrent processing)
  - Conditional branching based on outputs
  - Refinement chains (iterative improvement)
  - Chain orchestration and management
  - Error handling and fallback strategies

### Lab 2.6: Context-Aware Q&A System (Capstone)
- **Duration**: 60 minutes
- **Difficulty**: ⭐⭐⭐⭐⭐
- **Topics**:
  - Integration of all Session 2 techniques
  - Production-ready Q&A system architecture
  - Multi-turn conversation with context management
  - Intelligent context selection and injection
  - System monitoring and health checks
  - Deployment patterns and best practices

## 🔧 Key Technologies

- **LLM**: OpenAI GPT-4
- **Programming**: Python 3.9+
- **Data Analysis**: pandas, numpy
- **Interactive Development**: Jupyter Notebook
- **API Integration**: OpenAI Python SDK

## 📊 Sample Datasets

The `data/` folder contains:
- `credit_applications.json`: Sample credit application data for risk assessment labs
- Additional datasets will be added as labs progress

## 🎓 Learning Path

1. **Session 1**: Prompt Engineering Fundamentals Review
   - Lab 1.1: Baseline Assessment
   - Lab 1.2: Prompt Debugging and Optimization
   - Lab 1.3: Advanced Few-Shot Learning
   - Lab 1.4: Building Prompt Template Libraries
   - Lab 1.5: Cross-LLM Portability

2. **Session 2**: Advanced Context Engineering ✅
   - Lab 2.1: Context Window Optimization ✓
   - Lab 2.2: Stateful Conversation Systems ✓
   - Lab 2.3: Multi-Document Context Management ✓
   - Lab 2.4: Dynamic Context Injection ✓
   - Lab 2.5: Advanced Prompt Chaining ✓
   - Lab 2.6: Context-Aware Q&A System (Capstone) ✓

## 💡 Best Practices

- **Always test systematically**: Use A/B comparisons for optimizations
- **Measure objectively**: Track tokens, latency, accuracy, and cost
- **Iterate incrementally**: Change one variable at a time
- **Validate thoroughly**: Test edge cases before production
- **Document improvements**: Maintain a changelog of optimization impacts

## 🔒 Security & Compliance

- Never commit API keys to version control
- Use environment variables for sensitive data
- Follow BFSI data handling guidelines
- Ensure auditability for all AI-driven decisions
- Validate model outputs before production use

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

This is a training repository. For questions or improvements:
1. Document issues or enhancement ideas
2. Test changes thoroughly with provided datasets
3. Maintain backward compatibility with existing labs
4. Update documentation for any structural changes

## 📧 Support

For technical issues or questions about the labs:
- Review the lab's "Instructor Notes" section
- Check common troubleshooting in individual lab markdown files
- Refer to OpenAI API documentation for API-related issues

## 🔄 Updates

- **v1.0** (2026-02): Initial release with complete Session 1 (Labs 1.1-1.5)
- **v1.1** (2026-02): Added Lab 2.1 - Context Window Optimization
- **v1.2** (2026-02): Added Lab 2.2 - Stateful Conversation Systems
- **v2.0** (2026-02): **Complete Session 2 Release**
  - Lab 2.3: Multi-Document Context Management
  - Lab 2.4: Dynamic Context Injection
  - Lab 2.5: Advanced Prompt Chaining
  - Lab 2.6: Context-Aware Q&A System (Capstone)
  - All Session 2 labs now complete with production-ready implementations

---

**Happy Learning! 🚀**

Master prompt engineering through systematic, hands-on practice with real-world BFSI scenarios.
