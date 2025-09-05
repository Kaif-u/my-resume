# my-resume
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohammad Kaif Ansari - Resume</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
        }
        .container {
            max-width: 800px;
        }
        .section-title {
            position: relative;
            display: inline-block;
            margin-bottom: 1rem;
            font-size: 1.5rem;
            font-weight: 600;
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: -5px;
            height: 3px;
            width: 70%;
            background-color: #6366f1;
            border-radius: 999px;
        }
        .icon {
            color: #6366f1;
        }
        .chat-container {
            max-height: 400px;
            overflow-y: auto;
            border-radius: 12px;
            padding: 1rem;
            background-color: #f9fafb;
            box-shadow: inset 0 2px 4px 0 rgba(0, 0, 0, 0.06);
            border: 1px solid #e5e7eb;
        }
        .chat-message {
            margin-bottom: 1rem;
            padding: 0.75rem 1rem;
            border-radius: 12px;
            max-width: 80%;
        }
        .user-message {
            background-color: #e0e7ff;
            color: #1e3a8a;
            margin-left: auto;
            border-bottom-right-radius: 4px;
        }
        .ai-message {
            background-color: #d1fae5;
            color: #065f46;
            margin-right: auto;
            border-bottom-left-radius: 4px;
        }
        .modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 100;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">
    <div class="container mx-auto px-4 py-10">
        <div class="bg-white shadow-xl rounded-2xl overflow-hidden">
            <div class="bg-gradient-to-r from-indigo-500 to-indigo-600 p-8 text-white text-center rounded-t-2xl">
                <h1 class="text-4xl font-bold mb-1">Mohammad Kaif Ansari</h1>
                <p class="text-lg font-medium">Analyst</p>
                <div class="flex flex-col sm:flex-row justify-center items-center mt-4 text-sm font-light">
                    <span class="flex items-center mx-2 my-1 sm:my-0">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1 text-white" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z" />
                            <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />
                        </svg>
                        mohammadkaifansari00@gmail.com
                    </span>
                    <span class="flex items-center mx-2 my-1 sm:my-0">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 mr-1 text-white" viewBox="0 0 20 20" fill="currentColor">
                            <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.774a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.96 18 3 13.04 3 7V5z" />
                        </svg>
                        +91 9935870571
                    </span>
                    <a href="https://linkedin.com/in/mohammadkaifansari" target="_blank" class="flex items-center mx-2 my-1 sm:my-0 text-white hover:text-gray-200 transition-colors">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="h-4 w-4 mr-1">
                            <path d="M19 0H5a5 5 0 00-5 5v14a5 5 0 005 5h14a5 5 0 005-5V5a5 5 0 00-5-5zM8 19H5V8h3v11zM6.5 6.732c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zM20 19h-3v-5.625c0-3.36-4-3.262-4 0V19h-3V8h3v1.895S16.51 8 18 8c2.49 0 4 1.547 4 4.542V19z"/>
                        </svg>
                        LinkedIn
                    </a>
                </div>
            </div>
            <div class="p-8">
                <section class="mb-8">
                    <div class="flex items-center">
                        <h2 class="section-title">Work Experience</h2>
                        <button class="ml-4 px-3 py-1 bg-indigo-500 text-white rounded-full text-sm hover:bg-indigo-600 transition-colors" onclick="readSection('work-experience')">
                            Read Aloud ✨
                        </button>
                    </div>
                    <div id="work-experience" class="space-y-6">
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm transition-transform transform hover:scale-[1.01]">
                            <h3 class="font-bold text-lg text-gray-900">Analyst - HCLTech</h3>
                            <p class="text-sm text-gray-500 mt-1">Sep 2023 - Present | Noida, India</p>
                            <ul class="list-disc list-inside mt-3 text-gray-700 space-y-2">
                                <li>Created end-to-end observability workflows on AWS CloudWatch, Azure Monitor, and SolarWinds for service transparency.</li>
                                <li>Implemented Al-based anomaly detection, intelligent alert routing, and automated runbook generation.</li>
                                <li>Automated log parsing and enrichment with Python, reducing manual checks and improving RCA time.</li>
                                <li>Enhanced BMC Helix ITSM workflows with data-driven prioritization, reducing MTTR by 30%.</li>
                                <li>Applied thresholding and trend checks on key performance metrics (CPU, latency) to reduce noise and improve system health monitoring.</li>
                            </ul>
                        </div>
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm transition-transform transform hover:scale-[1.01]">
                            <h3 class="font-bold text-lg text-gray-900">DBA Intern - HCLTech</h3>
                            <p class="text-sm text-gray-500 mt-1">Apr 2023 - Sep 2023 | Noida, India</p>
                            <ul class="list-disc list-inside mt-3 text-gray-700 space-y-2">
                                <li>Enhanced stored procedures, views, and indexes in MySQL/Oracle/SQL Server environments for query optimization.</li>
                                <li>Automated backup/recovery workflows and SQL performance tuning using Profiler and execution plans.</li>
                                <li>Built dashboards for capacity planning and performance trend analysis in Excel and Power BI.</li>
                            </ul>
                        </div>
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm transition-transform transform hover:scale-[1.01]">
                            <h3 class="font-bold text-lg text-gray-900">Scholar - HCLTech</h3>
                            <p class="text-sm text-gray-500 mt-1">Sep 2022 - Apr 2023 | Lucknow, India</p>
                            <ul class="list-disc list-inside mt-3 text-gray-700 space-y-2">
                                <li>Completed labs simulating cloud deployment, database scaling, and integrated monitoring solutions.</li>
                                <li>Built foundational knowledge in ITIL processes, AWS, Azure fundamentals, and scripting automation.</li>
                            </ul>
                        </div>
                    </div>
                </section>
                <section class="mb-8">
                    <div class="flex items-center">
                        <h2 class="section-title">Skills</h2>
                        <button class="ml-4 px-3 py-1 bg-indigo-500 text-white rounded-full text-sm hover:bg-indigo-600 transition-colors" onclick="readSection('skills')">
                            Read Aloud ✨
                        </button>
                    </div>
                    <div id="skills" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 text-sm">
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm">
                            <p class="font-bold mb-1 text-indigo-600">Programming</p>
                            <p>Python, SQL, Bash, Pandas, APIs, Git</p>
                        </div>
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm">
                            <p class="font-bold mb-1 text-indigo-600">AI/Automation</p>
                            <p>Anomaly Detection, AI Ops, Prompt Engineering, Auto-Remediation, Log Analysis</p>
                        </div>
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm">
                            <p class="font-bold mb-1 text-indigo-600">Cloud/MLOps</p>
                            <p>AWS (EC2, Lambda, CloudWatch), Azure (Monitor, AI Services), CI/CD Concepts</p>
                        </div>
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm">
                            <p class="font-bold mb-1 text-indigo-600">Monitoring/Visualization</p>
                            <p>SolarWinds, BMC Helix ITSM, Excel, Power BI, Google Data Studio</p>
                        </div>
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm">
                            <p class="font-bold mb-1 text-indigo-600">Databases</p>
                            <p>MySQL, Oracle, SQL Server, Stored Procedures, Query Optimization</p>
                        </div>
                        <div class="bg-gray-50 rounded-lg p-4 shadow-sm">
                            <p class="font-bold mb-1 text-indigo-600">Infra/OS</p>
                            <p>Linux (RHEL), Unix, Networking Fundamentals</p>
                        </div>
                    </div>
                </section>
                <section class="mb-8">
                    <div class="flex items-center">
                        <h2 class="section-title">Education & Certifications</h2>
                        <button class="ml-4 px-3 py-1 bg-indigo-500 text-white rounded-full text-sm hover:bg-indigo-600 transition-colors" onclick="readSection('education')">
                            Read Aloud ✨
                        </button>
                    </div>
                    <div id="education" class="space-y-4 text-gray-700">
                        <div class="flex items-center bg-gray-50 rounded-lg p-4 shadow-sm">
                            <span class="icon mr-3">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 20 20" fill="currentColor">
                                    <path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.5 8.283V11a1 1 0 001 1v2.5a.5.5 0 001 0V14a1 1 0 011-1h2a1 1 0 011 1v.5a.5.5 0 001 0V12a1 1 0 001-1V8.283l2.294-1.163a1 1 0 000-1.838l-7-3zM10 14a.5.5 0 00-1 0v.5a.5.5 0 001 0V14z" />
                                </svg>
                            </span>
                            <div>
                                <h3 class="font-bold text-gray-900">Bachelor of Computer Applications</h3>
                                <p class="text-sm">Amity University, 2023 - 2026</p>
                            </div>
                        </div>
                        <div class="flex items-center bg-gray-50 rounded-lg p-4 shadow-sm">
                            <span class="icon mr-3">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 20 20" fill="currentColor">
                                    <path fill-rule="evenodd" d="M4 4a2 2 0 012-2h8a2 2 0 012 2v12a2 2 0 01-2 2h-8a2 2 0 01-2-2V4zm2 2a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1zm1 3a1 1 0 000 2h6a1 1 0 100-2H7zm-1 3a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1z" clip-rule="evenodd" />
                                </svg>
                            </span>
                            <div>
                                <h3 class="font-bold text-gray-900">AWS Certified Cloud Practitioner</h3>
                                <p class="text-sm text-gray-600">Certified since 2024</p>
                            </div>
                        </div>
                        <div class="flex items-center bg-gray-50 rounded-lg p-4 shadow-sm">
                            <span class="icon mr-3">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 20 20" fill="currentColor">
                                    <path fill-rule="evenodd" d="M4 4a2 2 0 012-2h8a2 2 0 012 2v12a2 2 0 01-2 2h-8a2 2 0 01-2-2V4zm2 2a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1zm1 3a1 1 0 000 2h6a1 1 0 100-2H7zm-1 3a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1z" clip-rule="evenodd" />
                                </svg>
                            </span>
                            <div>
                                <h3 class="font-bold text-gray-900">Microsoft Certified: Azure AI Fundamentals</h3>
                                <p class="text-sm text-gray-600">Certified since 2024</p>
                            </div>
                        </div>
                    </div>
                </section>
                <section class="mb-8">
                    <h2 class="section-title">My Achievements</h2>
                    <ul class="list-disc list-inside mt-3 text-gray-700 space-y-2">
                        <li>Received Exceptional Performance Award for 2 consecutive years at HCLTech.</li>
                        <li>Recognized and appreciated by leadership and peers for collaboration, automation initiatives, and delivering consistent results.</li>
                        <li>Designed and automated reporting pipelines, reducing repetitive tasks by 40%.</li>
                        <li>Integrated LLM-based runbooks and AI-driven troubleshooting workflows to improve operational response times.</li>
                    </ul>
                </section>
                <section class="mb-8">
                    <h2 class="section-title">Contact Me</h2>
                    <form id="contactForm" class="bg-gray-50 rounded-lg p-6 shadow-sm space-y-4">
                        <p class="text-sm text-gray-600">Please note: This is a static form and does not send emails. It copies the information to the clipboard.</p>
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700">Name</label>
                            <input type="text" id="name" name="name" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm p-2" required>
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700">Email Address</label>
                            <input type="email" id="email" name="email" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm p-2" required>
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700">Message</label>
                            <textarea id="message" name="message" rows="4" class="mt-1 block w-full rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm p-2" required></textarea>
                        </div>
                        <div class="flex justify-center">
                            <button type="submit" class="w-full sm:w-auto px-6 py-2 border border-transparent text-base font-medium rounded-full shadow-sm text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition-colors">
                                Submit Message
                            </button>
                        </div>
                    </form>
                </section>
                
                <!-- Interactive AI Chat Section -->
                <section>
                    <div class="flex items-center">
                        <h2 class="section-title">Ask a question about my resume ✨</h2>
                        <div id="ai-loading" class="hidden ml-4 text-sm text-gray-500">
                            Thinking...
                        </div>
                    </div>
                    <div id="ai-chat" class="chat-container">
                        <div class="ai-message chat-message">
                            Hello! I am an AI assistant here to help you understand my resume. Ask me anything about my skills or experience.
                        </div>
                    </div>
                    <div class="mt-4 flex space-x-2">
                        <input type="text" id="ai-input" placeholder="e.g., What is your experience with AWS?" class="flex-grow rounded-md border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 sm:text-sm p-2">
                        <button id="ai-ask-btn" class="px-4 py-2 border border-transparent text-sm font-medium rounded-full shadow-sm text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition-colors">
                            Ask
                        </button>
                    </div>
                </section>

                <div class="mt-8 text-center text-gray-500 text-sm">Last updated: September 5, 2025</div>
            </div>
        </div>
    </div>

    <!-- Modal for form submission -->
    <div id="modal" class="modal hidden">
        <div class="bg-white p-8 rounded-lg shadow-xl text-center">
            <h3 class="text-xl font-bold mb-4">Message Sent!</h3>
            <p id="modal-text" class="mb-6 text-gray-700"></p>
            <button id="modal-close" class="px-6 py-2 border border-transparent text-base font-medium rounded-full shadow-sm text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition-colors">
                OK
            </button>
        </div>
    </div>

    <script>
        // Form submission modal
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const form = e.target;
            const name = form.name.value;
            const email = form.email.value;
            const message = form.message.value;

            const contactInfo = `
Name: ${name}
Email: ${email}
Message: ${message}
            `;
            
            const tempTextArea = document.createElement('textarea');
            tempTextArea.value = contactInfo;
            document.body.appendChild(tempTextArea);
            tempTextArea.select();
            
            let modalText = '';
            try {
                const successful = document.execCommand('copy');
                modalText = 'Form data has been copied to the clipboard. You can now paste it into an email or document.';
            } catch (err) {
                modalText = 'Could not copy text automatically. Please copy the form data manually.';
            }
            
            document.body.removeChild(tempTextArea);

            document.getElementById('modal-text').textContent = modalText;
            document.getElementById('modal').classList.remove('hidden');
        });

        document.getElementById('modal-close').addEventListener('click', function() {
            document.getElementById('modal').classList.add('hidden');
        });

        // AI Chat Functionality
        const aiInput = document.getElementById('ai-input');
        const aiAskBtn = document.getElementById('ai-ask-btn');
        const aiChat = document.getElementById('ai-chat');
        const aiLoading = document.getElementById('ai-loading');

        const RESUME_CONTENT = `
        Mohammad Kaif Ansari
        Analyst at HCLTech
        mohammadkaifansari00@gmail.com
        +91 9935870571
        linkedin.com/in/mohammadkaifansari
        
        Work Experience
        Analyst, HCLTech (Sep 2023 - Present):
        - Created end-to-end observability workflows on AWS CloudWatch, Azure Monitor, and SolarWinds for service transparency.
        - Implemented Al-based anomaly detection, intelligent alert routing, and automated runbook generation.
        - Automated log parsing and enrichment with Python, reducing manual checks and improving RCA time.
        - Enhanced BMC Helix ITSM workflows with data-driven prioritization, reducing MTTR by 30%.
        - Applied thresholding and trend checks on key performance metrics (CPU, latency) to reduce noise and improve system health monitoring.
        
        DBA Intern, HCLTech (Apr 2023 - Sep 2023):
        - Enhanced stored procedures, views, and indexes in MySQL/Oracle/SQL Server environments for query optimization.
        - Automated backup/recovery workflows and SQL performance tuning using Profiler and execution plans.
        - Built dashboards for capacity planning and performance trend analysis in Excel and Power BI.
        
        Scholar, HCLTech (Sep 2022 - Apr 2023):
        - Completed labs simulating cloud deployment, database scaling, and integrated monitoring solutions.
        - Built foundational knowledge in ITIL processes, AWS, Azure fundamentals, and scripting automation.
        
        Skills
        Programming: Python, SQL, Bash, Pandas, APIs, Git
        AI/Automation: Anomaly Detection, AI Ops, Prompt Engineering, Auto-Remediation, Log Analysis
        Cloud/MLOps: AWS (EC2, Lambda, CloudWatch), Azure (Monitor, AI Services), CI/CD Concepts
        Monitoring/Visualization: SolarWinds, BMC Helix ITSM, Excel, Power BI, Google Data Studio
        Databases: MySQL, Oracle, SQL Server, Stored Procedures, Query Optimization
        Infra/OS: Linux (RHEL), Unix, Networking Fundamentals
        Soft Skills: Problem-Solving, Stakeholder Communication, Cross-Team Collaboration, Documentation, Ownership
        
        Education
        - Bachelor of Computer Applications, Amity University (2023 - 2026)
        - Class 12th (CBSE Non-Medical), Lucknow Public School and College (2021-2022)
        - Class 10th (CBSE), Lucknow Public School and College (2019-2020), 82%
        
        Certifications
        - AWS Certified Cloud Practitioner
        - Microsoft Certified: Azure AI Fundamentals
        
        Achievements
        - Received Exceptional Performance Award for 2 consecutive years at HCLTech.
        - Designed and automated reporting pipelines, reducing repetitive tasks by 40%.
        - Integrated LLM-based runbooks and AI-driven troubleshooting workflows to improve operational response times.
        `;

        async function sendMessage() {
            const userQuery = aiInput.value.trim();
            if (!userQuery) return;

            // Display user message
            const userMessageDiv = document.createElement('div');
            userMessageDiv.textContent = userQuery;
            userMessageDiv.className = 'chat-message user-message';
            aiChat.appendChild(userMessageDiv);
            aiChat.scrollTop = aiChat.scrollHeight;

            aiInput.value = '';
            aiAskBtn.disabled = true;
            aiLoading.classList.remove('hidden');

            const systemPrompt = "You are an AI assistant for a professional resume. You are grounded in the provided resume text. Respond concisely and professionally, as if you are the person the resume belongs to. Answer questions based ONLY on the resume content. Do not make up information. If the answer is not in the resume, say you cannot answer the question.";
            const apiKey = ""
            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;

            const payload = {
                contents: [{
                    parts: [{
                        text: `Resume:\n${RESUME_CONTENT}\n\nQuestion: ${userQuery}`
                    }]
                }],
                systemInstruction: {
                    parts: [{
                        text: systemPrompt
                    }]
                },
                tools: [{
                    "google_search": {}
                }]
            };

            let retryCount = 0;
            const maxRetries = 3;
            const delay = 1000;

            const fetchWithRetry = async (url, options, retries) => {
                try {
                    const response = await fetch(url, options);
                    if (response.status === 429 && retries > 0) {
                        await new Promise(res => setTimeout(res, delay * (maxRetries - retries + 1)));
                        return fetchWithRetry(url, options, retries - 1);
                    }
                    return response;
                } catch (error) {
                    if (retries > 0) {
                        await new Promise(res => setTimeout(res, delay * (maxRetries - retries + 1)));
                        return fetchWithRetry(url, options, retries - 1);
                    }
                    throw error;
                }
            };
            
            try {
                const response = await fetchWithRetry(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                }, maxRetries);

                if (!response.ok) {
                    throw new Error(`API error: ${response.status}`);
                }

                const result = await response.json();
                const aiResponse = result?.candidates?.[0]?.content?.parts?.[0]?.text || "I'm sorry, I couldn't process that. Please try again.";

                const aiMessageDiv = document.createElement('div');
                aiMessageDiv.textContent = aiResponse;
                aiMessageDiv.className = 'chat-message ai-message';
                aiChat.appendChild(aiMessageDiv);
            } catch (error) {
                console.error('Error fetching from API:', error);
                const errorMessageDiv = document.createElement('div');
                errorMessageDiv.textContent = 'An error occurred. Please try again later.';
                errorMessageDiv.className = 'chat-message ai-message';
                aiChat.appendChild(errorMessageDiv);
            } finally {
                aiAskBtn.disabled = false;
                aiLoading.classList.add('hidden');
                aiChat.scrollTop = aiChat.scrollHeight;
            }
        }

        aiAskBtn.addEventListener('click', sendMessage);
        aiInput.addEventListener('keypress', function(e) {
            if (e.key === 'Enter') {
                sendMessage();
            }
        });

        // Text-to-Speech Functionality
        const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
        let audioSource = null;

        function pcmToWav(pcmData, sampleRate) {
            const numChannels = 1;
            const bytesPerSample = 2; // Signed 16-bit PCM
            const blockAlign = numChannels * bytesPerSample;
            const byteRate = sampleRate * blockAlign;
            const dataSize = pcmData.length * bytesPerSample;
            const buffer = new ArrayBuffer(44 + dataSize);
            const view = new DataView(buffer);

            // RIFF header
            writeString(view, 0, 'RIFF');
            view.setUint32(4, 36 + dataSize, true);
            writeString(view, 8, 'WAVE');

            // fmt chunk
            writeString(view, 12, 'fmt ');
            view.setUint32(16, 16, true);
            view.setUint16(20, 1, true); // format code (1 = PCM)
            view.setUint16(22, numChannels, true);
            view.setUint32(24, sampleRate, true);
            view.setUint32(28, byteRate, true);
            view.setUint16(32, blockAlign, true);
            view.setUint16(34, 16, true); // bits per sample

            // data chunk
            writeString(view, 36, 'data');
            view.setUint32(40, dataSize, true);

            // Write PCM data
            let offset = 44;
            for (let i = 0; i < pcmData.length; i++, offset += 2) {
                view.setInt16(offset, pcmData[i], true);
            }

            return new Blob([view], { type: 'audio/wav' });
        }

        function writeString(view, offset, string) {
            for (let i = 0; i < string.length; i++) {
                view.setUint8(offset + i, string.charCodeAt(i));
            }
        }

        async function readSection(sectionId) {
            if (audioSource) {
                audioSource.stop();
                audioSource.disconnect();
            }

            const sectionElement = document.getElementById(sectionId);
            const textToRead = sectionElement.textContent.replace(/\s+/g, ' ').trim();

            const apiKey = ""
            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-tts:generateContent?key=${apiKey}`;
            const payload = {
                contents: [{
                    parts: [{ text: textToRead }]
                }],
                generationConfig: {
                    responseModalities: ["AUDIO"],
                    speechConfig: {
                        voiceConfig: {
                            prebuiltVoiceConfig: { voiceName: "Kore" }
                        }
                    }
                },
                model: "gemini-2.5-flash-preview-tts"
            };

            const maxRetries = 3;
            const delay = 1000;

            const fetchWithRetry = async (url, options, retries) => {
                try {
                    const response = await fetch(url, options);
                    if (response.status === 429 && retries > 0) {
                        await new Promise(res => setTimeout(res, delay * (maxRetries - retries + 1)));
                        return fetchWithRetry(url, options, retries - 1);
                    }
                    return response;
                } catch (error) {
                    if (retries > 0) {
                        await new Promise(res => setTimeout(res, delay * (maxRetries - retries + 1)));
                        return fetchWithRetry(url, options, retries - 1);
                    }
                    throw error;
                }
            };

            try {
                const response = await fetchWithRetry(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                }, maxRetries);

                if (!response.ok) {
                    throw new Error(`API error: ${response.status} ${response.statusText}`);
                }

                // The TTS model returns a raw binary stream, not JSON.
                const pcmData = await response.arrayBuffer();

                // API returns signed PCM16 audio data, which we need to convert to a Wav blob
                const pcm16 = new Int16Array(pcmData);
                const sampleRate = 16000; // API returns 16kHz
                const wavBlob = pcmToWav(pcm16, sampleRate);
                const audioUrl = URL.createObjectURL(wavBlob);

                const audio = new Audio(audioUrl);
                audio.play();
            } catch (error) {
                console.error('Error with TTS API:', error);
            }
        }
    </script>
</body>
</html>
