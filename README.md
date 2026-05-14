# AI Prompt Roles Collection 🤖

A curated collection of professional AI prompt engineering templates designed to maximize LLM effectiveness across various use cases. Each prompt is carefully crafted with clear instructions, constraints, and best practices.

## 📋 Overview

This repository contains production-ready AI prompts that serve as specialized "roles" for Large Language Models. Each prompt is structured to provide consistent, high-quality outputs while maintaining ethical guidelines and factual accuracy.

## 🎯 Purpose

- **Reusability**: Ready-to-use prompts that can be copied and customized
- **Best Practices**: Incorporates prompt engineering principles and patterns
- **Collaboration**: A living collection that grows with community contributions
- **Learning**: Examples that demonstrate effective prompt construction

## 📁 Repository Structure

```
.
├── README.md
├── prompts/
│   ├── resume-optimizer/
│   │   ├── prompt.md
│   │   └── examples.md
│   ├── code-reviewer/
│   │   ├── prompt.md
│   │   └── examples.md
│   └── [other-roles]/
├── templates/
│   └── prompt-template.md
├── docs/
│   ├── contribution-guide.md
│   └── prompt-engineering-tips.md
└── LICENSE
```

## 🚀 Current Prompts

### 1. Resume Optimizer

**Purpose**: ATS-compliant resume tailoring without fabrication

**Features**:

* Keyword optimization from job descriptions
* 1-page format with 3 bullets per experience
* Maintains 100% factual accuracy
* Handles additional candidate/project context
* ATS-friendly formatting and keyword alignment
* Honest gap analysis between experience and requirements

**Status**: ✅ Complete
**Path**: [`/prompts/resume-optimizer/`](./prompts/resume-optimizer/)

---

### 2. LeetCode Technical Interviewer

**Purpose**: Simulates realistic FAANG-style coding interviews and algorithm practice sessions

**Features**:

* Mock technical interview simulation
* Progressive hint system
* Time and space complexity analysis
* Company-specific interview styles
* Multiple interview modes (mock, guided, rapid-fire)
* Covers DSA topics from easy to hard difficulty

**Status**: ✅ Complete
**Path**: [`/prompts/leetcode-interviewer/`](./prompts/leetcode-interviewer/)


---

*More prompts coming soon...*

## 💡 How to Use

1. **Browse the Collection**: Navigate to `/prompts/` to see all available roles
2. **Copy the Prompt**: Each prompt is in a standalone `.md` file for easy copying
3. **Customize**: Replace placeholder text with your specific inputs
4. **Deploy**: Use with your preferred LLM (ChatGPT, Claude, Gemini, etc.)

### Example Usage

```markdown
1. Open the prompt file (e.g., /prompts/resume-optimizer/prompt.md)
2. Copy the entire prompt structure
3. Replace [bracketed placeholders] with your actual data
4. Paste into your AI assistant
5. Review and iterate on the output
```

## 🏗️ Prompt Structure Philosophy

Each prompt in this collection follows these principles:

- **Clear Role Definition**: Establishes the AI's expertise and purpose
- **Explicit Constraints**: Defines what the AI should and shouldn't do
- **Input Specifications**: Clearly outlines required and optional inputs
- **Process Framework**: Provides step-by-step methodology
- **Output Format**: Specifies expected deliverable structure
- **Examples**: Includes before/after demonstrations where applicable
- **Ethical Guardrails**: Ensures responsible and accurate AI behavior

## 🤝 Contributing

This is a collaborative project! Contributions are welcome and encouraged.

### How to Contribute

1. **Fork** this repository
2. **Create** a new branch (`git checkout -b feature/new-prompt-role`)
3. **Add** your prompt following the template in `/templates/prompt-template.md`
4. **Include** examples and use cases in `examples.md`
5. **Commit** your changes (`git commit -m 'Add: [Prompt Name]'`)
6. **Push** to the branch (`git push origin feature/new-prompt-role`)
7. **Open** a Pull Request

### Contribution Guidelines

- ✅ Follow the established prompt structure template
- ✅ Include clear use cases and examples
- ✅ Ensure ethical considerations are addressed
- ✅ Test the prompt with multiple LLMs if possible
- ✅ Document any limitations or edge cases
- ❌ Don't include prompts that encourage harmful outputs
- ❌ Don't include proprietary or copyrighted content

See [`docs/contribution-guide.md`](./docs/contribution-guide.md) for detailed guidelines.

## 🎓 Prompt Engineering Resources

New to prompt engineering? Check out these resources:

- [Anthropic's Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- [OpenAI's Best Practices](https://platform.openai.com/docs/guides/prompt-engineering)
- **Internal**: [`docs/prompt-engineering-tips.md`](./docs/prompt-engineering-tips.md)

## 📊 Prompt Categories

Prompts are organized by use case:

- **📝 Content Creation**: Writing, editing, content optimization
- **💼 Professional**: Resume, cover letters, business communications
- **💻 Technical**: Code review, debugging, documentation
- **📚 Education**: Tutoring, explanation, curriculum design
- **🔍 Analysis**: Data interpretation, research synthesis
- **🎨 Creative**: Story writing, brainstorming, ideation

## 🔮 Roadmap

Upcoming prompt roles we're planning:

- [ ] Code Reviewer & Debugger
- [ ] Technical Documentation Writer
- [ ] Cover Letter Generator
- [ ] Interview Question Preparer
- [ ] Content SEO Optimizer
- [ ] Email Response Assistant
- [ ] Meeting Notes Summarizer
- [ ] Research Paper Analyzer

**Have an idea?** Open an issue with the `prompt-request` label!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

These prompts are provided as-is for educational and professional use. Always:
- Review AI outputs for accuracy
- Verify factual claims independently
- Ensure outputs comply with your use case requirements
- Follow ethical guidelines for AI usage
- Respect copyright and intellectual property

## 🌟 Acknowledgments

Built collaboratively by the community. Special thanks to all contributors!

## 📬 Contact & Feedback

- **Issues**: Report bugs or request features via [GitHub Issues](../../issues)
- **Discussions**: Share ideas in [GitHub Discussions](../../discussions)
- **Pull Requests**: Contributions welcome!

---

**⭐ If you find this repository helpful, please consider giving it a star!**

*Last Updated: December 2025*
