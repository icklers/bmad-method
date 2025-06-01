# BMAD Getting Started Guide
*5-Minute Quickstart to AI-Driven Development Excellence*

## 🚀 What is BMAD?

BMAD (Breakthrough Method of Agile AI-driven Development) transforms you into a "Vibe CEO" - thinking like a CEO with unlimited resources, using specialized AI agents as your high-powered development team. It's an enterprise-grade methodology that maintains software engineering rigor while dramatically accelerating delivery through intelligent AI orchestration.

## ⚡ Quick Setup (2 minutes)

### 1. **Initialize Your Project**
```bash
# Create your project directory
mkdir my-awesome-project
cd my-awesome-project

# Copy the BMAD agent system to your project root
cp -r /path/to/bmad-agent ./bmad-agent
```

### 2. **Choose Your Environment**
- **🌐 Web UI** (Gemini, ChatGPT): Best for planning, strategy, and document creation
- **💻 IDE** (Cursor, Windsurf): Best for implementation and detailed story work

### 3. **Create Project Structure**
```bash
mkdir docs
mkdir src
touch README.md
```

## 🎯 Your First BMAD Project (3 minutes)

### Phase 1: Ideation & Planning (Web UI Recommended)

#### **Start with Analyst Agent**
*Use when: You have a rough idea but need market validation or deep exploration*

**Prompt Template:**
```
I want to build [YOUR IDEA]. I need help with brainstorming and creating a project brief. 

Please operate as the BMAD Analyst agent and help me:
1. Explore this concept thoroughly
2. Identify target users and market opportunities  
3. Create a comprehensive project brief

Let's start with brainstorming mode.
```

**OR Start with Product Manager**
*Use when: You have a clear concept and are ready for requirements*

**Prompt Template:**
```
I have a clear project concept: [DESCRIBE YOUR PROJECT]

Please operate as the BMAD Product Manager agent and help me create a PRD with epics and stories. Use incremental mode so we can work through this step by step.
```

#### **Continue the Planning Chain**
1. **Analyst** → Creates Project Brief
2. **PM** → Creates PRD with Epics/Stories  
3. **Design Architect** → Creates UI/UX Specification (if UI project)
4. **Architect** → Creates Technical Architecture
5. **Design Architect** → Creates Frontend Architecture (if applicable)
6. **PO** → Validates all documents with master checklist

### Phase 2: Implementation (IDE Recommended)

#### **Setup IDE Agents**
1. **Copy agent files to your IDE:**
   - For dedicated agents: Use `bmad-agent/personas/sm.ide.md` and `dev.ide.md`
   - For orchestrator: Use `ide-bmad-orchestrator.md` with config

2. **Document Sharding** (Critical Step):
```
Please run the doc-sharding-task to break down my PRD and Architecture documents into smaller, manageable files for development.
```

3. **Story Generation & Development:**
```
Please operate as the BMAD Scrum Master and create the next story for development using the create-next-story-task.
```

## 📋 Essential BMAD Principles

### **🎯 "Vibe CEO" Mindset**
- Think big, act decisively
- Your AI agents are your elite team
- You provide strategic oversight and quality control

### **📖 Document-Driven Workflow**
- Each phase produces key artifacts (Project Brief → PRD → Architecture → Stories)
- Documents serve as handoff points between agents
- Quality checklists ensure consistency and completeness

### **🔄 Iterative Excellence**
- "Not a linear process" - expect to revisit and refine
- Use "YOLO mode" for speed, "Incremental mode" for precision
- Embrace changes and course corrections

## 🛠️ Agent Quick Reference

| Agent | When to Use | Primary Output |
|-------|-------------|----------------|
| **Analyst** | Unclear requirements, need research | Project Brief |
| **PM** | Ready to define requirements | PRD with Epics/Stories |
| **Architect** | Need technical design | Architecture Document |
| **Design Architect** | UI/UX focused projects | UI Specs, Frontend Architecture |
| **PO** | Validate documents, manage backlog | Validated artifacts, Stories |
| **SM** | Generate detailed stories | Individual Story files |
| **Dev** | Implement features | Working code |
| **Platform Engineer** | Infrastructure needs | Infrastructure setup |

## 🚦 Decision Tree: Where to Start?

```
Do you have a clear project concept?
├── NO → Start with ANALYST
│   └── Need market research/brainstorming
└── YES → Do you have detailed requirements?
    ├── NO → Start with PRODUCT MANAGER  
    │   └── Create PRD and define scope
    └── YES → Do you have technical architecture?
        ├── NO → Start with ARCHITECT
        │   └── Design technical solution
        └── YES → Start with SCRUM MASTER
            └── Generate implementation stories
```

## ⚠️ Common Pitfalls to Avoid

1. **Skipping the PO validation step** - Always run master checklists
2. **Trying to do everything in one agent session** - Use specialized agents
3. **Not sharding large documents** - Break down PRDs/Architecture for better AI processing
4. **Ignoring quality checklists** - They prevent downstream issues
5. **Rushing through planning** - Quality inputs = quality outputs

## 🎉 Success Indicators

### **After Planning Phase:**
- ✅ Clear Project Brief with defined scope
- ✅ Comprehensive PRD with sequenced epics/stories  
- ✅ Technical architecture with technology decisions
- ✅ All documents pass PO master checklist

### **After Implementation Setup:**
- ✅ Documents sharded into manageable pieces
- ✅ First story generated and validated
- ✅ Development environment ready
- ✅ Clear next steps identified

## 📚 Next Steps

### **For Simple Projects:**
1. Complete planning phase (Web UI)
2. Export documents to your project
3. Switch to IDE for story generation and development

### **For Complex Projects:**
1. Consider multiple planning iterations
2. Use Design Architect for UI-heavy projects
3. Engage Platform Engineer early for infrastructure planning
4. Plan for multiple development cycles

### **Level Up Your BMAD Skills:**
- Explore advanced features like AI frontend prompt generation
- Customize agent personalities for your team style
- Create your own specialized task files
- Contribute improvements back to the BMAD community

## 🆘 Need Help?

- **Agent confused?** Try switching to a more specialized agent
- **Documents too large?** Run the doc-sharding-task
- **Quality issues?** Use the comprehensive checklists  
- **Workflow stuck?** Engage the PO for course correction
- **Technical problems?** The Platform Engineer can help

## 🌟 Walk-Through Example: "TaskTracker Pro"

Let's build a simple task management app together! Follow this example to see BMAD in action.

### **The Scenario**
You have an idea: *"I want to build a task management app that's simpler than existing solutions but has smart AI features."*

### **Step 1: Analyst Agent (Brainstorming)**

**Your Prompt:**
```
I want to build a task management app that's simpler than existing solutions but has smart AI features. I'm not sure about the exact features or target market.

Please operate as the BMAD Analyst agent and help me:
1. Explore this concept through brainstorming
2. Identify the target market and key features
3. Create a project brief

Let's start in brainstorming mode.
```

**Expected Analyst Response:**
- Questions about your vision, pain points with existing tools
- Market research suggestions (competitors, user needs)
- Feature brainstorming (AI task prioritization, smart scheduling)
- Target user identification (busy professionals, students, teams)

**Analyst Output:** `TaskTracker-Pro-Project-Brief.md`

### **Step 2: Product Manager (PRD Creation)**

**Your Prompt:**
```
Based on this project brief for TaskTracker Pro, please operate as the BMAD Product Manager and create a comprehensive PRD with epics and stories. 

Use incremental mode so we can work through each section step by step.
```

**Expected PM Process:**
1. Reviews brief and asks clarifying questions
2. Defines MVP scope (basic task management + one AI feature)
3. Creates 3-4 epics:
   - Epic 1: Core Task Management
   - Epic 2: User Authentication & Setup  
   - Epic 3: AI Smart Prioritization
   - Epic 4: Basic Reporting Dashboard

**PM Output:** `TaskTracker-Pro-PRD.md`

### **Step 3: Architect (Technical Design)**

**Your Prompt:**
```
Based on this PRD for TaskTracker Pro, please operate as the BMAD Architect agent and create the technical architecture.

Use incremental mode and help me make technology decisions for this web application.
```

**Expected Architect Process:**
1. Reviews PRD requirements and technical constraints
2. Recommends tech stack (React + Node.js + PostgreSQL)
3. Designs API structure and data models
4. Creates deployment strategy (Docker + cloud hosting)

**Architect Output:** `TaskTracker-Pro-Architecture.md`

### **Step 4: Design Architect (UI/UX)**

**Your Prompt:**
```
Based on the PRD and Architecture for TaskTracker Pro, please operate as the BMAD Design Architect and create the UI/UX specification.

Focus on a clean, modern interface that emphasizes simplicity.
```

**Expected Design Architect Process:**
1. Creates user flow diagrams (login → dashboard → task creation)
2. Designs information architecture 
3. Specifies component library approach
4. Defines responsive design strategy

**Design Architect Output:** `TaskTracker-Pro-UI-Spec.md`

### **Step 5: Product Owner (Validation)**

**Your Prompt:**
```
Please operate as the BMAD Product Owner and run the master checklist against all TaskTracker Pro documents to ensure they're aligned and ready for development.
```

**Expected PO Process:**
1. Validates PRD completeness and epic sequencing
2. Checks architecture alignment with requirements  
3. Ensures UI spec supports all user stories
4. Identifies any missing dependencies or conflicts

**PO Output:** Validation report + any needed corrections

### **Step 6: Move to IDE (Document Sharding)**

**Your IDE Prompt:**
```
Please run the doc-sharding-task against the TaskTracker Pro PRD and Architecture documents to break them into smaller files for development.
```

**Expected Output:**
- `docs/epic-1.md` (Core Task Management)
- `docs/epic-2.md` (User Authentication)  
- `docs/api-reference.md`
- `docs/data-models.md`
- `docs/tech-stack.md`

### **Step 7: Scrum Master (Story Generation)**

**Your IDE Prompt:**
```
Please operate as the BMAD Scrum Master and create the next story for TaskTracker Pro development using the create-next-story-task.
```

**Expected SM Output:**
- `docs/stories/1.1.story.md` - "User Registration and Login"
  - Clear acceptance criteria
  - Technical guidance for dev
  - Sequenced tasks and subtasks

### **Step 8: Developer (Implementation)**

**Your IDE Prompt:**
```
Please operate as the BMAD Developer agent and implement story 1.1 for TaskTracker Pro.
```

**Expected Dev Process:**
1. Reviews story requirements and technical guidance
2. Sets up project structure per architecture
3. Implements user registration/login functionality
4. Runs tests and validates against story DoD checklist

### **Expected Timeline**
- **Planning Phase (Web UI):** 30-60 minutes  
- **Setup & First Story (IDE):** 45-90 minutes
- **Total to Working MVP:** 2-3 hours vs weeks with traditional methods

### **What You'll Have Built**
- Professional project documentation suite
- Technical architecture ready for scaling
- Working authentication system
- Clear roadmap for remaining features
- Quality-assured, maintainable codebase

---

**Remember:** You're the Vibe CEO. Your AI agents are incredibly capable, but they need your strategic guidance, quality control, and clear direction. Start small, scale fast, and embrace the iterative nature of breakthrough development!

🚀 **Ready to begin your BMAD journey? Try the TaskTracker Pro example or pick your starting agent and let's build something amazing!**
