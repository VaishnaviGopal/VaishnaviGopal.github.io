<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NexusAI: The Cognitive Guardian</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- 
    Chosen Palette: Calm Focus (Light grays, deep navy text, bright blue accents)
    Application Structure Plan: A narrative-driven, single-page application that guides the user through the story of NexusAI. It starts with a hero section to hook the user, presents the core problems with interactive stats, introduces the persona "Priya" to make the problem relatable, then showcases NexusAI through a simulated, interactive "Focus Feed" which is the centerpiece of the application. This is followed by sections detailing the competitive advantage, business impact for IBM, technical architecture, and a clear adoption roadmap. This structure was chosen to be more engaging than a static report, turning passive reading into an active exploration of the solution's value.
    Visualization & Content Choices:
    - Problem Stats (Triage Tax, etc.): Goal is to inform and create impact. Method is dynamic number counters animated with JavaScript to make the stats feel alive.
    - Core Solution Demo: Goal is to demonstrate NexusAI's functionality. Method is a fully interactive "Focus Feed" simulation built with HTML/CSS/JS. Users can filter tasks, see AI summaries, and witness the "Cognitive Guardian" logic in action with a dynamic gauge. This is the most effective way to show, not just tell.
    - Competitive Landscape: Goal is to compare. Method is a clean HTML/CSS table for clarity and easy comparison.
    - Adoption Roadmap: Goal is to show a timeline. Method is a responsive, horizontal timeline built with styled HTML divs.
    - Architecture Diagram: Goal is to inform a technical audience. Method is a diagram recreated using structured HTML divs and Tailwind CSS to avoid external images or SVG.
    CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. 
    -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .gradient-text {
            background: linear-gradient(to right, #2563eb, #3b82f6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .task-card {
            transition: all 0.3s ease-in-out;
        }
        .task-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .control-btn.active {
            background-color: #1d4ed8;
            color: white;
        }
        .diagram-box {
            border: 1px solid #e5e7eb;
            background-color: #f9fafb;
            padding: 0.75rem;
            border-radius: 0.5rem;
            text-align: center;
            font-size: 0.875rem;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        .diagram-arrow {
            display: flex;
            align-items: center;
            justify-content: center;
            color: #9ca3af;
            font-size: 2rem;
            font-weight: bold;
        }
        .arrow-line {
            width: 100%;
            height: 2px;
            background-color: #d1d5db;
        }
        .arrow-head {
            width: 0;
            height: 0;
            border-top: 6px solid transparent;
            border-bottom: 6px solid transparent;
            border-left: 8px solid #d1d5db;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header & Hero Section -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <h1 class="text-xl font-bold text-gray-900">NexusAI</h1>
            <a href="#impact" class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700 transition">Business Value</a>
        </nav>
    </header>

    <main class="container mx-auto px-6 py-12 md:py-20">

        <!-- Hero -->
        <section class="text-center mb-16 md:mb-24">
            <h2 class="text-4xl md:text-6xl font-bold mb-4 text-gray-900">
                A Strategic Agent <br> <span class="gradient-text">to Safeguard Focus and Productivity</span>
            </h2>
            <p class="text-lg md:text-xl text-gray-600 max-w-3xl mx-auto mb-8">
                NexusAI is not just another productivity tool. It's a Cognitive Guardian built on IBM watsonx to help teams reclaim focus, fight burnout, and deliver better results.
            </p>
        </section>

        <!-- The Solution: Interactive Demo -->
        <section id="solution" class="bg-white p-6 md:p-10 rounded-2xl shadow-xl">
            <div class="text-center mb-8">
                <h3 class="text-3xl md:text-4xl font-bold text-gray-900">Introducing NexusAI: The Focus Feed</h3>
                <p class="text-lg text-gray-600 mt-2">Transforming chaos into a calm, prioritized, and actionable feed.</p>
            </div>
            
            <!-- Controls -->
            <div class="flex flex-col md:flex-row justify-between items-center mb-6 gap-4">
                <div class="flex flex-wrap gap-2 justify-center" id="feed-controls">
                    <button data-filter="all" class="control-btn active px-4 py-2 text-sm font-medium rounded-lg bg-blue-500 text-white hover:bg-blue-600 transition">All Tasks</button>
                    <button data-filter="critical" class="control-btn px-4 py-2 text-sm font-medium rounded-lg bg-white text-gray-700 border border-gray-300 hover:bg-gray-100 transition">Critical Only</button>
                    <button data-filter="review" class="control-btn px-4 py-2 text-sm font-medium rounded-lg bg-white text-gray-700 border border-gray-300 hover:bg-gray-100 transition">Needs Review</button>
                     <button id="guardian-toggle" class="px-4 py-2 text-sm font-medium rounded-lg bg-green-100 text-green-800 border border-green-300 hover:bg-green-200 transition">Activate Guardian Mode</button>
                </div>
                <div class="flex items-center gap-3 bg-gray-100 p-2 rounded-lg">
                    <span class="text-sm font-medium text-gray-700">Cognitive Load:</span>
                    <div class="w-32 h-4 bg-gray-300 rounded-full overflow-hidden">
                        <div id="cognitive-load-bar" class="h-full bg-green-500 transition-all duration-500" style="width: 20%;"></div>
                    </div>
                    <span id="cognitive-load-label" class="text-sm font-bold text-green-600">Low</span>
                </div>
            </div>

            <!-- Focus Feed -->
            <div id="focus-feed" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
                <!-- Task cards will be injected here by JavaScript -->
            </div>
            <div id="guardian-message" class="hidden mt-6 p-4 bg-blue-50 border border-blue-200 text-blue-800 rounded-lg text-center"></div>

        </section>

        <!-- The Problem Section -->
        <section id="problem" class="my-20 md:my-24">
            <div class="text-center mb-10">
                <h3 class="text-2xl md:text-3xl font-bold text-gray-900">The Silent Productivity Killers</h3>
                <p class="text-base text-gray-600 mt-2">The modern workflow is broken. Here's why.</p>
            </div>
            <div class="grid md:grid-cols-3 gap-6 text-center">
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h4 class="text-lg font-semibold mb-2 text-gray-900">The Triage Tax</h4>
                    <p class="text-sm text-gray-600">The daily mental effort of sorting through notifications, draining cognitive energy before the real work begins.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h4 class="text-lg font-semibold mb-2 text-gray-900">Context-Switching Penalty</h4>
                    <p class="text-sm text-gray-600">It can take over 20 minutes to fully re-engage with a complex task after just one interruption.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <h4 class="text-lg font-semibold mb-2 text-gray-900">The Burnout Spiral</h4>
                    <p class="text-sm text-gray-600">When conventional tools reward efficiency with more work, accelerating burnout.</p>
                </div>
            </div>
        </section>

        <!-- Why Existing Tools Fail -->
        <section class="my-20 md:my-32">
            <div class="text-center mb-12">
                 <h3 class="text-3xl md:text-4xl font-bold text-gray-900">Why Existing Tools Fall Short</h3>
                 <p class="text-lg text-gray-600 mt-2">They address symptoms, not the root cause.</p>
            </div>
             <div class="max-w-4xl mx-auto overflow-x-auto">
                <table class="w-full text-left border-collapse">
                    <thead>
                        <tr>
                            <th class="p-4 bg-gray-100 font-semibold text-gray-700 rounded-tl-lg">Feature</th>
                            <th class="p-4 bg-gray-100 font-semibold text-gray-700 text-center">Unified Inboxes (Beeper, Shift)</th>
                            <th class="p-4 bg-gray-100 font-semibold text-gray-700 text-center">In-App AI (Slack AI, Copilot)</th>
                            <th class="p-4 bg-blue-100 font-bold text-blue-800 text-center rounded-tr-lg">NexusAI</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr class="border-b border-gray-200">
                            <td class="p-4 font-medium">Consolidate Chaos</td>
                            <td class="p-4 text-center text-green-600 font-bold">✓</td>
                            <td class="p-4 text-center text-gray-400">✗</td>
                            <td class="p-4 text-center text-green-600 font-bold">✓</td>
                        </tr>
                        <tr class="border-b border-gray-200">
                             <td class="p-4 font-medium">Holistic Prioritization</td>
                             <td class="p-4 text-center text-red-500 font-bold">✗</td>
                             <td class="p-4 text-center text-red-500 font-bold">✗</td>
                             <td class="p-4 text-center text-green-600 font-bold">✓</td>
                        </tr>
                        <tr class="border-b border-gray-200">
                             <td class="p-4 font-medium">Proactive Wellness Features</td>
                             <td class="p-4 text-center text-red-500 font-bold">✗</td>
                             <td class="p-4 text-center text-red-500 font-bold">✗</td>
                             <td class="p-4 text-center text-green-600 font-bold">✓</td>
                        </tr>
                        <tr>
                             <td class="p-4 font-medium">Cross-Platform Context</td>
                             <td class="p-4 text-center text-red-500 font-bold">✗</td>
                             <td class="p-4 text-center text-red-500 font-bold">✗</td>
                             <td class="p-4 text-center text-green-600 font-bold">✓</td>
                        </tr>
                    </tbody>
                </table>
             </div>
        </section>

        <!-- Business Impact -->
        <section id="impact" class="my-20 md:my-32 text-center">
            <h3 class="text-3xl md:text-4xl font-bold text-gray-900 mb-12">Business Value for IBM</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <h4 class="text-xl font-semibold mb-2 text-gray-900">Supercharge Internal Teams</h4>
                    <p class="text-gray-600">Reclaim 30-60 minutes per day per employee. At scale, this translates to faster development cycles, quicker incident response, and a significant boost to the bottom line.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <h4 class="text-xl font-semibold mb-2 text-gray-900">Boost Employee Retention</h4>
                    <p class="text-gray-600">By actively reducing cognitive fatigue and after-hours pressure, NexusAI fosters a sustainable, human-first engineering culture that boosts retention and makes IBM an even more attractive employer.</p>
                </div>
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <h4 class="text-xl font-semibold mb-2 text-gray-900">Create a New Commercial Frontier</h4>
                    <p class="text-gray-600">A powerful standalone SaaS offering and a "killer feature" for IBM's existing AI portfolio.</p>
                </div>
            </div>
        </section>

        <!-- Architecture -->
        <section class="my-20 md:my-32">
            <div class="text-center mb-12">
                 <h3 class="text-3xl md:text-4xl font-bold text-gray-900">Architecture: Natively on IBM watsonx</h3>
                 <p class="text-lg text-gray-600 mt-2">Secure, scalable, and intelligent by design.</p>
            </div>
            <div class="max-w-6xl mx-auto p-8 bg-white rounded-xl shadow-lg">
                <div class="grid lg:grid-cols-11 gap-4 items-stretch">
                    
                    <!-- Event Sources -->
                    <div class="lg:col-span-2 flex flex-col justify-center space-y-4">
                        <div class="text-center text-sm font-semibold text-gray-500 mb-2">EVENT SOURCES</div>
                        <div class="diagram-box">Slack</div>
                        <div class="diagram-box">Outlook</div>
                        <div class="diagram-box">ServiceNow</div>
                        <div class="diagram-box">PagerDuty</div>
                    </div>

                    <!-- Arrow 1 -->
                    <div class="lg:col-span-1 flex items-center justify-center">
                        <div class="flex items-center w-full">
                            <div class="arrow-line"></div>
                            <div class="arrow-head"></div>
                        </div>
                    </div>

                    <!-- Core Engine -->
                    <div class="lg:col-span-3 flex flex-col justify-center space-y-4">
                        <div class="text-center text-sm font-semibold text-gray-500 mb-2">CORE ENGINE</div>
                        <div class="diagram-box bg-blue-100 border-blue-200 text-blue-800 p-6">
                            <h5 class="font-bold text-lg">watsonx Orchestrate</h5>
                            <p class="text-sm mt-2">Handles secure connections, event listening, and skill sequencing using its robust, pre-built skill catalog.</p>
                        </div>
                    </div>

                    <!-- Arrow 2 -->
                    <div class="lg:col-span-1 flex flex-col items-center justify-center">
                        <div class="flex items-center w-full transform rotate-90 lg:rotate-0">
                            <div class="arrow-line"></div>
                            <div class="arrow-head"></div>
                        </div>
                        <div class="text-gray-400 text-xs my-2 lg:my-0 lg:mx-2">API Calls</div>
                        <div class="flex items-center w-full transform -rotate-90 lg:rotate-180">
                            <div class="arrow-line"></div>
                            <div class="arrow-head transform rotate-180"></div>
                        </div>
                    </div>

                    <!-- Cognitive Core & UI -->
                    <div class="lg:col-span-4 flex flex-col justify-center space-y-4">
                        <div class="text-center text-sm font-semibold text-gray-500 mb-2">CUSTOM SKILLS & UI</div>
                        <div class="diagram-box bg-indigo-50 border-indigo-200 text-indigo-800 p-4">
                             <h5 class="font-bold">Cognitive Core (on watsonx.ai)</h5>
                             <p class="text-xs mt-1">A set of custom skills powered by Granite foundation models.</p>
                             <ul class="text-xs text-left mt-2 pl-4 list-disc">
                                <li>analyzeAndPrioritize</li>
                                <li>calculateCognitiveLoad</li>
                                <li>summarizeThread</li>
                             </ul>
                        </div>
                         <div class="diagram-box bg-green-50 border-green-200 text-green-800 p-4">
                             <h5 class="font-bold">Focus Feed UI</h5>
                             <p class="text-xs mt-1">Connects directly to Orchestrate to display the prioritized feed and handle user interactions.</p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Adoption Roadmap -->
        <section class="my-20 md:my-32">
             <div class="text-center mb-12">
                 <h3 class="text-3xl md:text-4xl font-bold text-gray-900">Rapid Adoption Roadmap</h3>
            </div>
            <div class="relative max-w-5xl mx-auto">
                <div class="absolute left-1/2 w-0.5 h-full bg-gray-300 hidden md:block"></div>
                <div class="md:grid md:grid-cols-2 md:gap-x-12 space-y-12 md:space-y-0">
                    
                    <div class="md:text-right">
                        <div class="bg-white p-6 rounded-xl shadow-md inline-block md:ml-auto relative">
                            <div class="w-4 h-4 bg-blue-600 rounded-full absolute top-1/2 -translate-y-1/2 -right-9 hidden md:block"></div>
                            <h4 class="font-bold text-blue-600">Phase 1: Pilot</h4>
                            <p class="text-sm text-gray-600">(Weeks 1-4) Deploy to a single development team. The pre-built skills for Slack, Outlook, and ServiceNow allow for immediate connection. The team will see an instant reduction in notification noise and triage time.</p>
                        </div>
                    </div>
                    <div></div>

                    <div></div>
                    <div class="md:text-left">
                        <div class="bg-white p-6 rounded-xl shadow-md inline-block md:mr-auto relative">
                            <div class="w-4 h-4 bg-blue-600 rounded-full absolute top-1/2 -translate-y-1/2 -left-9 hidden md:block"></div>
                            <h4 class="font-bold text-blue-600">Phase 2: Scale</h4>
                            <p class="text-sm text-gray-600">(Weeks 5-12) Roll out to broader Software & Support divisions.Roll out to broader Software and Support divisions. The business value becomes immediately apparent as thousands of productive hours are reclaimed weekly.</p>
                        </div>
                    </div>
                    
                    <div class="md:text-right">
                        <div class="bg-white p-6 rounded-xl shadow-md inline-block md:ml-auto relative">
                            <div class="w-4 h-4 bg-blue-600 rounded-full absolute top-1/2 -translate-y-1/2 -right-9 hidden md:block"></div>
                            <h4 class="font-bold text-blue-600">Phase 3: Enterprise-Wide</h4>
                            <p class="text-sm text-gray-600">NexusAI becomes a standard tool for all knowledge workers at IBM, demonstrating a commitment to a modern, sustainable work culture.</p>
                        </div>
                    </div>
                    <div></div>

                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-8 text-center">
            <p class="font-bold text-lg">NexusAI: The Cognitive Guardian</p>
            <p class="text-gray-400 mt-2">A strategic lever to help IBM scale focus, reduce attrition, and deliver a smarter, more humane future of work.</p>
        </div>
    </footer>


<script>
document.addEventListener('DOMContentLoaded', function() {
    
    // Animate stats on scroll
    const statsElements = document.querySelectorAll('[data-target]');
    const observer = new IntersectionObserver(entries => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                const el = entry.target;
                const target = +el.getAttribute('data-target');
                const suffix = el.textContent.replace(/[0-9]/g, '');
                animateValue(el, 0, target, 1500, suffix);
                observer.unobserve(el);
            }
        });
    }, { threshold: 0.5 });

    statsElements.forEach(el => {
        if(el) observer.observe(el);
    });

    function animateValue(obj, start, end, duration, suffix) {
        let startTimestamp = null;
        const step = (timestamp) => {
            if (!startTimestamp) startTimestamp = timestamp;
            const progress = Math.min((timestamp - startTimestamp) / duration, 1);
            obj.innerHTML = Math.floor(progress * (end - start) + start) + suffix;
            if (progress < 1) {
                window.requestAnimationFrame(step);
            }
        };
        window.requestAnimationFrame(step);
    }

    // Interactive Focus Feed Logic
    const tasks = [
        { id: 1, type: 'pagerduty', title: 'DB CPU at 98% utilization', priority: 'critical', summary: 'Critical alert: The primary database CPU has been over 98% for 5 minutes. Immediate action required to prevent outage.' },
        { id: 2, type: 'slack', user: 'Priya\'s Manager', title: 'Urgent question about Project Phoenix deployment', priority: 'critical', summary: 'Manager needs to know if the fix for T-123 is ready for immediate deployment to production.' },
        { id: 3, type: 'servicenow', title: 'New Ticket: User cannot access billing portal', priority: 'high', summary: 'A high-priority ticket has been assigned regarding a key customer being unable to access their billing information.' },
        { id: 4, type: 'email', user: 'Team Lead', title: 'Review required: New architecture proposal', priority: 'review', summary: 'The draft for the new microservice architecture is ready for your review. Please provide feedback by EOD tomorrow.' },
        { id: 5, type: 'slack', user: 'Teammate', title: 'Quick question about the new API endpoint', priority: 'low', summary: 'A teammate has a non-blocking question about the usage of a newly developed API endpoint.' },
        { id: 6, type: 'email', user: 'HR Department', title: 'Reminder: All-hands meeting this Friday', priority: 'low', summary: 'This is a general reminder for the company-wide all-hands meeting scheduled for this Friday afternoon.' },
        { id: 7, type: 'jira', title: 'Story JIRA-451 moved to "In Progress"', priority: 'low', summary: 'FYI notification that a previously planned story has now been started.'},
    ];

    const feedContainer = document.getElementById('focus-feed');
    const controls = document.getElementById('feed-controls');
    let currentFilter = 'all';

    const platformStyles = {
        pagerduty: { icon: '🚨', color: 'red-100', textColor: 'red-800' },
        slack: { icon: '#', color: 'purple-100', textColor: 'purple-800' },
        servicenow: { icon: '🎫', color: 'blue-100', textColor: 'blue-800' },
        email: { icon: '✉️', color: 'yellow-100', textColor: 'yellow-800' },
        jira: { icon: '📈', color: 'cyan-100', textColor: 'cyan-800'}
    };
    
    function renderFeed() {
        feedContainer.innerHTML = '';
        const filteredTasks = tasks.filter(task => {
            if (currentFilter === 'all') return true;
            if (currentFilter === 'critical') return task.priority === 'critical';
            if (currentFilter === 'review') return task.priority === 'review';
            return true;
        });

        filteredTasks.forEach(task => {
            const style = platformStyles[task.type] || { icon: '🔔', color: 'gray-100', textColor: 'gray-800'};
            const card = document.createElement('div');
            card.className = 'task-card bg-white p-4 rounded-lg border border-gray-200 cursor-pointer';
            card.innerHTML = `
                <div class="flex items-start justify-between">
                    <div class="flex items-center gap-3">
                        <div class="text-xl">${style.icon}</div>
                        <div>
                            <p class="font-semibold text-gray-800">${task.title}</p>
                            ${task.user ? `<p class="text-sm text-gray-500">From: ${task.user}</p>`: ''}
                        </div>
                    </div>
                    <span class="text-xs font-bold px-2 py-1 rounded-full bg-${style.color} text-${style.textColor}">${task.priority}</span>
                </div>
                <div class="summary hidden mt-3 pt-3 border-t border-gray-200">
                    <p class="text-sm text-gray-600">${task.summary}</p>
                </div>
            `;
            feedContainer.appendChild(card);

            card.addEventListener('click', () => {
                const summaryEl = card.querySelector('.summary');
                summaryEl.classList.toggle('hidden');
            });
        });
    }

    controls.addEventListener('click', (e) => {
        if (e.target.tagName === 'BUTTON' && e.target.dataset.filter) {
            currentFilter = e.target.dataset.filter;
            document.querySelectorAll('#feed-controls .control-btn').forEach(btn => btn.classList.remove('active'));
            e.target.classList.add('active');
            renderFeed();
        }
    });
    
    // Cognitive Guardian Logic
    const guardianToggle = document.getElementById('guardian-toggle');
    const cognitiveLoadBar = document.getElementById('cognitive-load-bar');
    const cognitiveLoadLabel = document.getElementById('cognitive-load-label');
    const guardianMessage = document.getElementById('guardian-message');

    let guardianActive = false;
    
    function updateCognitiveLoad(level, text, color, barColor) {
        cognitiveLoadBar.style.width = level;
        cognitiveLoadLabel.textContent = text;
        cognitiveLoadLabel.className = `text-sm font-bold text-${color}-600`;
        cognitiveLoadBar.className = `h-full bg-${barColor}-500 transition-all duration-500`;
    }

    guardianToggle.addEventListener('click', () => {
        guardianActive = !guardianActive;
        if(guardianActive) {
            guardianToggle.textContent = 'Guardian Mode Active';
            guardianToggle.classList.remove('bg-green-100', 'text-green-800', 'border-green-300', 'hover:bg-green-200');
            guardianToggle.classList.add('bg-purple-600', 'text-white', 'border-purple-600');
            
            // Simulate high load
            updateCognitiveLoad('90%', 'High', 'red', 'red');

            // Find a non-critical task to snooze
            const taskToSnooze = tasks.find(t => t.priority === 'low');
            if (taskToSnooze) {
                 guardianMessage.innerHTML = `<strong>Guardian Activated:</strong> The request "${taskToSnooze.title}" is non-urgent. NexusAI has automatically postponed it until Monday morning to protect your focus.`;
                 guardianMessage.classList.remove('hidden');
            }
        } else {
             guardianToggle.textContent = 'Activate Guardian Mode';
             guardianToggle.classList.add('bg-green-100', 'text-green-800', 'border-green-300', 'hover:bg-green-200');
             guardianToggle.classList.remove('bg-purple-600', 'text-white', 'border-purple-600');
             updateCognitiveLoad('20%', 'Low', 'green', 'green');
             guardianMessage.classList.add('hidden');
        }
    });

    // Initial render
    renderFeed();
});
</script>

</body>
</html>
