<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24,20,12,6&height=3" width="100%">

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=240&text=Claude%20Course%20Code%20AND%20Co-Work&fontSize=42&fontColor=ffffff&animation=fadeIn" />
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24,20,12,6&height=3" width="100%">

---

# Claude Course
- By the time most people realize it, they’ve wasted weeks hopping between scattered tutorials trying to figure out Claude Code, MCP, or agentic AI.
- So, I made a one-page list of 13 free courses and resources.
- It takes you from beginner-friendly Claude fundamentals to advanced MCP patterns, agent skills, and deploying on AWS Bedrock or Google Vertex AI.
- No more jumping between random tutorials.
- Everything you need to actually build AI apps is in one place.
- Here’s what it covers:
<img width="866" height="1092" alt="image" src="https://github.com/user-attachments/assets/09cc2ca5-7218-4b8b-b34b-05faf87ecfc2" />
<img width="1010" height="1122" alt="image" src="https://github.com/user-attachments/assets/aaca15bc-2dac-4c59-a02e-3c8cd3c43fdd" />

---

# 1. Claude 101
- ✦ Get started with Claude
- Link: https://anthropic.skilljar.com/claude-code-in-action

# 2. Building with the Claude API
- ✦ Full API fundamentals course
- Link: https://anthropic.skilljar.com/claude-with-the-anthropic-api

# 3. Claude Code in Action
- ✦ 21 lessons, free certificate
- Link: https://anthropic.skilljar.com/claude-code-in-action

# 4. Intro to Model Context Protocol
- ✦ Build MCP servers from scratch
- Link: https://anthropic.skilljar.com/introduction-to-model-context-protocol

# 5. MCP: Advanced Topics
- ✦ Production patterns and transport
- Link: https://anthropic.skilljar.com/model-context-protocol-advanced-topics

# 6. Introduction to Agent Skills
- ✦ Build and share reusable Skills
- Link: https://anthropic.skilljar.com/introduction-to-agent-skills

# 7. Claude with Amazon Bedrock
- ✦ Deploy Claude inside AWS
- Link: https://anthropic.skilljar.com/claude-in-amazon-bedrock

# 8. Claude with Google Vertex AI
- ✦ Deploy Claude via Google Cloud
- Link: https://anthropic.skilljar.com/claude-with-google-vertex

# 9. AI Fluency: Framework & Foundations
- ✦ Core AI concepts and responsible use
- Link: https://anthropic.skilljar.com/ai-fluency-framework-foundations

# 10. AI Fluency for Students
- ✦ AI skills for academic success
- Link: https://anthropic.skilljar.com/ai-fluency-for-students

# 11. AI Fluency for Educators
- ✦ Apply AI Fluency in teaching
- Link: https://anthropic.skilljar.com/ai-fluency-for-educators

# 12. AI Fluency for Nonprofits
- ✦ AI skills for mission-driven teams
- Link: https://anthropic.skilljar.com/ai-fluency-for-nonprofits

# 13. Teaching AI Fluency
- ✦ Teach and assess AI Fluency
- Link: https://anthropic.skilljar.com/teaching-ai-fluency
  
---

# Build an AI agent" is too vague to act on :
- Claude Code breaks it into 5 layers. Each one solves what the previous leaves open.

## 𝟭/ 𝗖𝗟𝗔𝗨𝗗𝗘.𝗺𝗱 (𝗠𝗲𝗺𝗼𝗿𝘆 𝗟𝗮𝘆𝗲𝗿)

- > Always loaded. The agent's constitution.
- > Holds architecture rules, naming, test expectations, repo map.
- > Global lives at ~/.claude/CLAUDE.md
- > Project lives at .claude/CLAUDE.md
- > Files are additive. Subfolder CLAUDE.md loads as you enter it.

# 𝟮/ 𝗦𝗸𝗶𝗹𝗹𝘀 (𝗞𝗻𝗼𝘄𝗹𝗲𝗱𝗴𝗲 𝗟𝗮𝘆𝗲𝗿)

- > On-demand, not always-on.
- > Auto-invoked via description matching.
- > Each SKILL.md ships with reference docs, scripts, templates.
-> Body loads only when triggered.
- > Reference material stays nearly free in context.

# 𝟯/ 𝗛𝗼𝗼𝗸𝘀 (𝗚𝘂𝗮𝗿𝗱𝗿𝗮𝗶𝗹 𝗟𝗮𝘆𝗲𝗿)

- > Deterministic scripts. Not AI.
- > Fire at 25 distinct lifecycle events.
- > PreToolUse, PostToolUse, SessionStart, Stop, SubagentStop.
- > Auto-lint on Write, block rm -rf, ping Slack on Stop.
- > Think Git hooks for your agent.

# 𝟰/ 𝗦𝘂𝗯𝗮𝗴𝗲𝗻𝘁𝘀 (𝗗𝗲𝗹𝗲𝗴𝗮𝘁𝗶𝗼𝗻 𝗟𝗮𝘆𝗲𝗿)

- > Each gets own context, model, tools, permissions.
- > Code-reviewer, test-runner, explorer.
- > Main agent delegates, only results come back.
- > Keeps the main context clean.
- > Subagents cannot spawn subagents. No infinite recursion.

# 𝟱/ 𝗣𝗹𝘂𝗴𝗶𝗻𝘀 (𝗗𝗶𝘀𝘁𝗿𝗶𝗯𝘂𝘁𝗶𝗼𝗻 𝗟𝗮𝘆𝗲𝗿)

- > Think npm packages for agent capabilities.
- > Bundle skills, subagents, hooks, commands, MCP servers.
- > Plugin skills are namespaced so multiples coexist.
- > Install once. Reuse across projects and teammates.

# The mental model that ties it together:
- > CLAUDE.md sets the rules. 
- > Skills provide expertise. 
- > Hooks enforce quality. 
- > Subagents delegate work. 
- > Plugins distribute to the team.
<img width="820" height="1120" alt="image" src="https://github.com/user-attachments/assets/4916ec33-c7fe-44a8-bf4d-cd49b6c95aa0" />

# CLAUDE CODE COMMAND 
<img width="962" height="1230" alt="image" src="https://github.com/user-attachments/assets/6db98fcd-9fcd-4a23-a0eb-034e9ceed461" />
<img width="998" height="1206" alt="image" src="https://github.com/user-attachments/assets/df3691d1-7c95-4b88-860d-08a4bd91ab4b" />

---

# Software development is quietly undergoing its biggest shift in decades.
<img width="792" height="924" alt="image" src="https://github.com/user-attachments/assets/449979d5-0ac6-4f66-85cd-189b16f7c52c" />
<img width="896" height="1122" alt="image" src="https://github.com/user-attachments/assets/1b1975be-cd75-41ae-8519-5aa8b2785dc3" />

---

# A single CLAUDE.md is not a Claude Code project. It is a starter file.

- The serious teams using Claude Code in production have a real folder structure with rules, commands, skills, agents, hooks, and MCP integrations. That structure is what turns an AI assistant into a teammate that respects your codebase conventions and your team's workflow.
- Here is what a production Claude Code project actually looks like:
- The Folder Structure
  
<img width="624" height="512" alt="image" src="https://github.com/user-attachments/assets/4827d96b-cfde-4f85-8eb9-df5cb2b7961f" />
<img width="1056" height="1144" alt="image" src="https://github.com/user-attachments/assets/12916ebb-21ea-4fe4-acfa-b9fa7b18f006" />
<img width="1094" height="1124" alt="image" src="https://github.com/user-attachments/assets/da391d6d-983a-492b-a4de-1bd9ce69db6d" />
<img width="1042" height="1310" alt="image" src="https://github.com/user-attachments/assets/d3506c24-974c-4b51-a9e0-2a1d880241fd" />


---

# [Claude Code built the first working version in 4 hours](https://github.com/Ratnesh-181998/Claude-Course/blob/main/Claude%20Code%20PlayBook.pdf)

The lesson wasn't "AI replaced developers."

The lesson was this:
Most people use Claude Code like a chatbot.
Top engineers use it like a teammate.

Here's my practical Claude Code workflow:
1️⃣ Start with a PRODUCT requirement, not a coding task.
❌ Build a dashboard.
✅ Build a dashboard where sales managers can track leads, conversion rates, and revenue in real time.
The quality of the output depends on the clarity of the outcome.

2️⃣ Create a CLAUDE.md file.
This is the biggest unlock.
Include:
• Project overview
• Tech stack
• Coding standards
• Folder structure
• Business rules
• Do's and Don'ts
Claude becomes dramatically more consistent.

3️⃣ Let Claude explore before coding.
I always ask:
"Analyze the codebase first. Identify risks, dependencies, and implementation options before writing code."
This single step prevents hours of rework.

4️⃣ Use Claude for architecture, not just code generation.
My best results come from prompts like:
"Design the complete system architecture and implementation plan."
The code is easy.
The thinking is where the value is.

5️⃣ Make Claude review its own work.
Before accepting any output:
"Act as a senior engineer. Review this implementation. Find bugs, security issues, scalability concerns, and improvements."
The second pass is often better than the first.

6️⃣ Use it on the work you're avoiding.
Not the easy tasks.
The messy integrations.
The undocumented APIs.
The legacy code.
The migration projects.
That's where the biggest ROI lives.


---

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24,20,12,6&height=3" width="100%">


# 📞 **CONTACT & NETWORKING** 📞


## 💼 Professional Networks

[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ratneshkumar1998/)
[![GitHub](https://img.shields.io/badge/🐙_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ratnesh-181998)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/RatneshS16497)
[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white)](https://share.streamlit.io/user/ratnesh-181998)
[![Email](https://img.shields.io/badge/✉️_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rattudacsit2021gate@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@rattudacsit2021gate)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-F58025?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/32068937/ratnesh-kumar)

## 🚀 AI/ML & Data Science  [AI/ML 1620+ Problem Solved](https://github.com/Ratnesh-181998/DSML)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://share.streamlit.io/user/ratnesh-181998)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/RattuDa98)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/rattuda)

## 💻 Competitive Programming [Including all coding plateform's 5000+ Problems/Questions solved](https://github.com/Ratnesh-181998/Algorithms-and-Data-Structures)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Ratnesh_1998/)
[![HackerRank](https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black)](https://www.hackerrank.com/profile/rattudacsit20211)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/ratnesh_181998)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Ratnesh_181998)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/ratnesh1998)
[![HackerEarth](https://img.shields.io/badge/HackerEarth-323754?style=for-the-badge&logo=hackerearth&logoColor=white)](https://www.hackerearth.com/@ratnesh138/)
[![InterviewBit](https://img.shields.io/badge/InterviewBit-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://www.interviewbit.com/profile/rattudacsit2021gate_d9a25bc44230/)


<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24,20,12,6&height=3" width="100%">

## 📊 **GitHub Stats & Metrics** 📊



![Profile Views](https://komarev.com/ghpvc/?username=Ratnesh-181998&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS)



<img 
  src="https://streak-stats.demolab.com?user=Ratnesh-181998&theme=radical&hide_border=true&background=0D1117&stroke=4ECDC4&ring=F38181&fire=FF6B6B&currStreakLabel=4ECDC4"
  alt="GitHub Streak Stats"
width="48%"/>


<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ratnesh-181998&theme=react-dark&hide_border=true&bg_color=0D1117&color=4ECDC4&line=F38181&point=FF6B6B" width="48%" />


<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24,20,12,6&height=3" width="100%">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=4ECDC4&center=true&vCenter=true&width=600&lines=Ratnesh+Kumar+Singh;Data+Scientist+%7C+AI%2FML+Engineer;4%2B+Years+Building+Production+AI+Systems" alt="Typing SVG" />

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=2000&pause=1000&color=F38181&center=true&vCenter=true&width=600&lines=Built+with+passion+for+the+AI+Community+🚀;Innovating+the+Future+of+AI+%26+ML;MLOps+%7C+LLMOps+%7C+AIOps+%7C+GenAI+%7C+AgenticAI+Excellence" alt="Footer Typing SVG" />


<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%">
