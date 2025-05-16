作为Web UI专家，请根据下面的Web应用开发架构设计中的前端框架和最佳实践，以及后续的界面描述，为AI提示词优化应用生成用户界面。

下面是架构设计：

## 方案一：React + Vite + TypeScript + Tailwind CSS（前端）& Node.js + Express + TypeScript（后端）

### 技术栈及主流版本（2025年预测）
- 前端：
  - React 18.x
  - Vite 5.x
  - TypeScript 5.x
  - Tailwind CSS 4.x
  - React Router v6.x
- 后端：
  - Node.js 20.x
  - Express 5.x
  - TypeScript 5.x
  - Jest 30.x（测试）
  - pino/winston（日志）

下面是界面描述：

### Overall Layout
The interface follows a two-column layout:

1. **Left Sidebar**:
- Logo/Brand section with "Chat" text and subtitle
- "New session" button with a pen icon
- "History" section with clock icon
- Two history items in Chinese characters

2. **Main Content Area (Right)**:
- Header with "Promptyoo" title
- Descriptive subtitle text
- Form sections for prompt optimization

### Detailed Components

#### Left Sidebar
- Brand section:
  - "Chat" in large text
  - Subtitle: "Optimize prompts to include RABPOC."
- Black in bold "New session" button with pen icon
- History section with grey clock icon
- Two navigation items in Chinese
  - “提示词优化要素”
  - “免费AI工具推荐”

#### Main Content Area
1. **Header Section**:
   - Title: "Promptyoo"
   - Subtitle: "Want high-quality AI responses? I can help you optimize your prompts. Before asking AI a question, simply provide brief answers to these 6 sub-questions that help generate high-quality prompts. Then, I'll ask DeepSeek to generate an excellent prompt based on your answers. You can then copy this prompt to ask AI."

2. **Input Form**:
   - **Role Section**:
     - Label: "R: What role you want AI to play?"
     - Text input field with "Prompt Optimization Expert" as example
   
   - **Audience Section**:
     - Label: "A: What Audience you want AI to generate content for?"
     - Text input field with "AI tool beginners" as example
   
   - **Boundary Section**:
     - Label: "B: What Boundary should AI focus on for this discussion?"
     - Text input field with "Prompt optimization" as example

   - **Purpose Section**:
     - Label: "P: What Purpose you want AI to help you achieve?"
     - Text input field with "find popular prompt optimization tools" as example

   - **Output Section**:
     - Label: "O: What Output format you want AI to generate?"
     - Text input field with "tool name (official website link)" as example

   - **Concern Section**:
     - Label: "C: What Concern you have about this discussion with AI?"
     - Text input field with "AI hallucinations (if not found, please be honest and don't make up information)" as example

3. **Action Area**:
   - Blue "Optimize Prompt" button

4. **Output Section**:
   - Gray background section
   - Label: "Optimized Prompt"
   - Helper text: "Your optimized prompt will be displayed here. Optimize your prompt now!"