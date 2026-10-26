# CrewAI Examples

<h2>Introduction</h2>

Welcome to the official collection of <strong>complete CrewAI applications</strong>. This repository contains end-to-end implementations that showcase how to build real-world applications using CrewAI's framework for orchestrating AI agents.

<blockquote>
  <strong>🍳 Looking for feature-specific tutorials?</strong> Check out the <a href="https://github.com/crewAIInc/crewAI-cookbook">CrewAI Cookbook</a> for focused guides on specific CrewAI features and patterns.
</blockquote>

<h2>What You'll Find Here</h2>

These are <strong>full applications</strong> that demonstrate:

<ul>
  <li>Complete project structures and organization</li>
  <li>Real-world integration patterns (APIs, databases, external services)</li>
  <li>Comprehensive code implementations with error handling</li>
  <li>End-to-end workflows from input to output</li>
  <li>Industry-specific implementations across various domains</li>
</ul>

Each example is a standalone application you can run, modify, and deploy.

<strong>Note:</strong> All examples use <strong>CrewAI version 0.152.0</strong> and <strong>UV package management</strong> for optimal performance and developer experience.

<hr>

<h2>📁 Repository Structure</h2>

<h3>🌊 <a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows">Flows</a></h3>

Advanced orchestration examples using CrewAI Flows for complex workflows with state management.

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/content_creator_flow">Content Creator Flow</a> — Multi-crew content generation system for blogs, LinkedIn posts, and research reports.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/email_auto_responder_flow">Email Auto Responder Flow</a> — Automated email monitoring and response generation.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/lead-score-flow">Lead Score Flow</a> — Lead qualification with human-in-the-loop review.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/meeting_assistant_flow">Meeting Assistant Flow</a> — Meeting notes processing with Trello/Slack integration.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/self_evaluation_loop_flow">Self Evaluation Loop Flow</a> — Iterative content improvement with self-review.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/write_a_book_with_flows">Write a Book with Flows</a> — Automated book writing with parallel chapter generation.</li>
</ul>

<h3>👥 <a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews">Crews</a></h3>

Traditional CrewAI implementations showcasing multi-agent collaboration.

<h4>Content Creation &amp; Marketing</h4>

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/game-builder-crew">Game Builder Crew</a> — Multi-agent team that designs and builds Python games.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/instagram_post">Instagram Post</a> — Creative social media content generation.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/landing_page_generator">Landing Page Generator</a> — Full landing page creation from concepts.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/marketing_strategy">Marketing Strategy</a> — Comprehensive marketing campaign development.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/screenplay_writer">Screenplay Writer</a> — Convert text/emails into screenplay format.</li>
</ul>

<h4>Business &amp; Productivity</h4>

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/job-posting">Job Posting</a> — Automated job description creation.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/prep-for-a-meeting">Prep for a Meeting</a> — Meeting preparation research and strategy.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/recruitment">Recruitment</a> — Automated candidate sourcing and evaluation.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/stock_analysis">Stock Analysis</a> — Financial analysis with SEC data integration.</li>
</ul>

<h4>Data &amp; Research</h4>

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/industry-agents">Industry Agents</a> — Industry-specific agent implementations.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/match_profile_to_positions">Match Profile to Positions</a> — CV-to-job matching with vector search.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/meta_quest_knowledge">Meta Quest Knowledge</a> — PDF-based question-answering system.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/markdown_validator">Markdown Validator</a> — Automated Markdown validation and correction.</li>
</ul>

<h4>Travel &amp; Planning</h4>

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/surprise_trip">Surprise Trip</a> — Personalized surprise travel planning.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/trip_planner">Trip Planner</a> — Destination comparison and itinerary optimization.</li>
</ul>

<h4>Templates</h4>

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/starter_template">Starter Template</a> — Basic template for new CrewAI projects.</li>
</ul>

<h3>🔌 <a href="https://github.com/crewAIInc/crewAI-examples/tree/main/integrations">Integrations</a></h3>

Examples showing CrewAI integration with other platforms and services.

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/CrewAI-LangGraph">CrewAI-LangGraph</a> — Integration with the LangGraph framework.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/azure_model">Azure Model</a> — Using CrewAI with Azure OpenAI.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/nvidia_models">NVIDIA Models</a> — Integration with NVIDIA's AI ecosystem.</li>
</ul>

<h3>📓 <a href="https://github.com/crewAIInc/crewAI-examples/tree/main/Notebooks">Notebooks</a></h3>

Jupyter notebook examples for interactive exploration and learning.

<hr>

<h2>🚀 Getting Started</h2>

<h3>1. Clone the Repository</h3>

```bash
git clone https://github.com/crewAIInc/crewAI-examples.git
cd crewAI-examples
```

<h3>2. Choose an Example Category</h3>

<ul>
  <li>For multi-crew orchestration → Explore <code>/flows</code>.</li>
  <li>For standard crews → Explore <code>/crews</code>.</li>
  <li>For platform integrations → Explore <code>/integrations</code>.</li>
</ul>

<h3>3. Navigate to a Specific Example</h3>

```bash
cd crews/marketing_strategy
```

<h3>4. Install Dependencies with UV</h3>

```bash
uv sync
```

This installs the dependencies and creates the project's virtual environment.

<h3>5. Follow the Example's README</h3>

Each example contains specific setup instructions and usage guides.

<hr>

<h2>📚 Learning Path</h2>

<h3>🌱 Beginners</h3>

Start with these beginner-friendly projects:

<ol>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/starter_template">Starter Template</a> — Learn the basic crew structure.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/instagram_post">Instagram Post</a> — Explore simple content creation.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/job-posting">Job Posting</a> — Understand a straightforward business use case.</li>
</ol>

<h3>⚡ Intermediate</h3>

Explore multi-agent collaboration and external integrations:

<ol>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/marketing_strategy">Marketing Strategy</a> — Multi-agent collaboration.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/self_evaluation_loop_flow">Self Evaluation Loop Flow</a> — Iterative workflows.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/stock_analysis">Stock Analysis</a> — External API integration.</li>
</ol>

<h3>🚀 Advanced</h3>

Deep dive into complex agentic workflows:

<ol>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/content_creator_flow">Content Creator Flow</a> — Multi-crew orchestration with dynamic routing.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/write_a_book_with_flows">Write a Book with Flows</a> — Complex parallel execution.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/lead-score-flow">Lead Score Flow</a> — Human-in-the-loop patterns.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/CrewAI-LangGraph">CrewAI-LangGraph</a> — Framework integration.</li>
</ol>

<hr>

<h2>🛠 Common Patterns</h2>

<ul>
  <li><strong>Configuration:</strong> Most examples use YAML files for agent and task definitions.</li>
  <li><strong>Tools:</strong> Examples showcase integration with APIs, databases, and file systems.</li>
  <li><strong>Flows:</strong> Advanced examples demonstrate state management and orchestration.</li>
  <li><strong>Training:</strong> Several examples include agent training capabilities.</li>
</ul>

<h2>📝 Contributing</h2>

We welcome contributions! Please feel free to submit examples showcasing new use cases or improvements to existing ones.

<h2>📄 License</h2>

This repository is maintained by the CrewAI team. Check individual examples for specific licensing information.

<hr>

<h2>🔗 Related Resources</h2>

<ul>
  <li><a href="https://github.com/crewAIInc/crewAI"><strong>CrewAI Framework</strong></a> — Main CrewAI repository.</li>
  <li><a href="https://github.com/crewAIInc/crewAI-cookbook"><strong>CrewAI Cookbook</strong></a> — Feature-focused tutorials and guides.</li>
  <li><a href="https://docs.crewai.com/"><strong>CrewAI Documentation</strong></a> — Comprehensive documentation.</li>
  <li><a href="https://community.crewai.com/"><strong>CrewAI Community</strong></a> — Join community discussions.</li>
</ul>

<p align="center">
  ⭐ If you find these examples helpful, consider starring the repository!
</p>
