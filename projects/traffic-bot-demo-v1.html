<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Traffic Bot Showcase - Charlie Sim Portfolio</title>
    <!-- React & ReactDOM -->
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <!-- Babel for JSX -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <!-- Tailwind CSS (for rapid styling) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        body { 
            font-family: 'Inter', sans-serif; 
            background: linear-gradient(135deg, #4f46e5 0%, #7c3aed 100%);
            min-height: 100vh;
            padding: 20px;
            color: #1f2937;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            color: white;
            margin-bottom: 40px;
        }

        .header h1 {
            font-size: 3rem;
            font-weight: 800;
            margin-bottom: 15px;
            text-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .header p {
            font-size: 1.25rem;
            opacity: 0.9;
            max-width: 800px;
            margin: 0 auto;
        }

        .card {
            background: white;
            border-radius: 16px;
            padding: 30px;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            margin-bottom: 30px;
        }

        /* Tab Navigation */
        .phase-tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 30px;
            border-bottom: 2px solid #e5e7eb;
            overflow-x: auto;
            padding-bottom: 2px;
        }

        .phase-tab {
            padding: 12px 24px;
            background: none;
            border: none;
            border-bottom: 3px solid transparent;
            cursor: pointer;
            font-size: 1rem;
            font-weight: 600;
            color: #6b7280;
            transition: all 0.2s;
            white-space: nowrap;
        }

        .phase-tab:hover {
            color: #4f46e5;
        }

        .phase-tab.active {
            color: #4f46e5;
            border-bottom-color: #4f46e5;
        }

        /* Pipeline Visuals */
        .pipeline-visual {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin: 30px 0;
            padding: 20px;
            background: #f9fafb;
            border-radius: 12px;
            flex-wrap: wrap;
            gap: 20px;
        }

        .pipeline-step {
            flex: 1;
            text-align: center;
            min-width: 150px;
        }

        .step-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 15px;
            background: linear-gradient(135deg, #4f46e5 0%, #7c3aed 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            color: white;
            box-shadow: 0 4px 6px rgba(79, 70, 229, 0.4);
            transition: all 0.3s ease;
        }

        .step-icon.active {
            transform: scale(1.1);
            box-shadow: 0 10px 15px rgba(79, 70, 229, 0.5);
        }

        .arrow {
            font-size: 2rem;
            color: #d1d5db;
        }

        /* Slack Demo Specifics */
        .slack-container {
            border: 1px solid #e5e7eb;
            border-radius: 12px;
            overflow: hidden;
            height: 600px;
            display: flex;
            flex-direction: column;
            background: white;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            position: relative; /* For cursor positioning */
        }

        .slack-sidebar { background-color: #3F0E40; color: #cfc3cf; }
        .channel-active { background-color: #1164A3; color: white; }
        .channel-item:hover:not(.channel-active) { background-color: #350d36; }
        
        .ephemeral-border { border-left: 3px solid #616061; }
        
        /* Code Block */
        .code-block {
            background: #1f2937;
            color: #e5e7eb;
            padding: 20px;
            border-radius: 8px;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
            line-height: 1.6;
            overflow-x: auto;
            margin: 15px 0;
            position: relative;
        }

        .code-label {
            position: absolute;
            top: 10px;
            right: 10px;
            background: #374151;
            color: #9ca3af;
            padding: 4px 10px;
            border-radius: 4px;
            font-size: 0.75rem;
        }

        .info-box {
            background: #eff6ff;
            border-left: 4px solid #3b82f6;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        /* Fake Cursor */
        .fake-cursor {
            position: absolute;
            width: 20px;
            height: 20px;
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='none' viewBox='0 0 24 24' stroke='black' stroke-width='2'%3E%3Cpath stroke-linecap='round' stroke-linejoin='round' d='M3 3l7.07 16.97 2.51-7.39 7.39-2.51L3 3z' /%3E%3C/svg%3E");
            background-size: contain;
            background-repeat: no-repeat;
            pointer-events: none;
            z-index: 50;
            transition: all 0.5s ease-out;
            filter: drop-shadow(2px 2px 2px rgba(0,0,0,0.3));
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fade-in { animation: fadeIn 0.5s ease-out forwards; }

        @media (max-width: 768px) {
            .pipeline-visual { flex-direction: column; }
            .arrow { transform: rotate(90deg); margin: 10px 0; }
            .header h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>
    <div id="root"></div>

    <script type="text/babel">
        const { useState, useEffect, useRef } = React;

        // --- Demo Data & Config ---
        const ESCAPE_TERMS = ["!ignore", "#announce", "📌", ":pushpin:"];
        const KEYWORDS = {
            support: ["error", "fail", "broken", "bug", "issue", "crash", "trouble", "exception", "not working", "doesn't work", "wifi", "password"],
            question: ["how to", "how do i", "how can", "what is", "where can", "question", "help", "anyone know"]
        };

        const INITIAL_CHANNELS = {
            "product-updates": [
                { id: 1, user: "Charlie Sim", avatar: "CS", time: "2:00 PM", text: "🚀 **Major Launch:** The new Reporting Dashboard is live! Big thanks to the engineering team.", type: "message" }
            ],
            "support-bugs": [
                { id: 101, user: "Sarah Engineer", avatar: "SE", time: "10:30 AM", text: "Looking into the redis latency issue now.", type: "message" }
            ],
            "product-questions": [
                { id: 201, user: "New Hire", avatar: "NH", time: "9:15 AM", text: "Where do we keep the API docs?", type: "message" }
            ]
        };

        const App = () => {
            const [activeTab, setActiveTab] = useState(1);
            
            // Slack Demo State
            const [activeChannel, setActiveChannel] = useState("product-updates");
            const [channels, setChannels] = useState(INITIAL_CHANNELS);
            const [inputValue, setInputValue] = useState("");
            const [ephemeralMsg, setEphemeralMsg] = useState(null);
            
            // Animation State
            const [isPlaying, setIsPlaying] = useState(false);
            const [cursorPos, setCursorPos] = useState({ x: 50, y: 50, visible: false });
            
            const chatEndRef = useRef(null);

            useEffect(() => {
                chatEndRef.current?.scrollIntoView({ behavior: "smooth" });
            }, [channels, ephemeralMsg, activeChannel]);

            // --- Traffic Bot Logic ---
            const handleSendMessage = (textOverride = null) => {
                const text = textOverride || inputValue;
                if (!text.trim()) return;

                const textLower = text.toLowerCase();
                if (!textOverride) setInputValue("");

                // 1. Only monitor #product-updates
                if (activeChannel !== "product-updates") {
                    postMessage(activeChannel, text);
                    return;
                }

                // 2. Escape Hatch
                if (ESCAPE_TERMS.some(term => textLower.includes(term))) {
                    postMessage(activeChannel, text);
                    return;
                }

                // 3. Keyword Detection
                let targetChannel = null;
                let reason = null;

                if (KEYWORDS.support.some(kw => textLower.includes(kw))) {
                    targetChannel = "support-bugs";
                    reason = "It looks like you're reporting a technical issue";
                } else if (KEYWORDS.question.some(kw => textLower.includes(kw))) {
                    targetChannel = "product-questions";
                    reason = "It looks like you have a question";
                }

                if (targetChannel) {
                    // Slight delay for bot reaction
                    setTimeout(() => {
                        setEphemeralMsg({ originalText: text, targetChannel, reason });
                    }, 600);
                } else {
                    postMessage(activeChannel, text);
                }
            };

            const postMessage = (channel, text, user = "You", avatar = "YO", isBot = false) => {
                setChannels(prev => ({
                    ...prev,
                    [channel]: [
                        ...prev[channel],
                        {
                            id: Date.now(),
                            user, avatar,
                            time: new Date().toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' }),
                            text, type: "message", isBot
                        }
                    ]
                }));
            };

            const handleMove = () => {
                if (!ephemeralMsg) return;
                
                // 1. Remove from current (simulated by just posting to new and showing success)
                // In real slack it stays or user deletes, we'll simulate the "move" flow
                
                const msgToMove = ephemeralMsg;
                
                // Post to new channel
                setChannels(prev => ({
                    ...prev,
                    [msgToMove.targetChannel]: [
                        ...prev[msgToMove.targetChannel],
                        {
                            id: Date.now(),
                            user: "Moved by You",
                            avatar: "YO",
                            time: new Date().toLocaleTimeString([], { hour: '2-digit', minute: '2-digit' }),
                            text: msgToMove.originalText,
                            type: "message",
                            isBot: false
                        }
                    ],
                    // Show success in old channel
                    [activeChannel]: [
                        ...prev[activeChannel],
                        { id: Date.now(), type: "ephemeral-success", text: `✅ Your message has been posted to #${msgToMove.targetChannel}.` }
                    ]
                }));
                setEphemeralMsg(null);
            };

            // --- Auto Play Scenario Logic ---
            const runScenario = async () => {
                if (isPlaying) return;
                setIsPlaying(true);
                
                // Reset
                setChannels(INITIAL_CHANNELS);
                setActiveChannel("product-updates");
                setEphemeralMsg(null);
                setInputValue("");
                
                const wait = (ms) => new Promise(res => setTimeout(res, ms));
                
                // 1. Move cursor to input
                setCursorPos({ x: '50%', y: '90%', visible: true });
                await wait(1000);
                
                // 2. Type message
                const messageToType = "Hey, does anyone know where the guest wifi password is?";
                for (let i = 0; i <= messageToType.length; i++) {
                    setInputValue(messageToType.substring(0, i));
                    await wait(30); 
                }
                await wait(500);
                
                // 3. Hit enter (simulate)
                handleSendMessage(messageToType);
                setInputValue("");
                await wait(1500); // Wait for bot to appear
                
                // 4. Move cursor to "Move" button
                // We'll estimate position based on UI layout
                setCursorPos({ x: '35%', y: '75%', visible: true }); 
                await wait(1000);
                
                // 5. Click "Move"
                // Simulate click effect
                setCursorPos(prev => ({ ...prev, scale: 0.9 }));
                setTimeout(() => setCursorPos(prev => ({ ...prev, scale: 1 })), 100);
                await wait(200);
                handleMove();
                await wait(1500);
                
                // 6. Move cursor to sidebar to switch channel
                setCursorPos({ x: '15%', y: '45%', visible: true }); // rough position of #product-questions
                await wait(1000);
                
                // 7. Click channel
                setCursorPos(prev => ({ ...prev, scale: 0.9 }));
                setTimeout(() => setCursorPos(prev => ({ ...prev, scale: 1 })), 100);
                await wait(200);
                setActiveChannel("product-questions");
                
                await wait(2000);
                setCursorPos(prev => ({ ...prev, visible: false }));
                setIsPlaying(false);
            };

            return (
                <div className="container">
                    <div className="header">
                        <h1>🚦 Traffic Bot</h1>
                        <p>How I automated Slack etiquette to save our product announcement channel from noise, bugs, and chaos.</p>
                    </div>

                    <div className="card">
                        <div className="section-title text-xl font-bold mb-4 text-gray-800">
                            💡 The Problem: Signal vs. Noise
                        </div>
                        <div className="grid md:grid-cols-2 gap-6 mb-6">
                            <div className="bg-red-50 p-6 rounded-lg border-l-4 border-red-500">
                                <h3 className="text-red-800 font-bold mb-2">❌ Before: The Dumping Ground</h3>
                                <p className="text-red-700 text-sm leading-relaxed">
                                    Our <code>#product-updates</code> channel was supposed to be for major launches. Instead, it was buried under:
                                </p>
                                <ul className="list-disc ml-5 mt-2 text-red-700 text-sm">
                                    <li>"Is the wifi down?"</li>
                                    <li>"Found a bug in login!"</li>
                                    <li>"Where are the docs?"</li>
                                </ul>
                            </div>
                            <div className="bg-green-50 p-6 rounded-lg border-l-4 border-green-500">
                                <h3 className="text-green-800 font-bold mb-2">✅ After: Automated Traffic Control</h3>
                                <p className="text-green-700 text-sm leading-relaxed">
                                    Traffic Bot silently monitors the channel. When it detects off-topic messages, it <strong>privately</strong> nudges users to the right place.
                                </p>
                                <ul className="list-disc ml-5 mt-2 text-green-700 text-sm">
                                    <li>Zero public shaming</li>
                                    <li>One-click to move messages</li>
                                    <li>90% reduction in noise</li>
                                </ul>
                            </div>
                        </div>

                        {/* Pipeline Visual */}
                        <div className="pipeline-visual">
                            <div className={`pipeline-step cursor-pointer`} onClick={() => setActiveTab(1)}>
                                <div className={`step-icon ${activeTab === 1 ? 'active' : ''}`}>👂</div>
                                <div className="font-bold mt-2">The Listener</div>
                                <div className="text-sm text-gray-500">Monitors Messages</div>
                            </div>
                            <div className="arrow">→</div>
                            <div className={`pipeline-step cursor-pointer`} onClick={() => setActiveTab(2)}>
                                <div className={`step-icon ${activeTab === 2 ? 'active' : ''}`}>🧠</div>
                                <div className="font-bold mt-2">The Brain</div>
                                <div className="text-sm text-gray-500">Analyzes Intent</div>
                            </div>
                            <div className="arrow">→</div>
                            <div className={`pipeline-step cursor-pointer`} onClick={() => setActiveTab(3)}>
                                <div className={`step-icon ${activeTab === 3 ? 'active' : ''}`}>👋</div>
                                <div className="font-bold mt-2">The Nudge</div>
                                <div className="text-sm text-gray-500">Ephemeral Action</div>
                            </div>
                        </div>

                        {/* Navigation Tabs */}
                        <div className="phase-tabs">
                            <button className={`phase-tab ${activeTab === 1 ? 'active' : ''}`} onClick={() => setActiveTab(1)}>1. The Logic</button>
                            <button className={`phase-tab ${activeTab === 2 ? 'active' : ''}`} onClick={() => setActiveTab(2)}>2. The Code</button>
                            <button className={`phase-tab ${activeTab === 3 ? 'active' : ''}`} onClick={() => setActiveTab(3)}>3. Live Demo</button>
                        </div>

                        {/* TAB CONTENT */}
                        <div className="min-h-[400px]">
                            {activeTab === 1 && (
                                <div className="animate-fade-in">
                                    <h3 className="text-xl font-bold mb-4">Designing a Friendly Bot</h3>
                                    <p className="mb-4 text-gray-600">
                                        The key insight was that <strong>rules don't work</strong>. People don't read pinned messages. 
                                        We needed a bot that wasn't a guard, but a guide.
                                    </p>
                                    
                                    <div className="bg-gray-100 p-6 rounded-lg mb-6">
                                        <h4 className="font-bold mb-3">Decision Flow</h4>
                                        <div className="space-y-3">
                                            <div className="flex items-center">
                                                <div className="bg-white px-3 py-1 rounded shadow text-sm font-mono">Event: New Message</div>
                                                <div className="mx-2">→</div>
                                                <div className="bg-purple-100 px-3 py-1 rounded shadow text-sm font-mono">Is Bot?</div>
                                                <div className="mx-2 text-gray-400">Yes → Ignore</div>
                                            </div>
                                            <div className="flex items-center">
                                                <div className="w-8"></div>
                                                <div className="mx-2">↓ No</div>
                                            </div>
                                            <div className="flex items-center">
                                                <div className="w-8"></div>
                                                <div className="bg-purple-100 px-3 py-1 rounded shadow text-sm font-mono">Contains "!ignore"?</div>
                                                <div className="mx-2 text-gray-400">Yes → Ignore (Escape Hatch)</div>
                                            </div>
                                            <div className="flex items-center">
                                                <div className="w-8"></div>
                                                <div className="mx-2">↓ No</div>
                                            </div>
                                            <div className="flex items-center">
                                                <div className="w-8"></div>
                                                <div className="bg-blue-100 px-3 py-1 rounded shadow text-sm font-mono">Contains "bug/fail"?</div>
                                                <div className="mx-2 text-green-600 font-bold">Yes → Suggest #support-bugs</div>
                                            </div>
                                        </div>
                                    </div>
                                    
                                    <div className="info-box">
                                        <p className="text-blue-800">
                                            <strong>Key Feature: The Escape Hatch</strong><br/>
                                            If a CTO needs to post "We found a critical bug", the bot shouldn't stop them. 
                                            Including <code>!ignore</code> or <code>📌</code> bypasses all checks.
                                        </p>
                                    </div>
                                </div>
                            )}

                            {activeTab === 2 && (
                                <div className="animate-fade-in">
                                    <h3 className="text-xl font-bold mb-4">Python + Slack Bolt + Google Cloud Functions</h3>
                                    <p className="mb-4 text-gray-600">
                                        The implementation is stateless and serverless. It costs $0 to run because it only wakes up when a message is posted.
                                    </p>

                                    <div className="code-block">
                                        <span className="code-label">main.py</span>
                                        <pre>{`@app.message()
def handle_message(message, say):
    text = message.get('text', '').lower()
    user_id = message['user']
    
    # 1. The Escape Hatch
    if any(term in text for term in ["!ignore", "#announce", "📌"]):
        return

    # 2. Logic Engine
    if any(kw in text for kw in ["bug", "error", "fail"]):
        target = "support-bugs"
        reason = "It looks like you're reporting a technical issue"
        
        # 3. The Gentle Nudge (Ephemeral)
        say(
            channel=message['channel'],
            user=user_id,
            ephemeral=True,  # Only visible to user
            blocks=[
                {
                    "type": "section",
                    "text": {"type": "mrkdwn", "text": f"👋 Hey! {reason}."}
                },
                {
                    "type": "actions",
                    "elements": [
                        {
                            "type": "button",
                            "text": {"type": "plain_text", "text": f"Move to #{target}"},
                            "action_id": "move_message"
                        }
                    ]
                }
            ]
        )`}</pre>
                                    </div>
                                </div>
                            )}

                            {activeTab === 3 && (
                                <div className="animate-fade-in">
                                    <div className="flex justify-between items-center mb-4">
                                        <h3 className="text-xl font-bold">Interactive Demo</h3>
                                        <div className="flex gap-2">
                                            <button 
                                                onClick={runScenario} 
                                                disabled={isPlaying}
                                                className={`text-sm px-4 py-2 rounded-full font-bold transition-all shadow-sm ${isPlaying ? 'bg-gray-100 text-gray-400' : 'bg-green-600 text-white hover:bg-green-700'}`}
                                            >
                                                {isPlaying ? '▶️ Playing...' : '▶️ Play Scenario (Watch Bot Action)'}
                                            </button>
                                        </div>
                                    </div>
                                    
                                    {/* SLACK DEMO UI */}
                                    <div className="slack-container relative">
                                        
                                        {/* Fake Cursor Element */}
                                        {cursorPos.visible && (
                                            <div 
                                                className="fake-cursor" 
                                                style={{ 
                                                    left: cursorPos.x, 
                                                    top: cursorPos.y,
                                                    transform: `scale(${cursorPos.scale || 1})`
                                                }}
                                            ></div>
                                        )}

                                        <div className="flex w-full h-full text-sm">
                                            {/* Sidebar */}
                                            <div className="w-[220px] slack-sidebar flex flex-col flex-shrink-0">
                                                <div className="p-4 border-b border-[#5d2c5d] font-bold text-white text-lg">Acme Corp ▼</div>
                                                <div className="p-4 flex-1">
                                                    <div className="mb-4 text-opacity-70 text-white font-medium">Channels</div>
                                                    <ul>
                                                        {Object.keys(channels).map(channel => (
                                                            <li 
                                                                key={channel}
                                                                onClick={() => { if(!isPlaying) { setActiveChannel(channel); setEphemeralMsg(null); } }}
                                                                className={`px-2 py-1 rounded cursor-pointer mb-1 flex items-center ${activeChannel === channel ? 'channel-active' : 'text-gray-300 hover:bg-[#350d36]'}`}
                                                            >
                                                                <span className="opacity-70 mr-1">#</span> {channel}
                                                            </li>
                                                        ))}
                                                    </ul>
                                                </div>
                                            </div>

                                            {/* Main Chat */}
                                            <div className="flex-1 flex flex-col bg-white">
                                                <div className="h-14 border-b flex items-center px-5 justify-between bg-white flex-shrink-0">
                                                    <div className="font-bold text-gray-800">#{activeChannel}</div>
                                                </div>

                                                <div className="flex-1 overflow-y-auto p-5 space-y-4 bg-white">
                                                    {channels[activeChannel].map((msg) => (
                                                        <div key={msg.id} className={`flex ${msg.type === 'ephemeral-success' ? 'opacity-70 bg-gray-50 p-2 rounded' : ''}`}>
                                                            <div className="w-9 h-9 rounded bg-gray-200 flex items-center justify-center font-bold text-gray-600 flex-shrink-0 mr-3">
                                                                {msg.isBot ? "🤖" : msg.type === 'ephemeral-success' ? "✓" : msg.avatar}
                                                            </div>
                                                            <div className="flex-1">
                                                                <div className="flex items-baseline mb-1">
                                                                    <span className="font-bold mr-2">{msg.isBot ? "Traffic Bot" : msg.user}</span>
                                                                    {msg.isBot && <span className="bg-blue-100 text-blue-700 text-[10px] px-1 rounded font-bold mr-2">APP</span>}
                                                                    <span className="text-xs text-gray-500">{msg.time}</span>
                                                                </div>
                                                                <div className="text-gray-800" dangerouslySetInnerHTML={{ __html: msg.text }} />
                                                            </div>
                                                        </div>
                                                    ))}

                                                    {/* Ephemeral Message */}
                                                    {ephemeralMsg && activeChannel === 'product-updates' && (
                                                        <div className="flex mt-2 animate-fade-in">
                                                            <div className="w-9 h-9 rounded bg-blue-500 flex items-center justify-center text-white font-bold flex-shrink-0 mr-3 shadow-md">🚦</div>
                                                            <div className="flex-1">
                                                                <div className="flex items-baseline mb-1">
                                                                    <span className="font-bold mr-2">Traffic Bot</span>
                                                                    <span className="bg-blue-100 text-blue-700 text-[10px] px-1 rounded font-bold mr-2">APP</span>
                                                                    <span className="text-xs text-gray-500">Only visible to you</span>
                                                                </div>
                                                                <div className="bg-gray-50 border border-gray-200 rounded p-3 ephemeral-border shadow-sm">
                                                                    <p className="mb-2">👋 <strong>Hey! {ephemeralMsg.reason}.</strong></p>
                                                                    <p className="mb-3 text-gray-600">To keep <b>#product-updates</b> clean, please move this.</p>
                                                                    <div className="flex gap-2">
                                                                        <button onClick={handleMove} className="bg-green-600 hover:bg-green-700 text-white font-semibold py-1 px-3 rounded text-xs transition-colors">Move to #{ephemeralMsg.targetChannel}</button>
                                                                        <button onClick={() => setEphemeralMsg(null)} className="bg-white border border-gray-300 text-gray-700 hover:bg-gray-50 py-1 px-3 rounded text-xs transition-colors">Dismiss</button>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    )}
                                                    <div ref={chatEndRef} />
                                                </div>

                                                <div className="p-4 pt-0">
                                                    <form onSubmit={(e) => { e.preventDefault(); handleSendMessage(); }} className="border border-gray-300 rounded-lg p-2 flex items-center shadow-sm">
                                                        <input
                                                            type="text"
                                                            value={inputValue}
                                                            onChange={(e) => setInputValue(e.target.value)}
                                                            placeholder={`Message #${activeChannel}`}
                                                            className="flex-1 outline-none text-gray-700 px-2"
                                                            disabled={isPlaying}
                                                        />
                                                        <button type="submit" disabled={!inputValue.trim() || isPlaying} className={`p-2 rounded ${inputValue.trim() ? 'bg-green-600 text-white' : 'bg-gray-100 text-gray-400'}`}>
                                                            ➤
                                                        </button>
                                                    </form>
                                                    <div className="text-xs text-gray-400 mt-2 text-center">
                                                        {!isPlaying && 'Try: "The site is down", "How do I use the API?", or "Critical update !ignore"'}
                                                        {isPlaying && 'Watching automated scenario...'}
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            )}
                        </div>
                    </div>

                    <div className="card">
                        <h2 className="text-2xl font-bold mb-4">📈 The Impact</h2>
                        <div className="grid md:grid-cols-4 gap-4 text-center">
                            <div className="p-4 bg-blue-50 rounded-lg">
                                <div className="text-3xl font-bold text-blue-600 mb-1">90%</div>
                                <div className="text-sm text-blue-800">Noise Reduction</div>
                            </div>
                            <div className="p-4 bg-green-50 rounded-lg">
                                <div className="text-3xl font-bold text-green-600 mb-1">0</div>
                                <div className="text-sm text-green-800">User Complaints</div>
                            </div>
                            <div className="p-4 bg-purple-50 rounded-lg">
                                <div className="text-3xl font-bold text-purple-600 mb-1">$0</div>
                                <div className="text-sm text-purple-800">Running Cost</div>
                            </div>
                            <div className="p-4 bg-orange-50 rounded-lg">
                                <div className="text-3xl font-bold text-orange-600 mb-1">3hrs</div>
                                <div className="text-sm text-orange-800">Saved Weekly</div>
                            </div>
                        </div>
                    </div>
                </div>
            );
        };

        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(<App />);
    </script>
</body>
</html>
